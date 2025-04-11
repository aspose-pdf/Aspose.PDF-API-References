---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XImageCollection. Classe représentant une collection d'XImage
type: docs
weight: 11360
url: /fr/net/aspose.pdf/ximagecollection/
---
## Classe XImageCollection

Classe représentant une collection d'XImage.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | Nombre d'images dans la collection. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | Renvoie vrai si l'objet est synchronisé. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | Obtient une image de la collection par son index. (2 indexeurs) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | Obtient un tableau de noms d'images. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | Renvoie l'objet de synchronisation. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | Ajoute une entité à la fin de la collection, de sorte que l'entité puisse être accessible par le dernier index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | Ajoute une entité à la fin de la collection, de sorte que l'entité puisse être accessible par le dernier index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | Ajoute une nouvelle image à la liste d'images. Cette méthode ajoute l'image en tant que référence au même PdfObject (ce qui permet de réduire la taille du fichier) |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | Ajoute une entité à la fin de la collection, de sorte que l'entité puisse être accessible par le dernier index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | Ajoute une entité à la fin de la collection, de sorte que l'entité puisse être accessible par le dernier index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | Ajoute une entité à la fin de la collection, de sorte que l'entité puisse être accessible par le dernier index. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | Efface tous les éléments de la collection. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | Détermine si la collection contient une valeur spécifique. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | Copie un tableau d'images dans la collection. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | Supprime des images de la collection. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | Supprime un index de la collection par index. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | Supprime un élément de la collection par nom. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | Supprime une image de la collection par index en effectuant l'action spécifiée par le paramètre d'action. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | Supprime un élément de la collection par nom. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | Renvoie l'énumérateur de la collection. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | Renvoie le nom dans la liste d'images qui est la clé de l'image donnée. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | Supprime un élément de la collection, lance NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | Remplace une image dans la collection par une autre image. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | Remplace une image dans la collection par une autre image. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | Remplace une image dans la collection par une autre image. |

### Voir aussi

* classe [XImage](../ximage/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)