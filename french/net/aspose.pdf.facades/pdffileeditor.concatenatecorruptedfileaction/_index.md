---
title: "Enum PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction. Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation"
type: docs
weight: 4590
url: /fr/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| StopWithError | `0` | Si un fichier corrompu est rencontré, alors arrêtez le processus de concaténation et renvoyez une erreur. |
| ConcatenateIgnoringCorrupted | `1` | Si un fichier corrompu est rencontré, alors n'arrêtez pas la concaténation et ne traitez pas le fichier corrompu. La liste des fichiers corrompus est accessible via la propriété Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Lorsque un objet corrompu est rencontré dans le document source, le processus ne sera pas arrêté et seul l'objet corrompu est ignoré. |

### Voir aussi

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


