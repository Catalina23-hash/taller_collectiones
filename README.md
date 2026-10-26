1.Java distingue entre mayúsculas y minúsculas, por lo que se debe escribir exactamente ArrayList, y además requiere importar la librería correspondiente para que el compilador lo reconozca.

2.Muestra una relación de agregación. Las listas solo almacenan referencias a los objetos, por lo que eliminar un elemento de una lista no destruye ni borra el objeto original de otras ubicaciones.

3.La relación Playlist-Canción es una agregación donde la canción puede existir de forma independiente; en cambio, Parqueadero-Puesto es una composición, ya que el puesto depende por completo del parqueadero y no tiene vida propia si este desaparece.

4.totalCanciones es un atributo static compartido por toda la clase para llevar un conteo global, mientras que titulo es un atributo individual que pertenece a cada instancia u objeto creado.

5.La palabra this hace referencia a una instancia u objeto específico en ejecución, mientras que los métodos o variables static pertenecen a la clase y funcionan sin necesidad de instanciar ningún objeto.
