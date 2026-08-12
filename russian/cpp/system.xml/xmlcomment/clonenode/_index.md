---
title: "System::Xml::XmlComment::CloneNode метод"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlComment::CloneNode метод. Создаёт дубликат этого узла в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode method


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** рекурсивно клонировать поддерево под указанным узлом; **false** клонировать только сам узел. Поскольку узлы комментариев не имеют дочерних элементов, клонированный узел всегда включает текстовое содержимое, независимо от настройки параметра. |

### ReturnValue

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlComment](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
