---
title: "Класс System::Security::SecurityElement"
linktitle: "SecurityElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::SecurityElement. XML-модель объекта для кодирования объекта безопасности. Не реализовано. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.security/securityelement/
---
## SecurityElement class


XML-модель объекта для кодирования объекта безопасности. Не реализовано. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SecurityElement : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Добавляет атрибут к тегу. |
| [AddChild](./addchild/)(SecurityElement) | Добавляет дочерний тег. |
| [Attribute](./attribute/)(const String\&) | Возвращает значение атрибута. |
| [Copy](./copy/)() | Клонирует тег. |
| [Equal](./equal/)(SecurityElement) | Проверяет равенство параметров. |
| static [Escape](./escape/)(const String\&) | Экранирует символы в XML-строке. |
| static [FromString](./fromstring/)(const String\&) | Создаёт элемент из XML-кода. |
| [get_Attributes](./get_attributes/)() | Возвращает атрибуты тега. |
| [get_Children](./get_children/)() | Получает дочерние объекты тега. |
| [get_Tag](./get_tag/)() | Получает имя тега. |
| [get_Text](./get_text/)() | Получает внутренний текст тега. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Проверяет, является ли имя атрибута допустимым. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Проверяет, является ли значение атрибута допустимым. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Проверяет, является ли тег допустимым. |
| static [IsValidText](./isvalidtext/)(const String\&) | Проверяет, является ли текст допустимым. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | Получает дочерний тег по имени. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Получает внутренний текст дочернего тега по имени тега. |
| [SecurityElement](./securityelement/)(const String\&) | Конструктор. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Конструктор. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Устанавливает атрибуты тега. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Устанавливает дочерние объекты тега. |
| [set_Tag](./set_tag/)(const String\&) | Устанавливает имя тега. |
| [set_Text](./set_text/)(const String\&) | Устанавливает внутренний текст тега. |
| [ToString](./tostring/)() const override | Преобразует тег в строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
