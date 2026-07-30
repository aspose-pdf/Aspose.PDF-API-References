---
title: "Classe CharInfoCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.CharInfoCollection. Représente une collection d'objets CharInfo"
type: docs
weight: 10630
url: /fr/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Représente la collection d'objets CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Obtient le nombre d'éléments d'objet [`CharInfo`](../charinfo/) réellement contenus dans la collection. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Obtient l'élément CharInfo à l'index spécifié. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | La collection est en lecture seule, lève NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | La collection est en lecture seule. Lève toujours NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Détermine si la collection contient une valeur spécifique. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Renvoie un énumérateur pour l'intégralité de la collection. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | La collection est en lecture seule, lève NotImplementedException. |

## Remarques

Fournit un accès aux informations de positionnement des caractères du segment de texte.

## Exemples

L'exemple montre comment itérer à travers tous les caractères et récupérer le charact

```csharp
//ouvrir le document
Document pdfDocument = new Document(inFile);
//créer un objet TextFragmentAbsorber pour collecter tous les objets texte de la page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accepter l'absorbeur pour toutes les pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//obtenir les fragments de texte extraits
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//boucler sur les fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //boucler sur les segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //boucler sur les caractères
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // imprimer la position du caractère et les informations du rectangle
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Voir aussi

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


