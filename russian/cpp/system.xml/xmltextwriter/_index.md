---
title: "Класс System::Xml::XmlTextWriter"
linktitle: "XmlTextWriter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlTextWriter. Представляет запись, обеспечивающую быстрый, некешированный, однонаправленный способ создания потоков или файлов, содержащих XML‑данные, соответствующие рекомендациям W3C Extensible Markup Language (XML) 1.0 и Namespaces in XML в C++."
type: docs
weight: 4000
url: /ru/cpp/system.xml/xmltextwriter/
---
## XmlTextWriter class


Представляет писатель, обеспечивающий быстрый, некешированный последовательный способ создания потоков или файлов, содержащих XML‑данные, соответствующие рекомендациям W3C Extensible Markup Language (XML) 1.0 и Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает этот поток и базовый поток. |
| [Flush](./flush/)() override | Сбрасывает всё, что находится в буфере, в базовые потоки, а также сбрасывает базовый поток. |
| [get_BaseStream](./get_basestream/)() | Возвращает объект базового потока. |
| [get_Formatting](./get_formatting/)() | Указывает, как форматируется вывод. |
| [get_Indentation](./get_indentation/)() | Возвращает количество символов отступа (IndentChars), которые записываются для каждого уровня иерархии, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| [get_IndentChar](./get_indentchar/)() | Возвращает, какой символ использовать для отступов, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| [get_Namespaces](./get_namespaces/)() | Возвращает значение, указывающее, следует ли поддерживать пространства имён. |
| [get_QuoteChar](./get_quotechar/)() | Возвращает, какой символ использовать для заключения значений атрибутов в кавычки. |
| [get_WriteState](./get_writestate/)() override | Возвращает состояние записывателя. |
| [get_XmlLang](./get_xmllang/)() override | Возвращает текущую область **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Возвращает объект [XmlSpace](../xmlspace/), представляющий текущую область **xml:space**. |
| [LookupPrefix](./lookupprefix/)(String) override | Возвращает ближайший префикс, определённый в текущей области пространства имён для указанного URI пространства имён. |
| [set_Formatting](./set_formatting/)(System::Xml::Formatting) | Указывает, как форматируется вывод. |
| [set_Indentation](./set_indentation/)(int32_t) | Устанавливает количество символов отступа (IndentChars), которые записываются для каждого уровня иерархии, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| [set_IndentChar](./set_indentchar/)(char16_t) | Устанавливает, какой символ использовать для отступов, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| [set_Namespaces](./set_namespaces/)(bool) | Устанавливает значение, указывающее, следует ли поддерживать пространства имён. |
| [set_QuoteChar](./set_quotechar/)(char16_t) | Устанавливает, какой символ использовать для заключения значений атрибутов в кавычки. |
| [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Кодирует указанные двоичные байты в base64 и записывает полученный текст. |
| [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Кодирует указанные двоичные байты в binhex и записывает полученный текст. |
| [WriteCData](./writecdata/)(String) override | Записывает блок **...**, содержащий указанный текст. |
| [WriteCharEntity](./writecharentity/)(char16_t) override | Принудительно генерирует символьную сущность для указанного значения Unicode‑символа. |
| [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Записывает текст по одному буферу за раз. |
| [WriteComment](./writecomment/)(String) override | Записывает комментарий ****, содержащий указанный текст. |
| [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) override | Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами. |
| [WriteEndAttribute](./writeendattribute/)() override | Закрывает предыдущий вызов [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| [WriteEndDocument](./writeenddocument/)() override | Закрывает любые открытые элементы или атрибуты и возвращает записыватель в состояние Start. |
| [WriteEndElement](./writeendelement/)() override | Закрывает один элемент и снимает соответствующую область пространства имён. |
| [WriteEntityRef](./writeentityref/)(const String\&) override | Записывает ссылку на сущность как **&name**;. |
| [WriteFullEndElement](./writefullendelement/)() override | Закрывает один элемент и снимает соответствующую область пространства имён. |
| [WriteName](./writename/)(const String\&) override | Записывает указанное имя, гарантируя, что оно является допустимым именем согласно [рекомендации W3C XML 1.0](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteNmToken](./writenmtoken/)(const String\&) override | Записывает указанное имя, гарантируя, что оно является допустимым **NmToken** согласно [рекомендации W3C XML 1.0](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) override | Записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**. |
| [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) override | Записывает имя, квалифицированное пространством имён. Этот метод ищет префикс, находящийся в области действия для данного пространства имён. |
| [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Записывает необработанную разметку вручную из буфера символов. |
| [WriteRaw](./writeraw/)(const String\&) override | Записывает необработанную разметку вручную из строки. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) override | Записывает начало атрибута. |
| [WriteStartDocument](./writestartdocument/)() override | Записывает объявление XML с версией "1.0". |
| [WriteStartDocument](./writestartdocument/)(bool) override | Записывает объявление XML с версией "1.0" и атрибутом standalone. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) override | Записывает указанный открывающий тег и связывает его с заданным пространством имён и префиксом. |
| [WriteString](./writestring/)(const String\&) override | Записывает предоставленное текстовое содержимое. |
| [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Генерирует и записывает сущность суррогатного символа для пары суррогатных символов. |
| [WriteWhitespace](./writewhitespace/)(String) override | Записывает указанные пробельные символы. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Создаёт экземпляр класса [XmlTextWriter](./), используя указанный поток и кодировку. |
| [XmlTextWriter](./xmltextwriter/)(const String\&, const SharedPtr\<Text::Encoding\>\&) | Создаёт экземпляр класса [XmlTextWriter](./), используя указанный файл. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::TextWriter\>\&) | Создаёт экземпляр класса [XmlTextWriter](./), используя указанный TextWriter. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Рекомендуется вместо этого использовать класс [XmlWriter](../xmlwriter/).

Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
