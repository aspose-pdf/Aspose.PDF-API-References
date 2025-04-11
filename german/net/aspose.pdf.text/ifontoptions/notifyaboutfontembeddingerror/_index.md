---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions-Eigenschaft. Manchmal ist es nicht möglich, die gewünschte Schriftart in das Dokument einzubetten. Es gibt viele Gründe, zum Beispiel Lizenzbeschränkungen oder wenn die gewünschte Schriftart auf dem Zielcomputer nicht gefunden wurde. Wenn diese Situation eintritt, ist es nicht einfach zu erkennen, da die gewünschte Schriftart über die Eigenschaftsflagge Font.IsEmbedded = true eingebettet ist. Natürlich ist es möglich, diese Eigenschaft sofort nach dem Setzen zu lesen, aber es ist kein bequemer Ansatz. Das Flag NotifyAboutFontEmbeddingError erzwingt einen Ausnahme-Mechanismus für Fälle, in denen der Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Wenn dieses Flag gesetzt ist, wird eine Ausnahme vom Typ [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) ausgelöst. Standardmäßig false.
type: docs
weight: 10
url: /de/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError-Eigenschaft

Manchmal ist es nicht möglich, die gewünschte Schriftart in das Dokument einzubetten. Es gibt viele Gründe, zum Beispiel Lizenzbeschränkungen oder wenn die gewünschte Schriftart auf dem Zielcomputer nicht gefunden wurde. Wenn diese Situation eintritt, ist es nicht einfach zu erkennen, da die gewünschte Schriftart über die Eigenschaftsflagge Font.IsEmbedded = true eingebettet ist. Natürlich ist es möglich, diese Eigenschaft sofort nach dem Setzen zu lesen, aber es ist kein bequemer Ansatz. Das Flag NotifyAboutFontEmbeddingError erzwingt einen Ausnahme-Mechanismus für Fälle, in denen der Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Wenn dieses Flag gesetzt ist, wird eine Ausnahme vom Typ [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) ausgelöst. Standardmäßig false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Siehe auch

* Schnittstelle [IFontOptions](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)