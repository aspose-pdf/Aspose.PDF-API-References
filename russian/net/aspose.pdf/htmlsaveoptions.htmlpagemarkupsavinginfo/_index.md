---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Если свойство SplitToPages класса HtmlSaveOptions установлено, то во время конвертации PDF в HTML создается несколько HTML-файлов (по одному HTML-файлу на каждую конвертированную страницу). Этот класс представляет собой набор данных, относящихся к пользовательскому сохранению разметки одной HTML-страницы во время конвертации PDF в HTML.
type: docs
weight: 5670
url: /ru/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Если свойство SplitToPages класса HtmlSaveOptions установлено, то во время конвертации PDF в HTML создается несколько HTML-файлов (по одному HTML-файлу на каждую конвертированную страницу). Этот класс представляет собой набор данных, относящихся к пользовательскому сохранению разметки одной HTML-страницы во время конвертации PDF в HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Устанавливается конвертером. Представляет сохраненный HTML в виде потока |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Должен быть установлен в пользовательском коде при необходимости. Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предоставленная HTML-разметка должна обрабатываться не пользовательским кодом, а кодом самого конвертера стандартным для конвертера способом. Таким образом, установка этого флага в пользовательском коде означает, что пользовательский код не обработал ссылочный файл, и конвертер должен обработать его самостоятельно |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Устанавливается конвертером. Если установлено свойство SplitToPages, то во время конвертации создается несколько HTML-файлов (по одному HTML-файлу на каждую конвертированную страницу). Это свойство содержит порядковый номер сохраненного HTML-файла. Свойство может использоваться в логике пользовательского кода для решения, как обрабатывать или где сохранять HTML-страницу, и если разделение на страницы отключено, это значение всегда содержит '1', так как в таком случае генерируется только одна большая HTML-страница для всего исходного документа. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Устанавливается конвертером. Если свойство SplitToPages установлено, то во время конвертации создается несколько HTML-файлов (по одному HTML-файлу на каждую конвертированную страницу). Это свойство сообщает пользовательскому коду, с какой страницы оригинального PDF была создана сохраненная HTML-разметка. Если номер оригинальной страницы по какой-либо причине неизвестен или SplitOnPages=false, то это свойство всегда содержит '0', что сигнализирует о том, что конвертер не может предоставить точный номер страницы оригинального PDF для предоставленного файла HTML-разметки. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или где сохранять содержимое |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)