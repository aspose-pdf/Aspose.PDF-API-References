---
title: "Aspose::Pdf::ExportFieldsOptions класс"
linktitle: "ExportFieldsOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ExportFieldsOptions класс. Представляет базовый класс параметров для экспорта полей формы в C++."
type: docs
weight: 4800
url: /ru/cpp/aspose.pdf/exportfieldsoptions/
---
## ExportFieldsOptions class


Представляет базовый класс параметров для экспорта полей формы.

```cpp
class ExportFieldsOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [ExportFieldsOptions](./exportfieldsoptions/)() |  |
| [get_ExportPasswordValue](./get_exportpasswordvalue/)() const | Получает значение, указывающее, следует ли экспортировать значение пароля. |
| [get_FieldSelector](./get_fieldselector/)() const | Получает делегат, определяющий, следует ли экспортировать конкретное поле. Если делегат равен **null**, экспортируются все поля (поведение по умолчанию). |
| [set_ExportPasswordValue](./set_exportpasswordvalue/)(bool) | Устанавливает значение, указывающее, следует ли экспортировать значение пароля. |
| [set_FieldSelector](./set_fieldselector/)(System::Predicate\<System::SharedPtr\<Forms::Field\>\>) | Устанавливает делегат, определяющий, следует ли экспортировать конкретное поле. Если делегат равен **null**, экспортируются все поля (поведение по умолчанию). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
