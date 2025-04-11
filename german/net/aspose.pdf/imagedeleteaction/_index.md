---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction Enum. Aktion, die mit dem Bildobjekt durchgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird
type: docs
weight: 5870
url: /de/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction Aufzählung

Aktion, die mit dem Bildobjekt durchgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird

```csharp
public enum ImageDeleteAction
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| KeepContents | `0` | Das Bild wird aus der Sammlung entfernt. Wenn der Seiteninhalt Verweise auf das Bild enthält, werden diese nicht entfernt. Das Dokument kann ungültig werden. |
| None | `1` | Das Bild wird aus der Sammlung und aus dem Seiteninhalt entfernt, aber das Bildobjekt wird nicht gelöscht. Die Dateigröße wird nicht verringert. |
| ForceDelete | `2` | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird aus dem Dokument entfernt. Wenn andere Verweise auf dasselbe Objekt existieren, kann das Dokument beschädigt werden. |
| Check | `3` | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird nur entfernt, wenn keine anderen Verweise auf das Bild von anderen Seiten existieren. Dies kann im Vergleich zur ForceDelete-Option mehr Zeit in Anspruch nehmen. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)