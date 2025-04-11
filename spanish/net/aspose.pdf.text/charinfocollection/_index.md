---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.CharInfoCollection. Representa una colección de objetos CharInfo
type: docs
weight: 10450
url: /es/net/aspose.pdf.text/charinfocollection/
---
## Clase CharInfoCollection

Representa una colección de objetos CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Obtiene el número de elementos de objeto [`CharInfo`](../charinfo/) que realmente están contenidos en la colección. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Obtiene un valor que indica si la colección es de solo lectura |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Obtiene el elemento CharInfo en el índice especificado. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso a la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | La colección es de solo lectura, lanza NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | La colección es de solo lectura. Siempre lanza NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Determina si la colección contiene un valor específico. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copia toda la colección a un Array unidimensional compatible, comenzando en el índice especificado del array de destino |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Devuelve un enumerador para toda la colección. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | La colección es de solo lectura, lanza NotImplementedException. |

## Observaciones

Proporciona acceso a la información de posicionamiento de los caracteres de los segmentos de texto.

## Ejemplos

El ejemplo demuestra cómo iterar a través de todos los caracteres y recuperar el carácter

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Véase También

* clase [CharInfo](../charinfo/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)