---
title: "Aspose::Pdf::BatesNArtifact class"
linktitle: "BatesNArtifact"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::BatesNArtifact класс. Класс описывает артефакт нумерации Бейтса в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf/batesnartifact/
---
## BatesNArtifact class


Класс описывает артефакт нумерации Бейтса.

```cpp
class BatesNArtifact : public Aspose::Pdf::PaginationArtifact
```

## Методы

| Метод | Описание |
| --- | --- |
| [BatesNArtifact](./batesnartifact/)() | Инициализирует новый экземпляр класса [BatesNArtifact](./). Этот конструктор является внутренним и создает экземпляр артефакта заголовка со значениями по умолчанию. |
| [get_NumberOfDigits](./get_numberofdigits/)() const | Получает количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6. |
| [get_Prefix](./get_prefix/)() const | Получает префикс, добавляемый к номеру Бейтса. |
| [get_StartNumber](./get_startnumber/)() const | Получает начальное число для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1. |
| [get_Suffix](./get_suffix/)() const | Получает суффикс, добавляемый к номеру Бейтса. |
| [set_NumberOfDigits](./set_numberofdigits/)(int32_t) | Устанавливает количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6. |
| [set_Prefix](./set_prefix/)(const System::String\&) | Устанавливает префикс, добавляемый к номеру Бейтса. |
| [set_StartNumber](./set_startnumber/)(int32_t) | Устанавливает начальное число для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1. |
| [set_Suffix](./set_suffix/)(const System::String\&) | Устанавливает суффикс, добавляемый к номеру Бейтса. |
## См. также

* Class [PaginationArtifact](../paginationartifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
