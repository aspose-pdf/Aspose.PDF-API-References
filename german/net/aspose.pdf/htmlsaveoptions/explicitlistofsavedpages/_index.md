---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-Eigenschaft. Mit dieser Eigenschaft können Sie explizit definieren, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1-basierte Nummern haben. Das heißt, gültige Seitenzahlen müssen aus dem Bereich 1...NumberOfPagesInConvertedDocument entnommen werden. Die Reihenfolge, in der die Seiten in dieser Liste erscheinen, hat keinen Einfluss auf ihre Reihenfolge in den resultierenden HTML-Seiten - in den Ergebnisseiten werden sie immer in der Reihenfolge angezeigt, in der sie im Quell-PDF vorhanden sind. Wenn diese Liste null ist (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitenzahl in dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst.
type: docs
weight: 70
url: /de/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages-Eigenschaft

Mit dieser Eigenschaft können Sie explizit definieren, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1-basierte Nummern haben. Das heißt, gültige Seitenzahlen müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) entnommen werden. Die Reihenfolge, in der die Seiten in dieser Liste erscheinen, hat keinen Einfluss auf ihre Reihenfolge in den resultierenden HTML-Seiten - in den Ergebnisseiten werden sie immer in der Reihenfolge angezeigt, in der sie im Quell-PDF vorhanden sind. Wenn diese Liste null ist (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitenzahl in dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Siehe auch

* Klasse [HtmlSaveOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)