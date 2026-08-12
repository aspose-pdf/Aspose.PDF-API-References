---
title: "System::Xml::XmlTextReader::GetNamespacesInScope метод"
linktitle: "GetNamespacesInScope"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlTextReader::GetNamespacesInScope метод. Возвращает коллекцию, содержащую все пространства имён, находящиеся в текущей области видимости, в C++."
type: docs
weight: 3400
url: /ru/cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope method


Возвращает коллекцию, содержащую все текущие области видимости пространств имён.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | XmlNamespaceScope | Значение [XmlNamespaceScope](../../xmlnamespacescope/), которое указывает тип возвращаемых узлов пространства имён. |

### ReturnValue

Объект IDictionary, содержащий все текущие пространства имён в области видимости. Если считыватель не находится на элементе, возвращается пустой словарь (без пространств имён).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
