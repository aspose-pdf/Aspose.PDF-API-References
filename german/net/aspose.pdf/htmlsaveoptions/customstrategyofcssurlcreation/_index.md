---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-Feld. Dieses Feld kann eine benutzerdefinierte Methode enthalten, die eine URL oder URL-Vorlage zurückgibt, wenn die Mehrseitengenerierung aktiviert ist - siehe Details unten zum Thema CSS, wie es im generierten Ergebnis-HTML eingefügt werden sollte. Z.B. wenn Sie möchten, dass der Konverter eine bestimmte URL anstelle des Standard-CSS-Dateinamens in das generierte CSS einfügt, sollten Sie einfach eine Methode erstellen und in diese Eigenschaft einfügen, die die gewünschte URL generiert. Wenn das Flag 'SplitCssIntoPages' gesetzt ist, muss diese benutzerdefinierte Strategie (falls vorhanden) nicht die genaue URL des CSS zurückgeben, sondern vielmehr eine Vorlagenzeichenfolge, die (nach der Ersetzung des Platzhalters mit der Seitennummer mit der string.Format()-Funktion im Konverter) in die URL für das CSS dieser oder jener Seite aufgelöst werden kann. Beispiele für die erwartete Rückgabezeichenfolge in einem solchen Fall sind: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')
type: docs
weight: 300
url: /de/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation-Feld

Dieses Feld kann eine benutzerdefinierte Methode enthalten, die eine URL (oder URL-Vorlage, wenn die Mehrseitengenerierung aktiviert ist - siehe Details unten) des betreffenden CSS zurückgibt, wie es im generierten Ergebnis-HTML eingefügt werden sollte. Z.B. wenn Sie möchten, dass der Konverter eine bestimmte URL anstelle des Standard-CSS-Dateinamens in das generierte CSS einfügt, sollten Sie einfach eine Methode erstellen und in diese Eigenschaft einfügen, die die gewünschte URL generiert. Wenn das Flag 'SplitCssIntoPages' gesetzt ist, muss diese benutzerdefinierte Strategie (falls vorhanden) nicht die genaue URL des CSS zurückgeben, sondern vielmehr eine Vorlagenzeichenfolge, die (nach der Ersetzung des Platzhalters mit der Seitennummer mit der string.Format()-Funktion im Konverter) in die URL für das CSS dieser oder jener Seite aufgelöst werden kann. Beispiele für die erwartete Rückgabezeichenfolge in einem solchen Fall sind: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Siehe auch

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)