---
title: "System::Globalization::TextInfo class"
linktitle: "TextInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::TextInfo class. Определяет свойства текста, специфичные для локали. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2800
url: /ru/cpp/system.globalization/textinfo/
---
## TextInfo class


Определяет свойства текста, специфичные для локали. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TextInfo : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Информация RTTI. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_ANSICodePage](./get_ansicodepage/)() const | Получает ANSI-кодовую страницу. |
| [get_CultureName](./get_culturename/)() const | Получает название культуры. |
| virtual [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | Получает кодовую страницу EBCDIC. |
| [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли формат только для чтения. |
| [get_IsRightToLeft](./get_isrighttoleft/)() const | Проверяет, написан ли текст слева направо. |
| [get_LCID](./get_lcid/)() const | Получает идентификатор локали. |
| virtual [get_ListSeparator](./get_listseparator/)() const | Получает разделитель списка. |
| virtual [get_MacCodePage](./get_maccodepage/)() const | Получает кодовую страницу Macintosh. |
| virtual [get_OEMCodePage](./get_oemcodepage/)() const | Получает кодовую страницу OEM. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [operator=](./operator=/)(const TextInfo\&) |  |
| static [ReadOnly](./readonly/)(const TextInfoPtr\&) | Получает только читаемую версию культуры. |
| virtual [set_ListSeparator](./set_listseparator/)(String) | Устанавливает разделитель списка. |
| [TextInfo](./textinfo/)(const TextInfo\&) | Информация RTTI. |
| virtual [ToLower](./tolower/)(char_t) const | Преобразует символ в нижний регистр. |
| virtual [ToLower](./tolower/)(String) const | Преобразует строку в нижний регистр. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [ToTitleCase](./totitlecase/)(String) const | Преобразует строку в регистр заголовка (за исключением аббревиатур, уже записанных заглавными буквами). |
| virtual [ToUpper](./toupper/)(char_t) const | Преобразует символ в верхний регистр. |
| virtual [ToUpper](./toupper/)(String) const | Преобразует строку в верхний регистр. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
