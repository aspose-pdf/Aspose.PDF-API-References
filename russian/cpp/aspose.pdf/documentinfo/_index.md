---
title: "Aspose::Pdf::DocumentInfo class"
linktitle: "DocumentInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DocumentInfo class. Представляет метаинформацию PDF‑документа в C++."
type: docs
weight: 4200
url: /ru/cpp/aspose.pdf/documentinfo/
---
## DocumentInfo class


Представляет метаинформацию PDF‑документа.

```cpp
class DocumentInfo : public System::Collections::Generic::Dictionary<System::String, System::String>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::String\&) override | Добавляет элемент с указанным ключом и значением в коллекцию. |
| [Clear](./clear/)() override | Очищает информацию о документе. |
| [ClearCustomData](./clearcustomdata/)() | Очищает только пользовательские данные, оставляя все остальные предопределённые значения (Title, Author и т.д.). |
| [DocumentInfo](./documentinfo/)(const System::SharedPtr\<Document\>\&) | Инициализирует экземпляр [DocumentInfo](./). |
| [get_Author](./get_author/)() | Получает автора документа. |
| [get_CreationDate](./get_creationdate/)() | Получает дату создания документа. |
| [get_CreationTimeZone](./get_creationtimezone/)() | Часовой пояс даты создания. |
| [get_Creator](./get_creator/)() | Получает создателя документа. |
| [get_Keywords](./get_keywords/)() | Получает или задает ключевые слова документа. |
| [get_ModDate](./get_moddate/)() | Получает дату изменения документа. |
| [get_ModTimeZone](./get_modtimezone/)() | Часовой пояс даты изменения. |
| [get_Producer](./get_producer/)() | Получает производителя документа. |
| [get_Subject](./get_subject/)() | Получает тему документа. |
| [get_Title](./get_title/)() | Получает заголовок документа. |
| [get_Trapped](./get_trapped/)() | Получает флаг trapped. |
| [idx_get](./idx_get/)(const System::String\&) const override | Получает значение, связанное с указанным ключом. |
| [idx_set](./idx_set/)(const System::String\&, System::String) override | Задает значение, связанное с указанным ключом. |
| static [IsPredefinedKey](./ispredefinedkey/)(const System::String\&) | Определяет, является ли ключ предопределённым (Title, Author и т.д.), а не пользовательским. |
| [Remove](./remove/)(const System::String\&) override | Удаляет элемент с указанным ключом из коллекции. |
| [set_Author](./set_author/)(const System::String\&) | Задает автора документа. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Задает дату создания документа. |
| [set_CreationTimeZone](./set_creationtimezone/)(System::TimeSpan) | Часовой пояс даты создания. |
| [set_Creator](./set_creator/)(const System::String\&) | Задает создателя документа. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Получает или задает ключевые слова документа. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Задает дату изменения документа. |
| [set_ModTimeZone](./set_modtimezone/)(System::TimeSpan) | Часовой пояс даты изменения. |
| [set_Producer](./set_producer/)(const System::String\&) | Задает производителя документа. |
| [set_Subject](./set_subject/)(const System::String\&) | Задает тему документа. |
| [set_Title](./set_title/)(const System::String\&) | Задает заголовок документа. |
| [set_Trapped](./set_trapped/)(const System::String\&) | Задает флаг trapped. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Устанавливает n‑й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
## См. также

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
