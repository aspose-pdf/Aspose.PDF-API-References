---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "HtmlSaveOptions fält. Detta fält kan innehålla en anpassad metod som returnerar URL eller URL‑mall om flersidig generering är på. Se detaljer nedan om den aktuella CSS som ska placeras i det genererade HTML‑resultatet. T.ex. om du vill att konverteraren placerar en specifik URL istället för standard‑CSS‑filnamnet i den genererade CSS‑filen, bör du skapa och tilldela den här egenskapen en metod som genererar önskad URL. Om flaggan SplitCssIntoPages är satt måste denna anpassade strategi, om någon, returnera en mallsträng snarare än en exakt CSS‑URL, så att efter ersättning av platshållaren med sidnummer via string.Format‑funktionen i konverteraren kan den omvandlas till URL för respektive sidas CSS‑URL. Exempel på förväntade retursträngar i sådant fall är SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /sv/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑koden. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard‑CSS‑filnamnet i den genererade CSS‑en, bör du helt enkelt skapa och tilldela den här egenskapen en metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är satt, måste denna anpassade strategi (om någon) returnera inte den exakta URL‑en för CSS utan snarare en mallsträng som (efter ersättning av platshållaren med sidnummer via string.Format()-funktionen i konverteraren) kan omvandlas till en URL för den aktuella sidans CSS‑URL. Exempel på förväntade retursträngar i ett sådant fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Se även

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


