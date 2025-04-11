---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.CharInfoCollection. Représente une collection d'objets CharInfo
type: docs
weight: 10450
url: /fr/net/aspose.pdf.text/charinfocollection/
---
## Classe CharInfoCollection

Représente une collection d'objets CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Obtient le nombre d'éléments d'objet [`CharInfo`](../charinfo/) réellement contenus dans la collection. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à la collection est synchronisé (sécurisé pour les threads). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Obtient l'élément CharInfo à l'index spécifié. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | La collection est en lecture seule, lance NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | La collection est en lecture seule. Lance toujours NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Détermine si la collection contient une valeur spécifique. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copie l'ensemble de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Renvoie un énumérateur pour l'ensemble de la collection. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | La collection est en lecture seule, lance NotImplementedException. |

## Remarques

Fournit un accès aux informations de positionnement des caractères des segments de texte.

## Exemples

L'exemple démontre comment itérer à travers tous les caractères et récupérer le caractère

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

### Voir aussi

* classe [CharInfo](../charinfo/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)