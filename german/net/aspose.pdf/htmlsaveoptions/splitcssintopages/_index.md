---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-Eigenschaft. Wenn der Mehrseitenmodus ausgewählt ist, d.h. SplitIntoPages wahr ist, definiert dieses Attribut, ob eine separate CSS-Datei für jede resultierende HTML-Seite erstellt werden soll. Standardmäßig ist dieses Attribut falsch, sodass eine große gemeinsame CSS für alle erstellten Seiten erstellt wird. Die Gesamtsumme der in diesem Modus generierten CSS ist normalerweise viel größer als die Größe einer großen CSS-Datei, da im ersteren Fall CSS-Klassen Duplikate sind, in diesem Fall in mehreren CSS-Dateien für jede Seite. Daher ist diese Einstellung nur dann schlechter zu verwenden, wenn Sie an der zukünftigen Verarbeitung jeder HTML-Seite unabhängig interessiert sind, und daher ist die Größe der CSS jeder einzelnen Seite das kritischste Problem.
type: docs
weight: 190
url: /de/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages-Eigenschaft

Wenn der Mehrseitenmodus ausgewählt ist (d.h. 'SplitIntoPages' ist 'wahr'), definiert dieses Attribut, ob eine separate CSS-Datei für jede resultierende HTML-Seite erstellt werden soll. Standardmäßig ist dieses Attribut falsch, sodass eine große gemeinsame CSS für alle erstellten Seiten erstellt wird. Die Gesamtsumme der in diesem Modus generierten CSS (eine CSS pro Seite) ist normalerweise viel größer als die Größe einer großen CSS-Datei, da im ersteren Fall CSS-Klassen Duplikate sind, in diesem Fall in mehreren CSS-Dateien für jede Seite. Daher ist diese Einstellung nur dann schlechter zu verwenden, wenn Sie an der zukünftigen Verarbeitung jeder HTML-Seite unabhängig interessiert sind, und daher ist die Größe der CSS jeder einzelnen Seite das kritischste Problem.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Siehe auch

* Klasse [HtmlSaveOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)