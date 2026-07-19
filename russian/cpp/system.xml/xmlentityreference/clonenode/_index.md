---
title: "Метод System::Xml::XmlEntityReference::CloneNode"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlEntityReference::CloneNode. Создаёт дубликат этого узла в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode method


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** — рекурсивно клонировать поддерево под указанным узлом; **false** — клонировать только сам узел. Для узлов [XmlEntityReference](../) этот метод всегда возвращает узел ссылки на сущность без дочерних элементов. Текст замены устанавливается, когда узел вставляется в родитель. |

### ReturnValue

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
