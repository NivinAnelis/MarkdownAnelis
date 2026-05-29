# Notas de clases de Programación II
# Anelis Azucena Nivin Mendoza

## prjPoliRetos


## Cuaderno de apuntes en Markdown para las clases

Apuntes realizados durante las clases de Programación II utilizando Java, Git y GitHub.

# Class I : Git

## Primer programa en Java

* cd ..
* ls -la
* cd prjGit
* ls -la
* code . : abrir el repositorio en Visual Studio Code
* touch Hi.java Suma.java : crear archivos Java
* ls
* rm Hi.java Suma.java : eliminar archivos repetidos
* history : visualizar historial de comandos
* mkdir doc : crear una carpeta

## Programa Hello World en Java

```java
public class Hi {

    public static void main(String[] args) {

        System.out.println("Hi, welcome to Java programming!");
        System.out.println("This is my first Java program.");

    }

}
```

Este programa representa la estructura básica de Java y permite comprobar el correcto funcionamiento del compilador.

## Programa de suma en Java

```java
public class Suma {

    public static void main(String[] args) {

        int num1 = 7;
        int num2 = 770;

        int suma = num1 + num2;

        System.out.println("La suma es: " + suma);

    }

}
```

En este programa se utilizan variables enteras, operaciones matemáticas y salida de datos por consola.

# Class II : GitHub

## Comandos Linux

* pwd : muestra la ruta actual
* cd : permite cambiar de directorio
* ls -la : lista archivos ocultos y visibles
* wsl : ejecutar entorno Linux
* exit : salir de terminal
* touch readme.md : crear archivo markdown
* code readme.md : editar archivo markdown

## Conectar repositorio con GitHub

```bash
git remote -v
git remote add origin URL
git push -u origin main
```

Estos comandos permiten conectar el repositorio local con GitHub para subir cambios y mantener respaldo del proyecto.

## Git commands

### Comandos principales

* git clone : descargar un repositorio remoto
* git init : inicializar Git en el proyecto
* git status : revisar estado del repositorio
* git add . : agregar todos los cambios
* git commit -m "" : guardar cambios con un mensaje
* git push : subir cambios a GitHub
* git pull : actualizar proyecto desde GitHub

## Flujo básico de Git

```bash
git init
git status
git add .
git commit -m "Primer commit"
git push
```

## Si git push no está conectado a GitHub

```bash
git remote add origin URL
git push -u origin main
```

El parámetro `-u` permite guardar la conexión entre el repositorio local y el remoto.

# Markdown

Markdown permite crear documentación organizada y fácil de leer.

## Insertar imágenes

```md
![Titulo](ruta/iPmagen.png)
```

## Texto en negrita

```md
**Texto importante**
```

## Encabezados

```md
# Titulo principal
## Subtitulo
### Encabezado pequeño
```

# Introducción a Java

Java es uno de los lenguajes de programación más utilizados actualmente. Se caracteriza por ser orientado a objetos y compatible con múltiples plataformas.

Java diferencia mayúsculas y minúsculas, por lo que es importante escribir correctamente nombres de clases y variables.

## Estructura básica de Java

```java
public class Main {

    public static void main(String[] args) {

    }

}
```

### Explicación

* class : define una clase
* main : método principal de ejecución
* {} : delimitan bloques de código
* ; : finaliza instrucciones

# Variables en Java

## Tipos de datos

```java
int
float
double
String
boolean
```

Las variables permiten almacenar información dentro del programa.

# Condicionales y ciclos

## Ejemplo utilizando for e if

```java
for (int i = 0; i < 10; i++) {

    if (i % 2 == 0) {

        System.out.println("+");

    } else {

        System.out.println("-");

    }

}
```

### Explicación

* for : repite instrucciones
* if : evalúa condiciones
* else : ejecuta una alternativa
* % : obtiene el residuo de una división

# Algoritmia

La algoritmia consiste en desarrollar soluciones lógicas mediante una serie de pasos organizados.

## Formas de representar algoritmos

* Pseudocódigo
* Diagramas de flujo
* Código fuente
* Pruebas de escritorio

# Diagramas de Flujo

Los diagramas de flujo permiten representar gráficamente la lógica de un programa.

## Tipos de diagramas

* Vertical
* Horizontal
* Panorámico
* Arquitectónico

Todo diagrama debe tener:

* Inicio
* Proceso
* Fin

# Programación Orientada a Objetos (POO)

La POO organiza los programas mediante:

* clases
* objetos
* atributos
* métodos

## Modificadores de acceso

```java
public
private
protected
```

# Controlador en Java

Cuando existen muchas clases dentro de un proyecto, se utiliza una clase llamada `Controlador` para organizar y ejecutar los diferentes métodos.

```java
public class Controlador {

    public void mostrarSerie() {

        SerieNumerica serie = new SerieNumerica();

        serie.mostrar();

    }

}
```

El controlador ayuda a mantener el proyecto más limpio y organizado.

# Métodos en Java

## Métodos void

No retornan valores.

```java
public void mostrarDato() {

}
```

## Métodos con retorno

```java
public int sumar() {

    return 5;

}
```

# AFD - Automata Finito Determinista

Un AFD permite validar cadenas mediante estados y transiciones.

## Componentes principales

* Q : conjunto de estados
* Σ : alfabeto
* q0 : estado inicial
* δ : transiciones
* F : estados finales

También se utilizan tablas de transición para representar el comportamiento del autómata.

# Trabajo en diferentes computadoras

## Descargar repositorio

```bash
git clone URL
```

## Actualizar cambios

```bash
git pull
```

## Subir cambios

```bash
git add .
git commit -m "Actualización"
git push
```

# Conclusión

Durante las clases se trabajaron temas relacionados con:

* Java
* Git y GitHub
* Markdown
* Algoritmia
* Diagramas de flujo
* Programación orientada a objetos
* Autómatas finitos

Todos estos conocimientos permiten desarrollar proyectos organizados, documentados y fáciles de mantener.
