---
title: "System::Xml::XmlCDataSection::CloneNode метод"
linktitle: "CloneNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlCDataSection::CloneNode метод. Создаёт дубликат этого узла на C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode method


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | bool | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Поскольку узлы CDATA не имеют дочерних элементов, независимо от значения параметра, клонированный узел всегда будет включать содержимое данных. |

### ReturnValue

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
