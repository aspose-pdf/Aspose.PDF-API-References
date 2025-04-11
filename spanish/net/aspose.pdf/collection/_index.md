---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Collection. Representa la clase para Colecciones12.3.5
type: docs
weight: 3020
url: /es/net/aspose.pdf/collection/
---
## Clase Colección

Representa la clase para Colección(12.3.5 Colecciones).

```csharp
public class Collection : EmbeddedFileCollection
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Collection](collection/)() | Inicializa un nuevo objeto Collection. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Obtiene el número de archivos incrustados en la colección. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nombre del archivo incrustado por defecto. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para hilos). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Obtiene el archivo incrustado por su índice. (2 indexadores) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Devuelve la lista de claves de archivos adjuntos. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Obtiene un "Esquema" de una colección de documentos. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso a esta colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Agrega la especificación del archivo incrustado a la colección. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Agrega un archivo a los archivos incrustados con la clave especificada. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copia un arreglo de objetos FileSpecification a la colección. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Elimina todos los archivos incrustados del documento. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Elimina el archivo incrustado por nombre. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Elimina el archivo de la colección por su clave en la colección. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Devuelve el archivo incrustado por su nombre. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Devuelve el enumerador de la colección. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Obtiene una colección de archivos ordenados de acuerdo con la especificación. |

### Ver También

* clase [EmbeddedFileCollection](../embeddedfilecollection/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)