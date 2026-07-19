---
title: "Метод System::Xml::Schema::XmlSchemaCollection::Add"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Schema::XmlSchemaCollection::Add. Добавляет XmlSchema в коллекцию в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method


Добавляет [XmlSchema](../../xmlschema/) в коллекцию.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Экземпляр [XmlSchema](../../xmlschema/) для добавления в коллекцию. |

### ReturnValue

Объект [XmlSchema](../../xmlschema/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Добавляет [XmlSchema](../../xmlschema/) в коллекцию. Указанный [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения внешних ссылок.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Экземпляр [XmlSchema](../../xmlschema/) для добавления в коллекцию. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/), используемый для разрешения пространств имён, указанных в элементах **include** и **import**. Если это **nullptr**, внешние ссылки не разрешаются. |

### ReturnValue

[XmlSchema](../../xmlschema/), добавленный в коллекцию схем.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method


Добавляет все пространства имён, определённые в данной коллекции (включая связанные с ними схемы), в эту коллекцию.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchemaCollection\>\& | [XmlSchemaCollection](../), который вы хотите добавить в эту коллекцию. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaCollection](../)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method


Добавляет схему, содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в коллекцию схем.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const String\& | URI пространства имён, связанный со схемой. Для XML‑схем обычно используется **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий схему для добавления. |

### ReturnValue

[XmlSchema](../../xmlschema/), добавленный в коллекцию схем; **nullptr**, если добавляемая схема является XDR‑схемой или в схеме есть ошибки компиляции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Добавляет схему, содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в коллекцию схем. Указанный [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения внешних ресурсов.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const String\& | URI пространства имён, связанный со схемой. Для XML‑схем обычно используется **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий схему для добавления. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/), используемый для разрешения пространств имён, указанных в элементах **include** и **import** или атрибуте **x-schema** (XDR‑схемы). Если это **nullptr**, внешние ссылки не разрешаются. |

### ReturnValue

[XmlSchema](../../xmlschema/), добавленный в коллекцию схем; **nullptr**, если добавляемая схема является XDR‑схемой или в схеме есть ошибки компиляции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const String\&) method


Добавляет схему, расположенную по указанному URL, в коллекцию схем.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const String\& | URI пространства имён, связанный со схемой. Для XML‑схем обычно используется **targetNamespace**. |
| uri | const String\& | URL, указывающий схему для загрузки. |

### ReturnValue

[XmlSchema](../../xmlschema/), добавленный в коллекцию схем; **nullptr**, если добавляемая схема является XDR‑схемой или в схеме есть ошибки компиляции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
