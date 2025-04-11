---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions-Schnittstelle. Nützliche Eigenschaften zur Anpassung des Schriftverhaltens
type: docs
weight: 10610
url: /de/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions-Schnittstelle

Nützliche Eigenschaften zur Anpassung des Schriftverhaltens

```csharp
public interface IFontOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Manchmal ist es nicht möglich, die gewünschte Schriftart in das Dokument einzubetten. Es gibt viele Gründe, zum Beispiel Lizenzbeschränkungen oder wenn die gewünschte Schriftart auf dem Zielcomputer nicht gefunden wurde. Wenn diese Situation eintritt, ist es nicht einfach zu erkennen, da die gewünschte Schriftart über die Eigenschaftsflagge Font.IsEmbedded = true; eingebettet wird. Natürlich ist es möglich, diese Eigenschaft sofort nach ihrer Festlegung zu lesen, aber es ist kein bequemer Ansatz. Das Flag NotifyAboutFontEmbeddingError erzwingt einen Ausnahme-Mechanismus für Fälle, in denen der Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Wenn dieses Flag gesetzt ist, wird eine Ausnahme vom Typ [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) ausgelöst. Standardmäßig false. |

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)