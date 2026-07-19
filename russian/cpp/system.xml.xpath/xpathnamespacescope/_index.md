---
title: "Перечисление System::Xml::XPath::XPathNamespaceScope"
linktitle: "XPathNamespaceScope"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Xml::XPath::XPathNamespaceScope. Определяет область видимости пространств имён в C++."
type: docs
weight: 1000
url: /ru/cpp/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum


Определяет область действия пространства имён.

```cpp
enum class XPathNamespaceScope
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Все | 0 | Возвращает все пространства имён, определённые в области текущего узла. Это включает пространство **xmlns:xml**, которое всегда объявляется неявно. Порядок возвращаемых пространств имён не определён. |
| ExcludeXml | 1 | Возвращает все пространства имён, определённые в области текущего узла, за исключением пространства **xmlns:xml**. Пространство **xmlns:xml** всегда объявляется неявно. Порядок возвращаемых пространств имён не определён. |
| Локальный | 2 | Возвращает все пространства имён, определённые локально в текущем узле. |

## См. также

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
