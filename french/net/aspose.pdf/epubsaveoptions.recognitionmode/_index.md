---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Lorsque le fichier PDF, qui a généralement une mise en page fixe, est converti, le moteur de conversion essaie d'effectuer un regroupement et une analyse multi-niveaux pour restaurer l'intention originale de l'auteur du document et produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour cette ou cette méthode souhaitable de reconnaissance du contenu.
type: docs
weight: 4070
url: /fr/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## Énumération EpubSaveOptions.RecognitionMode

Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion essaie d'effectuer un regroupement et une analyse multi-niveaux pour restaurer l'intention originale de l'auteur du document et produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour cette ou cette méthode souhaitable de reconnaissance du contenu.

```csharp
public enum RecognitionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Flow | `0` | Mode de reconnaissance complet, le moteur essaie d'effectuer un regroupement et une analyse multi-niveaux pour restaurer l'intention originale de l'auteur du document et produire du xhtml en mise en page fluide. |
| PdfFlow | `1` | L'idée principale de cette conversion est basée sur la sauvegarde de l'ordre "naturel" du rendu du contenu qui se forme lors du traitement des documents pdf. Dans les cas généraux, les documents pdf conservent un ordre de rendu de haut en bas, de gauche à droite (voir les directions de l'attachement directions.png). Cette hypothèse permet de créer un algorithme à chemin unique qui transformera les éléments Aps ayant des positions (mise en page fixe) en formats fluides comme HTML, EPUB, DOC. Ce mode sera particulièrement utile pour la conversion de PDF(APS) en EPUB, car le format EPUB a été développé pour les liseuses comme le Kindle ou les smartphones. La taille de l'écran de ces appareils est généralement inférieure à celle de l'écran d'un PC ordinaire. Par conséquent, le contenu des documents EPUB est mieux conservé dans le format fluide, pour un rendu correct sur des écrans de différentes tailles. Dans ce mode, chaque colonne sera ajoutée à la fin de la colonne précédente, ce qui permet de conserver la structure logique du document transformé lors de la "pagination" dans les lecteurs EPUB. Cette réalisation permet de rendre correctement les articles scientifiques ou de magazine. |
| Fixed | `2` | Ce mode est rapide et bon pour préserver au maximum l'apparence originale des pages, mais malheureusement, de nombreux lecteurs EPUB ne prennent pas en charge le xhtml avec mise en page fixe. |

### Voir aussi

* classe [EpubSaveOptions](../epubsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)