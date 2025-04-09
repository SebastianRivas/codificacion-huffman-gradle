# CODIFICACION HUFFMAN (JAVA & GRADLE)
Este proyecto tiene una implementación en el lenguaje de programación JAVA usando el gestor de paquetes GRADLE del algoritmo de compresión de datos llamado Codificación Huffman.

## ESTRUCTURA DE DIRECCTORIOS 🗂️
```bash
    .
    ├── app
    │   ├── bin
    │   ├── build.gradle.kts
    │   └── src
    │       ├── main
    │       │   ├── java
    │       │   │   └── org
    │       │   │       └── CodificacionHuffman
    │       │   │           ├── app
    │       │   │           │   ├── App.java
    │       │   │           │   ├── gui
    │       │   │           │   │   └── Principal.java
    │       │   │           │   └── logica
    │       │   │           │       ├── Arbol.java
    │       │   │           │       ├── Archivo.java
    │       │   │           │       ├── CodificacionHuffman.java
    │       │   │           │       ├── Lista.java
    │       │   │           │       ├── Nodo.java
    │       │   │           │       └── ProcesarStrings.java
    │       │   │           ├── input
    │       │   │           │   └── text
    │       │   │           │       └── Lorem Ipsum.txt
    │       │   │           └── output
    │       │   │               └── text
    │       │   └── resources
    │       └── test
    │           ├── java
    │           │   └── org
    │           │       └── CodificacionHuffman
    │           │           └── app
    │           │               ├── AppTest.java
    │           │               ├── gui
    │           │               │   └── PrincipalTest.java
    │           │               └── logica
    │           │                   ├── ArbolTest.java
    │           │                   ├── ArchivoTest.java
    │           │                   ├── CodificacionHuffmanTest.java
    │           │                   ├── ListaTest.java
    │           │                   ├── NodoTest.java
    │           │                   └── ProcesarStringsTest.java
    │           └── resources
    ├── build
    ├── gradle
    │   ├── libs.versions.toml
    │   └── wrapper
    │       ├── gradle-wrapper.jar
    │       └── gradle-wrapper.properties
    ├── gradle.properties
    ├── gradlew
    ├── gradlew.bat
    ├── README.md
    └── settings.gradle.kts
```

## EJECUCION DEL PROYECTO ⌨️
⚠️ La compilacion y posterior ejecucion del proyecto se debe hacer desde la raiz del proyecto ⚠️

⚠️ La salida del programa se almacena en ⚠️
```bash
app/src/main/java/org/CodificacionHuffman/output/text
```

* Compilacion y ejecucion

Compilacion
```bash
    ./gradlew build
```

Construccion del JAR
```bash
    ./gradlew jar
```

Ejecucion
```bash
    ./gradlew run
```