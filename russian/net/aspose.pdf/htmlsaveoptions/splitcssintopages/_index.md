---
title: SplitCssIntoPages
second_title: Aspose.PDF для справочника API .NET
description: Когда выбран многостраничный режим т.е. SplitIntoPages имеет значение true тогда этот атрибут определяет следует ли создавать отдельный CSS-файл для каждой HTML-страницы результата. По умолчанию этот атрибут равен false поэтому будет создан один большой общий CSS для всех создаваемых страниц. Суммарный размер всех CSS сгенерированных в этом режиме один CSS на страницу обычно намного больше чем размер одного большого файла CSS потому что в первом случае классы CSS дублируются в таком случае в нескольких файлах CSS для каждой страницы. Итак это параметр хуже использовать только тогда когда Вы заинтересованы в дальнейшей обработке каждой HTML-страницы независимо и поэтому размер CSS каждой отдельной страницы разобранной на части является наиболее важным вопросом.
type: docs
weight: 160
url: /ru/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

Когда выбран многостраничный режим (т.е. "SplitIntoPages" имеет значение "true"), тогда этот атрибут определяет, следует ли создавать отдельный CSS-файл для каждой HTML-страницы результата. По умолчанию этот атрибут равен false, поэтому будет создан один большой общий CSS для всех создаваемых страниц. Суммарный размер всех CSS, сгенерированных в этом режиме (один CSS на страницу) обычно намного больше, чем размер одного большого файла CSS, потому что в первом случае классы CSS дублируются в таком случае в нескольких файлах CSS для каждой страницы. Итак, это параметр хуже использовать только тогда, когда Вы заинтересованы в дальнейшей обработке каждой HTML-страницы независимо, и поэтому размер CSS каждой отдельной страницы, разобранной на части, является наиболее важным вопросом.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Смотрите также

* class [HtmlSaveOptions](../../htmlsaveoptions)
* пространство имен [Aspose.Pdf](../../htmlsaveoptions)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->