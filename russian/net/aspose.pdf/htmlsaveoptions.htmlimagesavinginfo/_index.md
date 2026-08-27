---
title: "Класс HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Этот класс представляет набор данных, связанных с сохранением внешних файлов изображений при преобразовании PDF в HTML"
type: docs
weight: 5770
url: /ru/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Этот класс представляет набор данных, связанных с сохранением файлов изображений внешних ресурсов во время преобразования PDF в HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Устанавливается конвертером. Предполагаемое имя файла, которое передаётся от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать файл или где его сохранять. |

## Поля

| Имя | Описание |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Устанавливается конвертером. Представляет бинарное содержимое сохранённого файла. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Этот флаг должен быть установлен в \"true\" в пользовательском коде, если по каким‑то причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным способом для конвертера. Таким образом, установка значения true означает, что пользовательский код не обработал указанный файл, и конвертер должен обработать его самостоятельно (и при сохранении, и при указании имени в ссылочном файле). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Сообщает пользовательскому коду, к какой странице сгенерированного набора HTML‑файлов относится сохранённое изображение. Если разбиение на страницы отключено, это значение всегда равно '1', поскольку в этом случае генерируется только одна HTML‑страница. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Представляет тип сохранённого изображения, на которое ссылается HTML. Устанавливается конвертером и может использоваться пользовательским кодом для принятия решения о дальнейших действиях. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Сохранённое изображение может относиться к самому HTML или быть извлечено из SVG, встроенного в HTML. Это свойство может сообщить пользовательскому коду тип родительского элемента обработанного изображения. Устанавливается конвертером и может использоваться пользовательским кодом для решения, что делать с этим изображением (например, пользовательский код может решить, где сохранить изображение или как его следует ссылаться в содержимом родителя). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Сообщает пользовательскому коду, к какой странице оригинального PDF‑документа относится сохранённое изображение. Поскольку может быть сохранено не все страницы оригинального документа, это значение указывает номер страницы‑хоста в оригинальном PDF. Если номер оригинальной страницы по какой‑то причине неизвестен, он всегда возвращает '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передаётся от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать файл или где его сохранять. |

### См. также

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


