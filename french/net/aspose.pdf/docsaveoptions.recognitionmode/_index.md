---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum DocSaveOptionsRecognitionMode d'Aspose.Pdf. Permet de contrôler comment un document PDF est converti en document de traitement de texte
type: docs
weight: 3770
url: /fr/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## Énumération DocSaveOptions.RecognitionMode

Permet de contrôler comment un document PDF est converti en document de traitement de texte.

```csharp
public enum RecognitionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Textbox | `0` | Ce mode est rapide et bon pour préserver au maximum l'apparence originale du fichier PDF, mais l'éditabilité du document résultant pourrait être limitée. |
| Flow | `1` | Mode de reconnaissance complet, le moteur effectue un regroupement et une analyse multi-niveaux pour restaurer l'intention originale de l'auteur du document et produire un document maximement modifiable. L'inconvénient est que le document de sortie pourrait avoir une apparence différente de celle du fichier PDF original. |
| EnhancedFlow | `2` | Un mode Flow alternatif qui prend en charge la reconnaissance des tableaux. |

## Remarques

Utilisez le mode Textbox lorsque le document résultant ne sera pas fortement modifié par la suite. Les zones de texte sont faciles à modifier lorsqu'il n'y a pas beaucoup à faire.

Utilisez le mode Flow lorsque le document de sortie nécessite des modifications supplémentaires. Les paragraphes et les lignes de texte en mode flow permettent une modification facile du texte, mais les objets de formatage non pris en charge auront une apparence moins bonne que dans le mode Textbox.

### Voir aussi

* classe [DocSaveOptions](../docsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)