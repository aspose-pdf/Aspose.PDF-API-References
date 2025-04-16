---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Поле HtmlSaveOptions. Это поле может содержать пользовательский метод, который возвращает URL или шаблон URL, если включена генерация нескольких страниц. См. детали ниже о CSS, как он должен быть помещен в сгенерированный результат HTML. Например, если вы хотите, чтобы конвертер поместил какой-то конкретный URL вместо стандартного имени файла CSS в сгенерированный CSS, тогда вам просто нужно создать и поместить в это свойство метод, который генерирует желаемый URL. Если установлен флаг 'SplitCssIntoPages', то эта пользовательская стратегия должна возвращать не точный URL CSS, а скорее строку-шаблон, которая может быть разрешена в URL для CSS этой или той страницы. Примеры ожидаемой возвращаемой строки в таком случае: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'
type: docs
weight: 300
url: /ru/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Поле HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Это поле может содержать пользовательский метод, который возвращает URL (или шаблон URL, если включена генерация нескольких страниц - см. детали ниже) для соответствующего CSS, как он должен быть помещен в сгенерированный результат HTML. Например, если вы хотите, чтобы конвертер поместил какой-то конкретный URL вместо стандартного имени файла CSS в сгенерированный CSS, тогда вам просто нужно создать и поместить в это свойство метод, который генерирует желаемый URL. Если установлен флаг 'SplitCssIntoPages', то эта пользовательская стратегия (если таковая имеется) должна возвращать не точный URL CSS, а скорее строку-шаблон, которая (после замены заполнителя номером страницы с помощью функции string.Format() внутри конвертера) может быть разрешена в URL для CSS этой или той страницы. Примеры ожидаемой возвращаемой строки в таком случае: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### См. также

* делегат [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* класс [HtmlSaveOptions](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)