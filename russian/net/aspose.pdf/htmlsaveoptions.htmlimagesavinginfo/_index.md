---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Этот класс представляет собой набор данных, связанных с сохранением файлов изображений внешних ресурсов во время конвертации PDF в HTML.
type: docs
weight: 5640
url: /ru/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Этот класс представляет собой набор данных, связанных с сохранением файлов изображений внешних ресурсов во время конвертации PDF в HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или где сохранить этот файл. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Устанавливается конвертером. Представляет бинарное содержимое сохраненного файла. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-то причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а кодом самого конвертера стандартным для конвертера способом. Таким образом, установка этого флага в true означает, что пользовательский код не обработал указанный файл, и конвертер должен обработать его самостоятельно (в обоих смыслах - для сохранения где-то и для именования в ссылочном файле). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Указывает пользовательскому коду, к какой странице сгенерированного набора HTML-страниц относится сохраненное изображение. Если разделение на страницы отключено, это значение всегда содержит '1', так как в этом случае генерируется только одна HTML-страница. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Представляет тип сохраненного изображения, на которое ссылается HTML. Устанавливается конвертером и может использоваться в пользовательском коде для решения, что следует делать. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Сохраненное изображение может относиться к самому HTML или может быть извлечено из SVG, встроенного в HTML. Это свойство может сообщить пользовательскому коду, каков тип родителя обрабатываемого изображения. Устанавливается конвертером и может использоваться в пользовательском коде для решения, что следует делать с этим изображением (например, пользовательский код может решить, где сохранить изображение или как оно должно быть упомянуто в содержимом родителя). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Указывает пользовательскому коду, к какой странице оригинального PDF-документа относится сохраненное изображение. Поскольку возможно, что будут сохранены не все страницы оригинального документа, это значение сообщает нам о номере страницы-хоста в оригинальном PDF. Если оригинальный номер страницы по какой-то причине неизвестен, он всегда возвращает '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или где сохранить этот файл. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)