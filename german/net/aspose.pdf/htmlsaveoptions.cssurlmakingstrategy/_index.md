---
title: HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF für .NET-API-Referenz
description: Sie können diesem Eigenschaftsdelegierten zuweisen der von einer benutzerdefinierten Methode erstellt wurde die die Erstellung der URL von CSS implementiert auf die im generierten HTML-Dokument verweist. Wenn Sie z. B. möchten dass CSS in HTML referenziert wird z. B. als otherPage.ASPXCssIDzjjkklj  muss eine solche benutzerdefinierte Strategie otherPage.ASPXCssIDzjjkklj zurückgeben.
type: docs
weight: 3470
url: /de/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

Sie können diesem Eigenschaftsdelegierten zuweisen, der von einer benutzerdefinierten Methode erstellt wurde, die die Erstellung der URL von CSS implementiert, auf die im generierten HTML-Dokument verweist. Wenn Sie z. B. möchten, dass CSS in HTML referenziert wird, z. B. als "otherPage.ASPX?CssID=zjjkklj" , muss eine solche benutzerdefinierte Strategie "otherPage.ASPX?CssID=zjjkklj" zurückgeben.

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | stellt einen Datensatz dar, der zur Generierung der CSS-URL verwendet werden kann |

### Rückgabewert

muss eine Zeichenfolge zurückgeben, die die CSS-URL oder die URL-Vorlage darstellt

### Siehe auch

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
