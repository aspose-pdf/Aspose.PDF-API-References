---
title: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class"
linktitle: "HiddenDataSanitizer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class. Представляет класс для очистки скрытых данных в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/
---
## HiddenDataSanitizer class


Представляет класс для очистки скрытых данных.

```cpp
class HiddenDataSanitizer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [HiddenDataSanitizer](./hiddendatasanitizer/)(const System::SharedPtr\<HiddenDataSanitizationOptions\>\&) | Обеспечивает функциональность по очистке скрытых данных из PDF‑документа, гарантируя удаление или преобразование чувствительной или ненужной информации, такой как метаданные, аннотации, JavaScript или приватный контент. |
| [Sanitize](./sanitize/)(const System::SharedPtr\<Document\>\&) | Очищает заданный PDF‑документ, удаляя или преобразуя скрытые данные. |
| static [SanitizeAllToImages](./sanitizealltoimages/)(const System::SharedPtr\<Document\>\&, int32_t) | Заменяет содержимое страниц изображениями и удаляет другие скрытые данные. Позволяет удалять скрытый текст с фоновым цветом, а также текст, скрытый под изображениями. Также полностью удаляет все интерактивные элементы. Документ конвертируется в изображения в текущем виде, а затем очищается от оставшихся скрытых данных. Если необходимо сначала очистить, а затем конвертировать, используйте метод главного класса. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
