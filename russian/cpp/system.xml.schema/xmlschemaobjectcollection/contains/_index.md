---
title: "System::Xml::Schema::XmlSchemaObjectCollection::Contains метод"
linktitle: "Contains"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaObjectCollection::Contains метод. Указывает, находится ли указанный XmlSchemaObject в XmlSchemaObjectCollection в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains method


Указывает, находится ли указанный [XmlSchemaObject](../../xmlschemaobject/) в [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const SharedPtr\<XmlSchemaObject\>\& | Элемент [XmlSchemaObject](../../xmlschemaobject/). |

### ReturnValue

**true** if the specified qualified name is in the collection; otherwise, returns **false**. If **nullptr** is supplied, **false** is returned because there is no qualified name with a null name.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
