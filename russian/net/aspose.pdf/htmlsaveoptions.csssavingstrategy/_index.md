---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Вы можете назначить этому свойству пользовательскую стратегию, которая реализует обработку и/или сохранение одной части CSS, созданной во время конвертации PDF в HTML. В таком случае обработка (например, сохранение в поток или на диск) должна выполняться в этом пользовательском коде
type: docs
weight: 5590
url: /ru/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Делегат HtmlSaveOptions.CssSavingStrategy

Вы можете назначить этому свойству пользовательскую стратегию, которая реализует обработку и/или сохранение одной части CSS, созданной во время конвертации PDF в HTML. В таком случае обработка (например, сохранение в поток или на диск) должна выполняться в этом пользовательском коде

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | представляет набор данных, который может быть использован для сохранения предоставленной части CSS |

### См. также

* класс [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* класс [HtmlSaveOptions](../htmlsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)