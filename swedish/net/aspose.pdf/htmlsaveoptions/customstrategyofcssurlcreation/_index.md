---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions field. This field can contain custom method that returns URL Or URL template if multipage generation is on  see details below of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS then You should just create and put into this property method that generates desirable URL. If flag SplitCssIntoPages set then this custom strategy if any must return not exact URL of CSS but rather template string that after substitution of placeholder with page number with string.Format function inside converter can be resolved into URL for this or that pages CSS URL. Examples of expected return string in such case are SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0
type: docs
weight: 300
url: /sv/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Referens
description: HtmlSaveOptions-fält. Detta fält kan innehålla en anpassad metod som returnerar URL eller URL-mall om multipagesgenerering är aktiverad - se detaljer nedan om ämnet CSS som det bör sättas in i det genererade resultatet HTML. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard CSS-filnamn i den genererade CSS:en, då bör du bara skapa och sätta in denna egenskap metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är inställd, då måste denna anpassade strategi (om någon) returnera inte exakt URL för CSS utan snarare en mallsträng som (efter substitution av platshållare med sidnummer med string.Format() funktionen inuti konverteraren) kan lösas till URL för denna eller den sidans CSS-URL. Exempel på förväntad retursträng i sådana fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Se Även

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)