---
title: CharInfoCollection
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa la colección de objetos CharInfo.
type: docs
weight: 6640
url: /es/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Representa la colección de objetos CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count) { get; } | Obtiene el número de[`CharInfo`](../charinfo) elementos de objeto realmente contenidos en la colección. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly) { get; } | Obtiene un valor que indica si la colección es de solo lectura |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized) { get; } | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [Item](../../aspose.pdf.text/charinfocollection/item) { get; } | Obtiene el elemento CharInfo en el índice especificado. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso a la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add)(CharInfo) | La colección es de solo lectura, lanzaExcepción no implementada . |
| [Clear](../../aspose.pdf.text/charinfocollection/clear)() | La colección es de solo lectura. Siempre arroja NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains)(CharInfo) | Determina si la colección contiene un valor específico. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto)(CharInfo[], int) | Copia la colección completa en un Array unidimensional compatible, comenzando en el índice especificado del array de destino |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator)() | Devuelve un enumerador para toda la colección. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove)(CharInfo) | La colección es de solo lectura, lanzaExcepción no implementada . |

### Observaciones

Proporciona acceso a la información de posicionamiento de los caracteres del segmento de texto.

### Ejemplos

El ejemplo muestra cómo recorrer todos los caracteres y recuperar el carácter

```csharp
//abrir documento
Document pdfDocument = new Document(inFile);
//crear objeto TextFragmentAbsorber para recopilar todos los objetos de texto de la página
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//aceptar el absorbedor para todas las páginas
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
// obtener los fragmentos de texto extraídos
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
// recorrer los fragmentos
foreach (TextFragment textFragment in textFragmentCollection)
{
    // recorrer los segmentos
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        // recorrer los caracteres
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // imprime la posición del carácter y la información del rectángulo
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Ver también

* class [CharInfo](../charinfo)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
