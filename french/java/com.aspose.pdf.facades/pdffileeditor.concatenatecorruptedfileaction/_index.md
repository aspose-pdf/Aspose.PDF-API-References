---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation."
type: docs
weight: 420
url: /fr/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation.

## Champs

| Champ | Description |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Si un fichier corrompu est rencontré, alors ne pas arrêter la concaténation et ne pas traiter le fichier corrompu. La liste des fichiers corrompus est accessible dans la propriété Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Lorsque un objet corrompu est rencontré dans le document source, le processus ne sera pas arrêté et seul l'objet corrompu est ignoré. |
| [StopWithError](#StopWithError) | Si un fichier corrompu est rencontré, alors arrêter le processus de concaténation et renvoyer une erreur. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Si un fichier corrompu est rencontré, alors ne pas arrêter la concaténation et ne pas traiter le fichier corrompu. La liste des fichiers corrompus est accessible dans la propriété Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Lorsque un objet corrompu est rencontré dans le document source, le processus ne sera pas arrêté et seul l'objet corrompu est ignoré.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Si un fichier corrompu est rencontré, alors arrêter le processus de concaténation et renvoyer une erreur.
