---
title: "Класс Aspose::Pdf::LowCode::TextExtractorOptions"
linktitle: "TextExtractorOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::TextExtractorOptions. Представляет параметры извлечения текста для плагина TextExtractor в C++."
type: docs
weight: 8700
url: /ru/cpp/aspose.pdf.lowcode/textextractoroptions/
---
## TextExtractorOptions class


Представляет параметры извлечения текста для плагина [TextExtractor](../textextractor/).

```cpp
class TextExtractorOptions : public Aspose::Pdf::LowCode::PdfExtractorOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Определяет различные режимы, которые могут использоваться при конвертации PDF‑документа в текст. См. класс [TextExtractorOptions](./). |
## Методы

| Метод | Описание |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Получает режим форматирования. |
| [get_OperationName](./get_operationname/)() override | Возвращает имя операции. |
| [TextExtractorOptions](./textextractoroptions/)(TextExtractorOptions::TextFormattingMode) | Инициализирует новый экземпляр объекта [TextExtractorOptions](./) для указанного режима форматирования текста. |
| [TextExtractorOptions](./textextractoroptions/)() | Инициализирует новый экземпляр объекта [TextExtractorOptions ](./) с режимом форматирования текста 'Raw' (по умолчанию). |
## Примечания


Объект [TextExtractorOptions](./) используется для установки [TextFormattingMode](./textformattingmode/) и других параметров операции извлечения текста. Также он наследует функции для добавления данных (файлов, потоков), представляющих входные PDF‑документы.
## См. также

* Class [PdfExtractorOptions](../pdfextractoroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
