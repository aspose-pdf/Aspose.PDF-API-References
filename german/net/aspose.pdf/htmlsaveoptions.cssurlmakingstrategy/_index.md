---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Erstellung der URL des in dem generierten HTML-Dokument referenzierten CSS implementiert. Z.B. wenn Sie CSS im HTML als "andereSeite.ASPXCssIDzjjkklj" referenzieren möchten. Dann muss eine solche benutzerdefinierte Strategie "andereSeite.ASPXCssIDzjjkklj" zurückgeben.
type: docs
weight: 5600
url: /de/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy-Delegat

Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Erstellung der URL des in dem generierten HTML-Dokument referenzierten CSS implementiert. Z.B. wenn Sie CSS im HTML als "andereSeite.ASPX?CssID=zjjkklj" referenzieren möchten. Dann muss eine solche benutzerdefinierte Strategie "andereSeite.ASPX?CssID=zjjkklj" zurückgeben.

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | stellt eine Menge von Daten dar, die zur Generierung der CSS-URL verwendet werden können |

### Rückgabewert

muss einen String zurückgeben, der die CSS-URL oder die URL-Vorlage darstellt

### Siehe auch

* Klasse [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)