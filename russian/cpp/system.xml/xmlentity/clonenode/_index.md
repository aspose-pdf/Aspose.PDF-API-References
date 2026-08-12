---
title: "System::Xml::XmlEntity::CloneNode метод"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlEntity::CloneNode метод. Создаёт дубликат этого узла. Узлы сущностей нельзя клонировать. Вызов этого метода для объекта XmlEntity генерирует исключение в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode method


Создаёт дубликат этого узла. Узлы сущностей нельзя клонировать. Вызов этого метода для объекта [XmlEntity](../) генерирует исключение.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. |

### ReturnValue

Копия [XmlNode](../../xmlnode/) из которого вызывается метод.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
