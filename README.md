# Práctica Autónoma N.° 01 — Carpeta `codigota1`

- **Asignatura:** Estructuras de Datos y Algoritmos (CDS-0202)
- **Docente:** Ing. Luiggi Alexander Jalca Saltos
- **Tema:** Pruebas y Uso de Operaciones en Listas Enlazadas Simples en Java

---

## 📌 Instrucciones para el estudiante

Las clases `Nodo.java` y `ListaEnlazadaSimple.java` ya se encuentran implementadas y listas para utilizarse. Su tarea consiste en agregar y ejecutar pruebas de las operaciones disponibles en la lista enlazada simple.

Para realizar la actividad, siga estos pasos:

1. Abra el archivo `src/Main.java`.
2. Ubique la línea que contiene el comentario:
   ```java
   // Aqui ubicar las pruebas de los metodos de la lista
   ```
3. Debajo de dicho comentario, agregue las llamadas a los métodos de la lista para comprobar su funcionamiento:
   - Realice inserciones al inicio mediante `lista.insertarAlInicio(...)`.
   - Realice inserciones al final mediante `lista.insertarAlFinal(...)`.
   - Muestre la lista en la consola mediante `lista.mostrarLista()`.
   - Consulte el total de nodos mediante `lista.contarNodos()`.
   - Compruebe la búsqueda de elementos mediante `lista.buscar(...)`.
4. Compile y ejecute el programa desde la terminal con los siguientes comandos:
   ```bash
   javac src/*.java
   java -cp src Main
   ```
5. Tome una captura de pantalla clara de la terminal, en la que se observen los resultados obtenidos, y adjúntela a su informe.
