# C++ Notes

Apuntes Generales de de C++

---

# Clase #1
## Proceso de compilación

Para desarrollar aplicacione en C++ vamos a entender y comprender como es el 
proceso de complicación de este lenguaje de programación. 

Los 4 primeros pasos, son lo pasos de build, construcción y los últimos dos pasos son los pasos de ejecución.

1. **Editor oo IDE**: 

Este es nuestro entorno de trabajo donde escribimos el código. Aquí escribimos
el código fuente con archivos que terminan en `.cpp` o `.h`.

2. **Preprocesador**:

Este paso es el preprocesamiento, se ejecuta este programa Preprocesador que toma los todos los archivos
y los junta para hacer un solo archivo para los siguientes pasos. 

3. **Compilador**:

Es un programa que toma el código fuente y lo transforma en código objeto que es un código para que la máquina
lo pueda entender y ejecutar. 

4. **LInker**:

Junta el código con las librerias/dependecias que sean necesarias para que tu código funcione.

5. **Loader**:

Se hace la carga, se ejecuta, un pequeño programa que arranca el programa y carga todas las librerías obtenidas
de forma dinámica, osea que no las colocas explicitas pero el programa las carga. 

6. **Ejecución**:

Se monta en memoria y se ejecuta el programa, donde puede recibir los datos de entrada y la salidas de los mismos. 

## Herramientas para trabajar con C++:

Se necesita un editor de código para poder trabajar con C++ y un compilador, es este caso se trabaja con 
**GCC** el compilador de GNU Compiler Collection, es una herramienta de compilación ampliamente utilizada y de
código abierto libre. En sistemas como linux ya viene preinstalada. 

---

