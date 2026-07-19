---
title: "Класс Aspose::Pdf::XfaConverter::XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::XfaConverter::XfaParserOptions. Класс для обработки инкапсуляции связанных данных в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.xfaconverter/xfaparseroptions/
---
## XfaParserOptions class


Класс для обработки связанных данных и их инкапсуляции.

```cpp
class XfaParserOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Получает базовый путь. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Если это свойство истинно, то для требуемых Xfa \"исключённых групп\" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из‑за отсутствия аналогов исключённых групп при конвертации Xfa‑представления форм в стандарт. По умолчанию значение ложно. |
| [get_PageSize](./get_pagesize/)() const | Получает размер страницы. |
| [get_Signed](./get_signed/)() const | Если это свойство истинно, документ будет конвертирован с использованием потока формы xfa (если он существует). Если ложно, поток формы xfa будет игнорироваться. Это свойство было введено, потому что не ясно, как вычислить контрольную сумму, используемую для проверки подписи. |
| [get_UriResolver](./get_uriresolver/)() const | Получает разрешитель URI. |
| [set_BasePath](./set_basepath/)(const System::SharedPtr\<System::Uri\>\&) | Устанавливает базовый путь. |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Если это свойство истинно, то для требуемых Xfa \"исключённых групп\" будут нарисованы дополнительные красные прямоугольники. Это свойство было введено из‑за отсутствия аналогов исключённых групп при конвертации Xfa‑представления форм в стандарт. По умолчанию значение ложно. |
| [set_PageSize](./set_pagesize/)(System::Drawing::SizeF) | Устанавливает размер страницы. |
| [set_Signed](./set_signed/)(bool) | Если это свойство истинно, документ будет конвертирован с использованием потока формы xfa (если он существует). Если ложно, поток формы xfa будет игнорироваться. Это свойство было введено, потому что не ясно, как вычислить контрольную сумму, используемую для проверки подписи. |
| [set_UriResolver](./set_uriresolver/)(const System::SharedPtr\<Aspose::Foundation::UriResolver::UriResolver\>\&) | Устанавливает разрешитель URI. |
| [XfaParserOptions](./xfaparseroptions/)(System::Drawing::SizeF) | Инициализирует новый экземпляр класса [XfaParserOptions](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::XfaConverter](../)
* Library [Aspose.PDF for C++](../../)
