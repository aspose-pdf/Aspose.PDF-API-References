---
title: "System::Xml::XmlWhitespace::CloneNode метод"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWhitespace::CloneNode метод. Создаёт дубликат этого узла в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode method


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Для узлов пробельных символов клонированный узел всегда включает значение данных, независимо от настройки параметра. |

### ReturnValue

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
