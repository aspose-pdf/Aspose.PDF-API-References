---
title: "Класс HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Если свойство SplitToPages у HtmlSaveOptions, то при преобразовании PDF в HTML создаются несколько HTML‑файлов, по одному файлу на каждую преобразованную страницу. Этот класс представляет набор данных, связанных с пользовательским сохранением разметки одной HTML‑страницы при преобразовании PDF в HTML."
type: docs
weight: 5800
url: /ru/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Если свойство SplitToPages у HtmlSaveOptions, то при преобразовании PDF в HTML создаются несколько HTML‑файлов (по одному файлу на каждую преобразованную страницу). Этот класс представляет набор данных, связанных с пользовательским сохранением разметки одной HTML‑страницы при преобразовании PDF в HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Поля

| Имя | Описание |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Устанавливается конвертером. Представляет сохранённый HTML в виде потока. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Должно устанавливаться в пользовательском коде при необходимости. Этот флаг должен быть установлен в значение "true" в пользовательском коде, если по каким‑то причинам предоставленная html‑разметка должна обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным способом для конвертера. Таким образом, установка этого флага в пользовательском коде означает, что пользовательский код не обработал указанный файл, и конвертер должен обработать его самостоятельно. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Устанавливается конвертером. Если свойство SplitToPages включено, то при преобразовании создаются несколько HTML‑файлов (по одному файлу на каждую преобразованную страницу). Это свойство содержит порядковый номер файла сохранённой HTML‑страницы. Свойство может использоваться в логике пользовательского кода для решения, как обрабатывать или куда сохранять HTML‑страницу, и если разбиение на страницы отключено, это значение всегда равно '1', поскольку в таком случае генерируется одна большая HTML‑страница для всего исходного документа. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Устанавливается конвертером. Если свойство SplitToPages включено, то при преобразовании создаются несколько HTML‑файлов (по одному файлу на каждую преобразованную страницу). Это свойство сообщает пользовательскому коду, с какой страницы оригинального PDF была создана сохранённая HTML‑разметка. Если номер оригинальной страницы по какой‑то причине неизвестен или SplitOnPages=false, то это свойство всегда содержит '0', что сигнализирует, что конвертер не может предоставить точный номер оригинальной страницы PDF для данного файла HTML‑разметки. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передаётся от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или куда сохранять содержимое. |

### См. также

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


