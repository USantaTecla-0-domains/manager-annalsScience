# Anales de la Ciencia
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## index

* [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)  
* [versions](#versions)
    * [0.0.dataLanguage](./0.0.dataLanguages/README.md)
    * [0.0.publicationLanguage](./0.0.publicationLanguage/README.md)
    * [1.0.basic](./1.0.basic/README.md)
    * [1.1.machine](./1.1.machine/README.md)
    * [2.0.graphics](./2.0.graphics/README.md)
    * [3.0.undoRedo](./3.0.undoRedo/README.md)
    * [4.0.distributed](./4.0.distributed/README.md)
    * [5.0.files](./5.0.files/README.md)
    * [6.0.bbdd](./6.0.bbdd/README.md)

## domainModel  

- A lo largo de la historia de la ciencia han surgido grandes personajes (filosofos, físicos, matemáticos, ... informáticos). Estas personas, bien por libre de forma autónoma o bajo el auspicio de alguna entidad (corte, mecenas, empresa, universidad, ...) han aportado grandes productos a la ciencia (teorias, leyes, herramientas, ..., software).
 * Por tanto, existe una relación entre la entidades asociadas a las personas que las integran y relaciones entre las personas y/o entidades asociadas a los productos que los crearon. 

- Para todos los elementos interesan los siguientes campos:

 * Nombre
 * Fecha de nacimiento, creación, ...
 * Fecha de defunción, utilidad, ...
 * Imagen, retrato, logo, ..., url a la imagen
 * Wiki, url al elemento
 * Para los Productos interesa:
   * Personas que han participado en su desarrollo
   * Entidades que han participado en su desarrollo
 * Para las Entidades intersa:
   * Personas que han participado en su desarrollo

![draughtsModeloDominio](./docs/diagrams/out/docs/diagrams/draughtsModeloDominio/draughtsModeloDominio.svg)

### vocabulary