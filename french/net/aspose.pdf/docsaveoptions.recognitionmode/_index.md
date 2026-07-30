---
title: "Enum DocSaveOptions.RecognitionMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Permet de contrôler comment un document PDF est converti en document de traitement de texte."
type: docs
weight: 3890
url: /fr/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

Permet de contrôler comment un document PDF est converti en document de traitement de texte.

```csharp
public enum RecognitionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Textbox | `0` | Ce mode est rapide et permet de préserver au maximum l'apparence originale du fichier PDF, mais l'édition du document résultant peut être limitée. |
| Flow | `1` | Mode de reconnaissance complet, le moteur effectue un regroupement et une analyse multi-niveaux pour restaurer l'intention de l'auteur du document original et produire un document hautement éditable. L'inconvénient est que le document de sortie peut différer de l'original PDF. |
| EnhancedFlow | `2` | Un mode Flow alternatif qui prend en charge la reconnaissance des tableaux. |

## Remarques

Utilisez le mode Textbox lorsque le document résultant ne sera pas fortement modifié par la suite. Les zones de texte sont faciles à modifier lorsqu'il n'y a pas grand-chose à faire.

Utilisez le mode Flow lorsque le document de sortie nécessite des modifications supplémentaires. Les paragraphes et les lignes de texte en mode Flow permettent une modification facile du texte, mais les objets de formatage non pris en charge apparaîtront moins bien que dans le mode Textbox.

### Voir aussi

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


