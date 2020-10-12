# Find MongoDB
Este ejercicio trata de aprender a usar los comandos *find* de MongoDB
Este tipo de comando sirve para devolver los documentos de una colección de la base de datos en uso.
Primero usaremos el comando **db.colordenadores.find({"memoria":"16Gb"})** que sirve para devolver todos los documentos en los que el campo "memoria" tenga el valor "16Gb".
Después usaremos **db.colordenadores.find ({"memoria": {$eq: "16Gb"}})** que sirve para lo mismo.
Por último **db.colordenadores.find ({"memoria": {$exists: "16Gb"}})** que sirve para devolver todos los documentos de un campo específico.