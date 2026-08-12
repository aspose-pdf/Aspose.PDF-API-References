---
title: "Класс System::Xml::Schema::XmlSchemaSet"
linktitle: "XmlSchemaSet"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaSet. Содержит кэш схем языка определения XML Schema (XSD) в C++."
type: docs
weight: 5800
url: /ru/cpp/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet class


Содержит кэш схем языка определения XML [Schema](../) (XSD).

```cpp
class XmlSchemaSet : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(String, const String\&) | Добавляет схему XML [Schema](../) языка определения (XSD) по указанному URL в [XmlSchemaSet](./). |
| [Add](./add/)(String, const SharedPtr\<XmlReader\>\&) | Добавляет схему XML [Schema](../) языка определения (XSD), содержащуюся в [XmlReader](../../system.xml/xmlreader/), в [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchemaSet\>\&) | Добавляет все схемы XML [Schema](../) языка определения (XSD) из указанного [XmlSchemaSet](./) в [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Добавляет указанный [XmlSchema](../xmlschema/) в [XmlSchemaSet](./). |
| [Compile](./compile/)() | Компилирует схемы XML [Schema](../) языка определения (XSD), добавленные в [XmlSchemaSet](./), в одну логическую схему. |
| [Contains](./contains/)(String) | Указывает, находится ли схема XML [Schema](../) языка определения (XSD) с указанным URI целевого пространства имён в [XmlSchemaSet](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Указывает, находится ли указанный объект XML [Schema](../) языка определения (XSD) [XmlSchema](../xmlschema/) в [XmlSchemaSet](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Копирует все объекты [XmlSchema](../xmlschema/) из [XmlSchemaSet](./) в указанный массив, начиная с заданного индекса. |
| [get_CompilationSettings](./get_compilationsettings/)() | Возвращает [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) для [XmlSchemaSet](./). |
| [get_Count](./get_count/)() | Возвращает количество логических схем XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [get_GlobalAttributes](./get_globalattributes/)() | Возвращает все глобальные атрибуты во всех схемах XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [get_GlobalElements](./get_globalelements/)() | Возвращает все глобальные элементы во всех схемах XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [get_GlobalTypes](./get_globaltypes/)() | Возвращает все глобальные простые и сложные типы во всех схемах XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [get_IsCompiled](./get_iscompiled/)() | Возвращает значение, указывающее, были ли скомпилированы схемы XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [get_NameTable](./get_nametable/)() | Возвращает таблицу имён [XmlNameTable](../../system.xml/xmlnametable/) по умолчанию, используемую [XmlSchemaSet](./) при загрузке новых схем XML [Schema](../) языка определения (XSD). |
| [Remove](./remove/)(const SharedPtr\<XmlSchema\>\&) | Удаляет указанную схему XML [Schema](../) языка определения (XSD) из [XmlSchemaSet](./). |
| [RemoveRecursive](./removerecursive/)(const SharedPtr\<XmlSchema\>\&) | Удаляет указанную схему XML [Schema](../) языка определения (XSD) и все импортируемые ею схемы из [XmlSchemaSet](./). |
| [Reprocess](./reprocess/)(SharedPtr\<XmlSchema\>) | Повторно обрабатывает схему XML [Schema](../) языка определения (XSD), уже существующую в [XmlSchemaSet](./). |
| [Schemas](./schemas/)() | Возвращает коллекцию всех схем XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./). |
| [Schemas](./schemas/)(String) | Возвращает коллекцию всех схем XML [Schema](../) языка определения (XSD) в [XmlSchemaSet](./), принадлежащих указанному пространству имён. |
| [set_CompilationSettings](./set_compilationsettings/)(const SharedPtr\<XmlSchemaCompilationSettings\>\&) | Устанавливает [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) для [XmlSchemaSet](./). |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Устанавливает [XmlResolver](../../system.xml/xmlresolver/), используемый для разрешения пространств имён или местоположений, указанных в элементах include и import схемы. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Добавляет обработчик событий для получения информации об ошибках проверки схемы XML [Schema](../) языка определения (XSD). |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Удаляет обработчик событий для получения информации об ошибках проверки схемы XML [Schema](../) языка определения (XSD). |
| [XmlSchemaSet](./xmlschemaset/)() | Инициализирует новый экземпляр класса [XmlSchemaSet](./). |
| [XmlSchemaSet](./xmlschemaset/)(const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlSchemaSet](./) с указанным [XmlNameTable](../../system.xml/xmlnametable/). |
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
