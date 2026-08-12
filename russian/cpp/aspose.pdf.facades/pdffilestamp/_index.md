---
title: "Aspose::Pdf::Facades::PdfFileStamp class"
linktitle: "PdfFileStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileStamp класс. Класс для добавления штампов (водяной знак или фон) в PDF‑файлы на C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class


Класс для добавления штампов (водяного знака или фона) в PDF‑файлы.

```cpp
class PdfFileStamp : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float) | Добавляет нижний колонтитул к страницам документа. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Добавляет нижний колонтитул к страницам документа. |
| [AddFooter](./addfooter/)(const System::String\&, float) | Добавляет изображение в качестве нижнего колонтитула к страницам документа. |
| [AddFooter](./addfooter/)(const System::String\&, float, float, float) | Добавляет изображение в качестве нижнего колонтитула страниц. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float) | Добавляет верхний колонтитул к странице. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Добавляет верхний колонтитул к страницам файла. |
| [AddHeader](./addheader/)(const System::String\&, float) | Добавляет изображение в качестве верхнего колонтитула к страницам файла. |
| [AddHeader](./addheader/)(const System::String\&, float, float, float) | Добавляет изображение в качестве верхнего колонтитула на страницах. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Добавляет изображение в качестве верхнего колонтитула на страницах. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Добавляет изображение в верхней части страницы. |
| [AddPageNumber](./addpagenumber/)(const System::String\&) | Добавьте номер страницы в файл. Текст номера [Page](../../aspose.pdf/page/) может содержать символ #, который будет заменён номером страницы. Номер [Page](../../aspose.pdf/page/) размещается в нижней части страницы, по центру по горизонтали. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&) | Добавляет номер страницы к странице. Номер [Page](../../aspose.pdf/page/) может содержать символ #, который будет заменён номером страницы. Номер [Page](../../aspose.pdf/page/) размещается в нижней части страницы, по центру по горизонтали. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t, float, float, float, float) | Добавляет номер страницы к страницам документа. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, float, float) | Добавляет номер страницы в указанном положении на странице. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Добавляет номер страницы к страницам документа. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, float, float) | Добавляет номер страницы в указанном положении на странице. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t) | Добавляет номер страницы к страницам. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t) | Добавляет номер страницы к страницам. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Stamp\>\&) | Добавляет штамп в файл. |
| [Close](./close/)() override | Закрывает открытые файлы и сохраняет изменения. Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом [Close()](./close/). |
| [get_AttachmentName](./get_attachmentname/)() const | Получает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Получает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [get_InputFile](./get_inputfile/)() const | Получает имя и путь входного файла. |
| [get_InputStream](./get_inputstream/)() const | Получает входной поток. |
| [get_KeepSecurity](./get_keepsecurity/)() const | Сохраняет безопасность, если true. (Эта функция будет реализована в следующих версиях). |
| [get_NumberingStyle](./get_numberingstyle/)() const | Получает стиль нумерации страниц. Возможные значения: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [get_OptimizeSize](./get_optimizesize/)() const | Получает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может вызвать более медленное выполнение и более высокие требования к памяти. Значение по умолчанию: false. |
| [get_OutputFile](./get_outputfile/)() const | Получает имя и путь выходного файла. |
| [get_OutputStream](./get_outputstream/)() const | Получает выходной поток. |
| [get_PageHeight](./get_pageheight/)() | Получает высоту первой страницы в исходном файле. |
| [get_PageNumberRotation](./get_pagenumberrotation/)() | Получает вращение номера страницы. [Rotation](../../aspose.pdf/rotation/) измеряется в градусах. По умолчанию 0. |
| [get_PageWidth](./get_pagewidth/)() | Получает ширину первой страницы во входном файле. |
| [get_Response](./get_response/)() const | Получает объект Response, в котором будет сохранён результат операции. |
| [get_SaveOptions](./get_saveoptions/)() const | Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_StampId](./get_stampid/)() const | [Stamp](../stamp/) Идентификатор следующей добавляемой печати (включая колонтитулы страниц/заголовки/номера страниц). |
| [get_StartingNumber](./get_startingnumber/)() const | Получает начальный номер первой страницы во входном файле. Последующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлено в 100, страницы документа будут иметь номера 100, 101, 102... |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&) | Конструктор для [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор для [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&, bool) | Конструктор для [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) | Конструктор [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)() | Конструктор [PdfFileStamp](./). Входной и выходной файлы могут быть указаны через соответствующие свойства. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfFileStamp](./) на основе *документа*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [PdfFileStamp](./) на основе *документа*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый объект [PdfFileStamp](./) на основе *документа*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт [PdfFileStamp](./), который сохранит результат в объект HttpResponse. |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт [PdfFileStamp](./), который сохранит результат в объект HttpResponse. |
| [Save](./save/)(System::String) override | Сохраняет результат в указанный файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет документ в указанный поток. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Устанавливает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Устанавливает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Устанавливает имя и путь входного файла. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает входной поток. |
| [set_KeepSecurity](./set_keepsecurity/)(bool) | Сохраняет безопасность, если true. (Эта функция будет реализована в следующих версиях). |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Устанавливает стиль нумерации страниц. Возможные значения: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и большим требованиям к памяти. Значение по умолчанию: false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Устанавливает имя и путь выходного файла. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает выходной поток. |
| [set_PageNumberRotation](./set_pagenumberrotation/)(float) | Устанавливает вращение номера страницы. [Rotation](../../aspose.pdf/rotation/) измеряется в градусах. По умолчанию 0. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Устанавливает объект Response, в котором будет сохранён результат операции. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Устанавливает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_StampId](./set_stampid/)(int32_t) | [Stamp](../stamp/) Идентификатор следующей добавляемой печати (включая колонтитулы страниц/заголовки/номера страниц). |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Устанавливает начальный номер первой страницы во входном файле. Последующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлено в 100, страницы документа будут иметь номера 100, 101, 102... |
## Поля

| Поле | Описание |
| --- | --- |
| static [PosBottomLeft](./posbottomleft/) | Позиция снизу слева. |
| static [PosBottomMiddle](./posbottommiddle/) | Позиция снизу по центру. |
| static [PosBottomRight](./posbottomright/) | Позиция снизу справа. |
| static [PosSidesLeft](./possidesleft/) | Позиция [Left](../../aspose.pdf/left/). |
| static [PosSidesRight](./possidesright/) | Позиция [Right](../../aspose.pdf/right/). |
| static [PosUpperLeft](./posupperleft/) | Позиция сверху слева. |
| static [PosUpperMiddle](./posuppermiddle/) | Позиция сверху по центру. |
| static [PosUpperRight](./posupperright/) | [Right](../../aspose.pdf/right/) верхнее положение. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
