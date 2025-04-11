---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.TextElement-Klasse. Allgemeines Textelement der logischen Struktur des Dokuments
type: docs
weight: 10190
url: /de/net/aspose.pdf.structure/textelement/
---
## TextElement-Klasse

Allgemeines Textelement der logischen Struktur des Dokuments.

```csharp
public class TextElement : Element
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Optional; PDF 1.4) Text, der eine genaue Ersetzung für das Strukturelement und dessen Kinder darstellt. Dieser Ersatztext (der auf so kleinen Inhalt wie möglich angewendet werden sollte) ist nützlich, wenn der Inhalt des Dokuments zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder für andere Zwecke extrahiert wird. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) Eine alternative Beschreibung des Strukturelements und dessen Kinder in menschenlesbarer Form, die nützlich ist, wenn der Inhalt des Dokuments zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder für andere Zwecke extrahiert wird. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Gibt die Sammlung der Kind-Elemente zurück. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) Die erweiterte Form einer Abkürzung. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) Eine Sprache, die die natürliche Sprache für allen Text im Strukturelement angibt, es sei denn, sie wird durch Sprachspezifikationen für geschachtelte Strukturelemente oder markierten Inhalt überschrieben. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Gibt den Wert des Textelements zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Element entfernen. |

### Siehe auch

* Klasse [Element](../element/)
* Namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* Assembly [Aspose.PDF](../../)