---
title: "Делегат HtmlSaveOptions.CssSavingStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Вы можете присвоить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение одной части CSS, созданной во время конвертации PDF в HTML. В таком случае обработка, например сохранение в поток или на диск, должна выполняться в этом пользовательском коде."
type: docs
weight: 5720
url: /ru/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

Вы можете присвоить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение одной части CSS, созданной во время конвертации PDF в HTML. В таком случае обработка (например сохранение в поток или на диск) должна выполняться в этом пользовательском коде.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | представляет набор данных, который может использоваться для сохранения предоставленной части CSS |

### См. также

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


