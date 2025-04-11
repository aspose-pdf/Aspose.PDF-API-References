---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontCollection. Représente une collection de polices
type: docs
weight: 10530
url: /fr/net/aspose.pdf.text/fontcollection/
---
## Classe FontCollection

Représente une collection de polices.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Obtient le nombre d'éléments d'objet [`Font`](../font/) réellement contenus dans la collection. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à la collection est synchronisé (sécurisé pour les threads). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Obtient l'élément de police à l'index spécifié. (2 indexeurs) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Ajoute une nouvelle police aux ressources de police et renvoie le nom automatiquement attribué de la ressource de police. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Détermine si la collection contient une valeur spécifique. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Vérifie si la police existe dans la collection de polices. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copie l'ensemble de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Renvoie un énumérateur pour l'ensemble de la collection. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Supprime l'élément spécifié de la collection. |

## Remarques

Les collections de polices représentées par la classe `FontCollection` sont utilisées dans plusieurs scénarios. Par exemple, dans les ressources avec la propriété [`Fonts`](../../aspose.pdf/resources/fonts/).

## Exemples

L'exemple démontre comment rendre toutes les polices déclarées sur la page intégrées.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Voir aussi

* classe [Font](../font/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)