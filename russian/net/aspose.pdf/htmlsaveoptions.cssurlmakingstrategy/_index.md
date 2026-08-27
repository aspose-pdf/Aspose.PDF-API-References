---
title: "Делегат HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Вы можете присвоить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, используемого в сгенерированном HTML‑документе. Например, если вы хотите, чтобы CSS в HTML ссылался, например, как otherPage.ASPXCssIDzjjkklj, то такая пользовательская стратегия должна возвращать otherPage.ASPXCssIDzjjkklj."
type: docs
weight: 5730
url: /ru/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

Вы можете присвоить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, используемого в сгенерированном HTML‑документе. Например, если вы хотите, чтобы CSS в HTML ссылался, например, как "otherPage.ASPX?CssID=zjjkklj", то такая пользовательская стратегия должна возвращать "otherPage.ASPX?CssID=zjjkklj".

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | представляет набор данных, который может использоваться для генерации URL CSS |

### Возвращаемое значение

должен возвращать строку, представляющую URL CSS или шаблон URL

### См. также

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


