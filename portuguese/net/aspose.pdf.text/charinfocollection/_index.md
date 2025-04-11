---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.CharInfoCollection. Representa uma coleção de objetos CharInfo
type: docs
weight: 10450
url: /pt/net/aspose.pdf.text/charinfocollection/
---
## Classe CharInfoCollection

Representa uma coleção de objetos CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Obtém o número de elementos do objeto [`CharInfo`](../charinfo/) realmente contidos na coleção. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Obtém um valor que indica se a coleção é somente leitura |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Obtém um valor que indica se o acesso à coleção é sincronizado (seguro para threads). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Obtém o elemento CharInfo no índice especificado. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Obtém um objeto que pode ser usado para sincronizar o acesso à coleção. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | A coleção é somente leitura, lança NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | A coleção é somente leitura. Sempre lança NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Determina se a coleção contém um valor específico. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Retorna um enumerador para toda a coleção. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | A coleção é somente leitura, lança NotImplementedException. |

## Observações

Fornece acesso às informações de posicionamento dos caracteres dos segmentos de texto.

## Exemplos

O exemplo demonstra como iterar por todos os caracteres e recuperar o caractere

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

### Veja Também

* classe [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)