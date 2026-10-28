+---------------------+
|      Usuario        |
+---------------------+
| idUsuario : int     |
| nombre : String     |
| correo : String     |
| telefono : String   |
+---------------------+
| solicitarPrestamo() |
| devolverLibro()     |
+---------------------+
           |
           | 1
           |
           | *
+---------------------+
|      Prestamo       |
+---------------------+
| idPrestamo : int    |
| fechaPrestamo:Date  |
| fechaDevolucion:Date|
| estado : String     |
+---------------------+
| registrarPrestamo() |
| finalizarPrestamo() |
+---------------------+
           |
           | *
           |
           | 1
+----------------------+
|       Libro          |
+----------------------+
| idLibro : int        |
| titulo : String      |
| autor : String       |
| editorial : String   |
| disponible : boolean |
+----------------------+
| prestar()            |
| devolver()           |
| consultarDisponibilidad() |
+----------------------+

+-------------------------+
|     Bibliotecario       |
+-------------------------+
| idBibliotecario : int   |
| nombre : String         |
| cargo : String          |
+-------------------------+
| registrarLibro()        |
| gestionarPrestamo()     |
+-------------------------+

Bibliotecario 1 -------- * Prestamo
