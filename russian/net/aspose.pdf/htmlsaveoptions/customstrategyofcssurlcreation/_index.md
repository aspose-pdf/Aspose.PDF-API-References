---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Поле HtmlSaveOptions. Это поле может содержать пользовательский метод, который возвращает URL или шаблон URL, если включена генерация нескольких страниц; см. детали ниже относительно CSS, который должен быть помещён в сгенерированный HTML. Например, если вы хотите, чтобы конвертер поместил какой‑то конкретный URL вместо стандартного имени файла CSS в сгенерированный CSS, то вам следует создать и задать в этом свойстве метод, генерирующий нужный URL. Если установлен флаг SplitCssIntoPages, то эта пользовательская стратегия, если она есть, должна возвращать не точный URL CSS, а шаблон строки, который после подстановки заполнителя номером страницы с помощью функции string.Format внутри конвертера может быть преобразован в URL CSS для той или иной страницы. Примеры ожидаемых возвращаемых строк в таком случае: SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /ru/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Это поле может содержать пользовательский метод, который возвращает URL (или шаблон URL, если включена генерация нескольких страниц — см. детали ниже) CSS‑файла, который должен быть вставлен в сгенерированный результат HTML. Например, если вы хотите, чтобы конвертер вставил какой‑то конкретный URL вместо стандартного имени CSS‑файла в сгенерированный CSS, то достаточно создать и задать в этом свойстве метод, генерирующий нужный URL. Если установлен флаг 'SplitCssIntoPages', то эта пользовательская стратегия (если она есть) должна возвращать не точный URL CSS, а шаблон строки, который (после подстановки номера страницы с помощью функции string.Format() внутри конвертера) может быть преобразован в URL CSS‑файла конкретной страницы. Примеры ожидаемых строк возврата в таком случае: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### См. также

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


