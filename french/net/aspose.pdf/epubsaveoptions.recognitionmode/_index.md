---
title: "Enum EpubSaveOptions.RecognitionMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Lorsqu'un fichier PDF qui a généralement une mise en page fixe est converti, le moteur de conversion tente d'effectuer un regroupement et une analyse multiniveau pour restaurer l'intention de l'auteur du document original et produire le résultat en mise en page fluide. Cette propriété ajuste cette conversion pour telle ou telle méthode souhaitable de reconnaissance du contenu."
type: docs
weight: 4190
url: /fr/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion tente d'effectuer un regroupement et une analyse à plusieurs niveaux afin de restaurer l'intention de l'auteur du document original et de produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour telle ou telle méthode souhaitable de reconnaissance du contenu.

```csharp
public enum RecognitionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Flow | `0` | Mode de reconnaissance complet, le moteur tente d'effectuer un regroupement et une analyse multiniveau pour restaurer l'intention de l'auteur du document original et produire du xhtml en mise en page fluide. |
| PdfFlow | `1` | L'idée principale de cette conversion repose sur la sauvegarde de l'ordre "naturel" de rendu du contenu qui se forme lors du traitement des documents pdf. Dans la plupart des cas, les documents pdf conservent un ordre de rendu de haut en bas, de gauche à droite (voir la pièce jointe directions.png). Cette hypothèse permet de créer un algorithme à chemin unique qui transformera les éléments Aps ayant des positions (mise en page fixe) en formats fluides tels que HTML, EPUB, DOC. Ce mode sera particulièrement utile pour la conversion de PDF(APS) vers EPUB, car le format EPUB a été développé pour les liseuses comme le Kindle ou les smartphones. La taille d'écran de ces appareils est généralement inférieure à celle d'un PC ordinaire. Ainsi, le contenu des documents EPUB est préférable de le sauvegarder au format fluide, pour un rendu correct sur des écrans de tailles différentes. Dans ce mode, chaque colonne sera ajoutée à la fin de la colonne précédente, ce qui permet de conserver la structure logique du document transformé lors de la "pagination" dans les lecteurs EPUB. Cette réalisation permet de rendre correctement les articles scientifiques ou de magazine. |
| Fixed | `2` | Ce mode est rapide et efficace pour préserver au maximum l'apparence originale des pages, mais malheureusement de nombreux lecteurs EPUB ne prennent pas en charge le xhtml à mise en page fixe. |

### Voir aussi

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


