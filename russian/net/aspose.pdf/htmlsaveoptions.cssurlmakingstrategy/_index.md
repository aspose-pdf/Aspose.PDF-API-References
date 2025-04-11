---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Вы можете назначить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, упомянутого в сгенерированном HTML-документе. Например, если вы хотите сделать CSS, упомянутым в HTML, например, как otherPage.ASPXCssIDzjjkklj, тогда такая пользовательская стратегия должна вернуть otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /ru/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Делегат HtmlSaveOptions.CssUrlMakingStrategy

Вы можете назначить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, упомянутого в сгенерированном HTML-документе. Например, если вы хотите сделать CSS, упомянутым в HTML, например, как "otherPage.ASPX?CssID=zjjkklj", тогда такая пользовательская стратегия должна вернуть "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | представляет набор данных, который можно использовать для генерации URL CSS |

### Возвращаемое значение

должно вернуть строку, представляющую URL CSS или шаблон URL

### См. также

* класс [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* класс [HtmlSaveOptions](../htmlsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)