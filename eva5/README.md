# evaluación 5 "trabajo de clase"

## 1- GO Y CODESPACES
1- crear un repositorio en github con el nombre:
programacion-segura, archivo main.go hola mundo

```go
package main

import (
	"fmt"
)

func main() {
    var mundo = "Mundo ok"
    const var_const = "constante"

    fmt.Print("hola mundo")
	fmt.Printf("hola %v\n", mundo)
	fmt.Println("hello",var_const)
}
```

para inicializar el modulo en go
```bash	
go mod init github.com/nombre_usuario/nombre_carpeta
```

2- configuración de codespaces con tiempo de espera y tiempo de eliminación



## SERVIDOR GO

```GO
package main

import (
    "fmt"
    "net/http"
)

func helloHandler(w http.ResponseWriter, r *http.Request) {
    fmt.Fprintf(w, "Hola Mundo")
}

func main() {
    http.HandleFunc("/", helloHandler)
    
    fmt.Println("Servidor iniciado en http://localhost:8080")
    http.ListenAndServe(":8080", nil)
}
```

```go
  // Servir archivos estáticos desde el directorio "static"
    fs := http.FileServer(http.Dir("./static"))
    http.Handle("/", fs)
```


## material referencia:


### docker
 video introductorio:
 >https://youtu.be/9eTVZwMZJsA?si=WqJKtYMj_11odqqk

### github codespace 
video introductorio:
>https://youtu.be/cO-oFpePy3c?si=Ev9z3ju-mardgkB2
- documentación oficial codespace:
https://docs.github.com/es/codespaces/overview


- costos:
https://docs.github.com/es/billing/managing-billing-for-your-products/managing-billing-for-github-codespaces/about-billing-for-github-codespaces

- ver codespaces creados
https://github.com/codespaces

- configurar la herramienta codespace

## GO (GOLANG)

- pagina oficial
go.dev

- lenguaje de programación go
video primeros pasos:
>https://youtu.be/D30UWujqftU?si=oD75sQmmSysblE9P

- para búsqueda de lenguaje go por **GOLANG**

- para finalizar la ejecución del código se presiona 
**ctrl + c**


## notas red
- puertos importantes
 80 http
 443 https
 22 ssh

 ## notas GIT GITHUB
 - para clonar un repositorio u trabajar de forma local se usa el comando git clone + ruta del repo ej:
 ```bash
 git clone https://github.com/NOMBRE_USUARIO_GITHUB/programacion-segura.git
 ```

grupos (2p):

1. Rafael Martorell - Juan Beleño

2. Catalina Toledo - Diego Gonzalez 

3. Jose Aylwin - Pedro Flores

4. Benjamin Uribe - Luis Zañartu

5. Francisco Villa - Daniel Romero

6. Sebastian Olivera - Jose Chavez


