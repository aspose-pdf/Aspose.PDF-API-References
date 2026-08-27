---
title: "ImageDeleteAction"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Aktion, die mit dem Bildobjekt ausgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird"
type: docs
weight: 6450
url: /de/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Aktion, die mit dem Bildobjekt ausgeführt wird, wenn das Bild aus der Sammlung entfernt wird. Wenn das Bildobjekt entfernt wird

## Members
| Member-Name | Beschreibung |
| :- | :- |
| KEEP_CONTENTS | Das Bild wird aus der Sammlung entfernt. Wenn Seiteninhalte Verweise auf das Bild enthalten, werden diese nicht entfernt. Das Dokument kann ungültig werden. |
| NONE | Das Bild wird aus der Sammlung und aus den Seiteninhalten entfernt, aber das Bildobjekt wird nicht gelöscht. Die Dateigröße wird nicht reduziert. |
| FORCE_DELETE | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird aus dem Dokument entfernt. Wenn weitere Verweise auf dasselbe Objekt existieren, kann das Dokument beschädigt werden. |
| CHECK | Das Bild wird aus der Sammlung entfernt und das Bildobjekt wird nur entfernt, wenn keine weiteren Verweise auf das Bild von anderen Seiten bestehen. Dies kann im Vergleich zur Option FORCE_DELETE mehr Zeit benötigen. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

