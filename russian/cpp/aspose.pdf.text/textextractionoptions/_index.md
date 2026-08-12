---
title: "Aspose::Pdf::Text::TextExtractionOptions класс"
linktitle: "TextExtractionOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextExtractionOptions класс. Представляет параметры извлечения текста в C++."
type: docs
weight: 4100
url: /ru/cpp/aspose.pdf.text/textextractionoptions/
---
## TextExtractionOptions class


Представляет параметры извлечения текста.

```cpp
class TextExtractionOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. Смотрите класс [TextDevice](../). |
## Методы

| Метод | Описание |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Получает режим форматирования. |
| [get_ScaleFactor](./get_scalefactor/)() const | Получает коэффициент, который будет применён для масштабирования размера шрифта во время извлечения в чистом режиме. Уменьшение значения приводит к большему количеству пробелов в извлечённом тексте. Значение по умолчанию — 1, без масштабирования; установка значения в ноль позволяет алгоритму выбирать масштаб автоматически. |
| [set_FormattingMode](./set_formattingmode/)(TextExtractionOptions::TextFormattingMode) | Получает режим форматирования. |
| [set_ScaleFactor](./set_scalefactor/)(double) | Устанавливает коэффициент, который будет применён для масштабирования размера шрифта во время извлечения в чистом режиме. Уменьшение значения приводит к большему количеству пробелов в извлечённом тексте. Значение по умолчанию — 1, без масштабирования; установка значения в ноль позволяет алгоритму выбирать масштаб автоматически. |
| [TextExtractionOptions](./textextractionoptions/)(TextExtractionOptions::TextFormattingMode) | Инициализирует новый экземпляр объекта [TextExtractionOptions](./) для указанного режима форматирования текста. |
## См. также

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
