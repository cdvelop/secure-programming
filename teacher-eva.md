Estructura de una clase de 15 minutos sobre Programación Segura:
Objetivo: Demostrar conocimiento práctico sobre programación segura y OWASP Top 10.

Público: Evaluadores para un puesto de profesor de programación.

Formato: Clase práctica y dinámica.

Duración: 15 minutos.

1. Introducción (2 minutos):

Presentación breve y concisa: Nombre, experiencia como ingeniero informático y entusiasmo por la enseñanza.

Enfoque de la clase: "Hoy, en vez de una clase tradicional, vamos a simular una situación real de desarrollo aplicando un concepto del OWASP Top 10."

que es el OWASP Top 10?
El OWASP Top 10 es una lista estándar de las 10 vulnerabilidades de seguridad más críticas en aplicaciones web, publicada por la Open Web Application Security Project (OWASP). Esta lista se actualiza periódicamente y es considerada como el estándar de facto para la seguridad de aplicaciones web.

Las vulnerabilidades incluyen:
1. Inyección (SQL, NoSQL, etc.)

// Ejemplo vulnerable a inyección SQL
func getUserData(username string) {
    db, _ := sql.Open("mysql", "user:password@/dbname")
    query := "SELECT * FROM users WHERE username = '" + username + "'"
    rows, _ := db.Query(query)
    // Este código es vulnerable a inyección SQL
    // Un atacante podría usar: admin' OR '1'='1

    // Versión segura usando parámetros preparados:
    safeQuery := "SELECT * FROM users WHERE username = ?"
    safeRows, _ := db.Query(safeQuery, username)
}
    
    
2. Autenticación rota
    Se refiere a vulnerabilidades en los mecanismos de autenticación que permiten a los atacantes comprometer contraseñas, tokens u otros elementos para asumir la identidad de otros usuarios.
    
    Ejemplo de código vulnerable:
    
    def login(username, password):
        # Almacenamiento de contraseña en texto plano (inseguro)
        stored_password = "password123"  
        if password == stored_password:
            return "Login exitoso"
       
    Versión segura:
    
    import bcrypt
    
    def secure_login(username, password):
        # Contraseña hasheada almacenada
        hashed = bcrypt.hashpw(password.encode(), bcrypt.gensalt())
        # Verificación segura
        if bcrypt.checkpw(password.encode(), hashed):
            return "Login exitoso"
    
3. Exposición de datos sensibles
        Se refiere a la exposición accidental de datos sensibles, como contraseñas, tokens de acceso, información de tarjetas de crédito, etc.
4. Entidades XML externas (XXE)
        Se refiere a la explotación de la capacidad de una aplicación para procesar documentos XML externos.
        

5. Control de acceso roto
6. Configuración de seguridad incorrecta
7. Cross-Site Scripting (XSS)
8. Deserialización insegura
9. Uso de componentes con vulnerabilidades conocidas
10. Registro y monitoreo insuficientes

Esta lista ayuda a desarrolladores y organizaciones a priorizar los riesgos de seguridad más importantes al desarrollar aplicaciones web.
