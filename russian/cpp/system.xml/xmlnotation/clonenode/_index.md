---
title: "Метод System::Xml::XmlNotation::CloneNode"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlNotation::CloneNode. Создаёт дубликат этого узла. Узлы Notation нельзя клонировать. Вызов этого метода для объекта XmlNotation вызывает исключение в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode method


Создает дубликат этого узла. Узлы нотации нельзя клонировать. Вызов этого метода для объекта [XmlNotation](../) приводит к выбросу исключения.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. |

### ReturnValue

Копия [XmlNode](../../xmlnode/) узла, из которого вызывается метод.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
