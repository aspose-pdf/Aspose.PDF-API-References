---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Aktion, die mit dem Bildobjekt ausgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird"
type: docs
weight: 2290
url: /de/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Aktion, die mit dem Bildobjekt ausgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Check](#Check) | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird nur entfernt, wenn keine anderen Verweise auf das Bild von anderen Seiten bestehen. Dies kann im Vergleich zur Option ForceDelete mehr Zeit benötigen. |
| [ForceDelete](#ForceDelete) | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird aus dem Dokument entfernt. Wenn andere Verweise auf dasselbe Objekt existieren, kann das Dokument beschädigt werden. |
| [KeepContents](#KeepContents) | Das Bild wird aus der Sammlung entfernt. Wenn der Seiteninhalt Verweise auf das Bild enthält, werden diese nicht entfernt. Das Dokument kann ungültig werden. |
| [None](#None) | Das Bild wird aus der Sammlung und aus dem Seiteninhalt entfernt, aber das Bildobjekt wird nicht gelöscht. Die Dateigröße wird nicht verringert. |

### Check {#Check}
```
public static final int Check
```

Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird nur entfernt, wenn keine anderen Verweise auf das Bild von anderen Seiten bestehen. Dies kann im Vergleich zur Option ForceDelete mehr Zeit benötigen.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird aus dem Dokument entfernt. Wenn andere Verweise auf dasselbe Objekt existieren, kann das Dokument beschädigt werden.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

Das Bild wird aus der Sammlung entfernt. Wenn der Seiteninhalt Verweise auf das Bild enthält, werden diese nicht entfernt. Das Dokument kann ungültig werden.

### None {#None}
```
public static final int None
```

Das Bild wird aus der Sammlung und aus dem Seiteninhalt entfernt, aber das Bildobjekt wird nicht gelöscht. Die Dateigröße wird nicht verringert.
