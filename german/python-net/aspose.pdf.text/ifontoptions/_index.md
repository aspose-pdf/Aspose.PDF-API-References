---
title: "IFontOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Nützliche Eigenschaften, um das Verhalten von Schriftarten anzupassen"
type: docs
weight: 180
url: /de/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Nützliche Eigenschaften, um das Verhalten von Schriftarten anzupassen

Der Typ IFontOptions stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| notify_about_font_embedding_error | Manchmal ist es nicht möglich, die gewünschte Schriftart in das Dokument einzubetten. Es gibt viele Gründe, zum Beispiel<br/>            Lizenzbeschränkungen oder wenn die gewünschte Schriftart auf dem Zielcomputer nicht gefunden wurde.<br/>            Wenn diese Situation eintritt, ist sie nicht einfach zu erkennen, weil die gewünschte Schriftart über das Setzen <br/>            des Property‑Flags Font.IsEmbedded = true eingebettet wird; natürlich kann diese Property sofort nach dem Setzen ausgelesen werden, aber<br/>            das ist kein bequemer Ansatz. Das Flag NotifyAboutFontEmbeddingError erzwingt einen Ausnahme‑Mechanismus <br/>            für Fälle, in denen der Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Wenn dieses Flag gesetzt ist, wird eine Ausnahme des Typs<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) ausgelöst. Standardmäßig false. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

