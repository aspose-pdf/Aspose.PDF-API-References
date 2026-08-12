---
title: "Класс Aspose::Pdf::Text::TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::TextExtractionErrorLocation. Представляет место в PDF‑документе, где возникла ошибка извлечения текста, в C++."
type: docs
weight: 4000
url: /ru/cpp/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class


Представляет место в PDF‑документе, где возникла ошибка извлечения текста.

```cpp
class TextExtractionErrorLocation : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_FontUsedKey](./get_fontusedkey/)() const | Ключ (имя) объекта PDF [Font](../font/), используемый для отображения оператора, вызывающего ошибку извлечения текста. |
| [get_FormKey](./get_formkey/)() const | Ключ (имя) PDF‑объекта Form XObject, в котором обнаружена ошибка извлечения текста из потока содержимого. Не пустой, если ObjectType == 'xForm'. |
| [get_ObjectType](./get_objecttype/)() const | Тип PDF‑объекта ([Page](../../aspose.pdf/page/) или xForm), в котором обнаружена ошибка извлечения текста из потока содержимого. |
| [get_OperatorIndex](./get_operatorindex/)() const | Индекс оператора отображения текста в потоке содержимого (коллекция операторов), вызывающего ошибку извлечения текста. |
| [get_OperatorString](./get_operatorstring/)() const | Оператор отображения [Text](../), вызывающий ошибку извлечения текста. |
| [get_PageNumber](./get_pagenumber/)() const | Номер страницы документа, где обнаружена ошибка извлечения текста. |
| [get_Path](./get_path/)() const | Расположение PDF‑документа, в котором возникла ошибка извлечения текста. |
| [get_TextStartPoint](./get_textstartpoint/)() const | Ключ (имя) объекта PDF [Font](../font/), используемый для отображения оператора, вызывающего ошибку извлечения текста. |
| [ToString](./tostring/)() const override | Возвращает строковое представление. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
