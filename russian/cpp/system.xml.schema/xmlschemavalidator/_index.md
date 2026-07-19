---
title: "System::Xml::Schema::XmlSchemaValidator class"
linktitle: "XmlSchemaValidator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaValidator class. Представляет движок проверки схемы XML Schema Definition Language (XSD). Класс XmlSchemaValidator не может быть унаследован в C++."
type: docs
weight: 7000
url: /ru/cpp/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator class


Представляет движок проверки XML [Schema](../) Definition Language (XSD) [Schema](../). Класс [XmlSchemaValidator](./) не может быть унаследован.

```cpp
class XmlSchemaValidator : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddSchema](./addschema/)(const SharedPtr\<XmlSchema\>\&) | Добавляет XML [Schema](../) Definition Language (XSD) схему в набор схем, используемых для проверки. |
| [EndValidation](./endvalidation/)() | Завершает проверку и проверяет ограничения идентичности для всего XML‑документа. |
| [get_LineInfoProvider](./get_lineinfoprovider/)() | Возвращает информацию о номере строки для проверяемого XML‑узла. |
| [get_SourceUri](./get_sourceuri/)() | Возвращает исходный URI для проверяемого XML‑узла. |
| [get_ValidationEventSender](./get_validationeventsender/)() | Возвращает объект, переданный в качестве отправителя события проверки. |
| [GetExpectedAttributes](./getexpectedattributes/)() | Возвращает ожидаемые атрибуты для текущего контекста элемента. |
| [GetExpectedParticles](./getexpectedparticles/)() | Возвращает ожидаемые частицы в текущем контексте элемента. |
| [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) | Проверяет ограничения идентичности на атрибутах по умолчанию и заполняет указанный List объектами [XmlSchemaAttribute](../xmlschemaattribute/) для всех атрибутов с значениями по умолчанию, которые ранее не были проверены с помощью метода [XmlSchemaValidator::ValidateAttribute](./validateattribute/) в контексте элемента. |
| [Initialize](./initialize/)() | Инициализирует состояние объекта [XmlSchemaValidator](./). |
| [Initialize](./initialize/)(const SharedPtr\<XmlSchemaObject\>\&) | Инициализирует состояние объекта [XmlSchemaValidator](./), используя указанный [XmlSchemaObject](../xmlschemaobject/) для частичной проверки. |
| [set_LineInfoProvider](./set_lineinfoprovider/)(const SharedPtr\<IXmlLineInfo\>\&) | Устанавливает информацию о номере строки для проверяемого XML‑узла. |
| [set_SourceUri](./set_sourceuri/)(const SharedPtr\<Uri\>\&) | Устанавливает исходный URI для проверяемого XML‑узла. |
| [set_ValidationEventSender](./set_validationeventsender/)(const SharedPtr\<Object\>\&) | Устанавливает объект, отправляемый в качестве отправителя события проверки. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Устанавливает объект [XmlResolver](../../system.xml/xmlresolver/), используемый для разрешения элементов **xs:import** и **xs:include**, а также атрибутов **xsi:schemaLocation** и **xsi:noNamespaceSchemaLocation**. |
| [SkipToEndElement](./skiptoendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Пропускает проверку содержимого текущего элемента и подготавливает объект [XmlSchemaValidator](./) для проверки содержимого в контексте родительского элемента. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Проверяет имя атрибута, URI пространства имён и значение в контексте текущего элемента. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) | Проверяет имя атрибута, URI пространства имён и значение в контексте текущего элемента. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Проверяет элемент в текущем контексте. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) | Проверяет элемент в текущем контексте с указанными значениями атрибутов **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** и **xsi:NoNamespaceSchemaLocation**. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Проверяет, является ли текстовое содержимое элемента допустимым в соответствии с его типом данных для элементов с простым содержимым, и проверяет, завершено ли содержимое текущего элемента для элементов со сложным содержимым. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) | Проверяет, является ли текстовое содержимое указанного элемента допустимым в соответствии с его типом данных. |
| [ValidateEndOfAttributes](./validateendofattributes/)(const SharedPtr\<XmlSchemaInfo\>\&) | Проверяет, присутствуют ли все обязательные атрибуты в контексте элемента, и подготавливает объект [XmlSchemaValidator](./) для проверки дочернего содержимого элемента. |
| [ValidateText](./validatetext/)(const String\&) | Проверяет, разрешена ли указанная текстовая **string** в контексте текущего элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое. |
| [ValidateText](./validatetext/)(XmlValueGetter) | Проверяет, разрешён ли текст, возвращаемый указанным объектом [XmlValueGetter](../xmlvaluegetter/), в контексте текущего элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое. |
| [ValidateWhitespace](./validatewhitespace/)(const String\&) | Проверяет, разрешены ли пробелы в указанной **string**, в контексте текущего элемента, и собирает пробелы для проверки, если текущий элемент имеет простое содержимое. |
| [ValidateWhitespace](./validatewhitespace/)(XmlValueGetter) | Проверяет, разрешены ли пробелы, возвращаемые указанным объектом [XmlValueGetter](../xmlvaluegetter/), в контексте текущего элемента, и собирает пробелы для проверки, если текущий элемент имеет простое содержимое. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) | Инициализирует новый экземпляр класса [XmlSchemaValidator](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
