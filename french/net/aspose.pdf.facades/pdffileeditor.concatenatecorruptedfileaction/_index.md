---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFileEditorConcatenateCorruptedFileAction d'Aspose.Pdf.Facades. Action effectuée lorsqu'un fichier corrompu a été rencontré dans le processus de concaténation
type: docs
weight: 4470
url: /fr/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## Énumération PdfFileEditor.ConcatenateCorruptedFileAction

Action effectuée lorsqu'un fichier corrompu a été rencontré dans le processus de concaténation.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| StopWithError | `0` | Si un fichier corrompu a été rencontré, alors arrêter le processus de concaténation et retourner une erreur. |
| ConcatenateIgnoringCorrupted | `1` | Si un fichier corrompu a été rencontré, alors ne pas arrêter la concaténation et ne pas traiter le fichier corrompu. La liste des fichiers corrompus est accessible dans la propriété Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Lorsqu'un objet corrompu est rencontré dans le document source, le processus ne sera pas arrêté et seul l'objet corrompu sera ignoré. |

### Voir aussi

* classe [PdfFileEditor](../pdffileeditor/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)