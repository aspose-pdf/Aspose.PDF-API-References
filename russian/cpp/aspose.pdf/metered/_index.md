---
title: "Aspose::Pdf::Metered class"
linktitle: "Metered"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Metered. Предоставляет методы для установки ключа metered в C++."
type: docs
weight: 11300
url: /ru/cpp/aspose.pdf/metered/
---
## Metered class


Предоставляет методы установки измеряемого ключа.

```cpp
class Metered : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Получает кредит потребления. |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Получает размер файла потребления. |
| [GetProductName](./getproductname/)() | Получить название продукта. |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Проверьте, лицензирован ли metered. |
| [Metered](./metered/)() | Инициализирует новый экземпляр этого класса. |
| [SetMeteredKey](./setmeteredkey/)(const System::String\&, const System::String\&) | Устанавливает публичный и приватный ключ metered. Если вы приобретаете лицензию metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако, если постоянно не удаётся загрузить данные потребления и проходит более 24 часов, лицензия будет переключена в статус оценки; чтобы избежать такой ситуации, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
