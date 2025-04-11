---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PageCollection. Colección de páginas de documentos PDF
type: docs
weight: 8080
url: /es/net/aspose.pdf/pagecollection/
---
## Clase PageCollection

Colección de páginas de documentos PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Obtiene el conteo de páginas en el documento. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Obtiene el valor que indica si la colección es de solo lectura. Siempre devuelve falso. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Devuelve verdadero si el objeto está sincronizado. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Obtiene la página por índice. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Obtiene el objeto de sincronización de la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Acepta el objeto visitante [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) que proporciona funcionalidad para trabajar con anotaciones. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Acepta el objeto visitante [`ImagePlacementAbsorber`](../imageplacementabsorber/) que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Acepta el objeto visitante [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Acepta el objeto visitante [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Agrega una página vacía. Si el documento ya contiene páginas de diferentes tamaños, se seleccionará el tamaño de la página que más se repite. En caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Agrega a la colección todas las páginas de la lista. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Agrega una página a la colección. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Agrega a la colección todas las páginas del arreglo. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Limpia la colección de páginas. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Determina si esta instancia contiene el objeto. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copia páginas en el documento. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Elimina todas las páginas de la colección. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Elimina la página especificada. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Elimina las páginas especificadas cuyos números están en el arreglo. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Elimina todos los campos ubicados en las páginas y coloca sus valores en su lugar. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Limpia los datos en caché. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Devuelve un enumerador de páginas. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Devuelve el índice de la página especificada. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas de diferentes tamaños, se seleccionará el tamaño de la página que más se repite. En caso de que solo haya dos páginas diferentes, se utilizará el tamaño de la primera página. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Inserta páginas de la colección en el documento. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Inserta una página en la colección de páginas en el lugar especificado. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Inserta las páginas del arreglo en el documento. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Elimina el elemento especificado, lanza NotSupportedException. |

### Ver También

* clase [Page](../page/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)