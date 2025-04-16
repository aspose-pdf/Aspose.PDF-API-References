---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: DocSaveOptions-Eigenschaft. In PDF können Wörter innerlich mit Operatoren dargestellt werden, die Wörter drucken, indem sie unabhängig ihre Buchstaben oder Silben drucken. Um Wörter zu erkennen, müssen wir manchmal Gruppen von unabhängigen Zeichen erkennen, die in der Tat Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen, die während der Erkennung von Wörtern im Quell-PDF als Abstand zwischen Wörtern behandelt werden müssen. Es ist auf die Schriftgröße normiert - 1,0 bedeutet 100% der angenommenen Schriftgröße des Wortes. ACHTUNG! Es wird nur in Fällen verwendet, in denen das Quell-PDF spezifische, selten verwendete Schriftarten enthält, für die der optimale Wert nicht aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter nichts im Ergebnisdokument.
type: docs
weight: 120
url: /de/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity-Eigenschaft

In PDF können Wörter innerlich mit Operatoren dargestellt werden, die Wörter drucken, indem sie unabhängig ihre Buchstaben oder Silben drucken. Um Wörter zu erkennen, müssen wir manchmal Gruppen von unabhängigen Zeichen erkennen, die in der Tat Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die während der Erkennung von Wörtern im Quell-PDF als Abstand zwischen Wörtern behandelt werden müssen. (Das Vorhandensein von leerem Raum, der mindestens diese Breite zwischen den Buchstaben hat, bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Es ist auf die Schriftgröße normiert - 1,0 bedeutet 100% der angenommenen Schriftgröße des Wortes. ACHTUNG! Es wird nur in Fällen verwendet, in denen das Quell-PDF spezifische, selten verwendete Schriftarten enthält, für die der optimale Wert nicht aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter nichts im Ergebnisdokument.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Siehe auch

* Klasse [DocSaveOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)