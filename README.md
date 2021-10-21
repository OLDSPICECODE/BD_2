# BASE DE DATOS RUDIMENTARIO EN C++

aca explicare como funciona cada funcion para la implementacion rapipda y facil

## IDE

de preferencia los siguientes:
  - Visual Studio Code
  - Visual studio Comunity
  - Atom
  
### Lenguaje de Programacion 📋

C++

### Primero. 🔧

La funcion principal va a tener que:
  - separa los comandos en vectores de string para poder procesarlos de manera mas facil

```
   CREATE TABLE ejemplo { id_alu int, nom text;}
   
   PALABRA Clave: CREATE 
   Accion despues: TABLE
   Nombre del objeto: ejemplo
   tipos de dato: vector<string> [int,text]
   atrivutos: vector<string> [id_alu,nom]
   
```

en otras palabras la funcion principal va atener que interpretar el lenguaje natural.

```
   SELECT * FROM ejemplo where a = b
   
   PALABRA clave: SELECT, WHERE
   Que seleccionamos: vector<string> [*]
   Tabla de donde selecionamos: ejemplo
   condicion: string = [=]
              vector = [a,b]
```

La funcion tiene que identificar las palabras clave y separarlo en parte y mandarlo a su respestiva funcion.

```
   DELETE FROM ejemplo where a = b
   
   PALABRA clave: DELETE FROM , WHERE
   Tabla de donde borraremos: ejemplo
   condicion: string = [=]
              vector<string> = [a,b]
```

```
   UPDATE ejemplo Set a = b where c=d
   
   PALABRAS CLAVE: UPDATE, SET,WHERE
   Tabla a modificar: ejemplo
   cosa a cambiar [   a   ,   b   ]
                   columna, cambio
   condicion: string = [=]
              vector<string> = [c,d]
```

### Preguntas 🔩

Tiempo maximo para entregar: Domingo 24 de octubre.
Calidad del trabajo: Lo mas optimo posible lo suficiente como para  implementar arboles B+

### Estilo de codificación ⌨️

Usar clases y .h para mejorar nuestro orden y facilitar el merge entre los forks que van a crear

