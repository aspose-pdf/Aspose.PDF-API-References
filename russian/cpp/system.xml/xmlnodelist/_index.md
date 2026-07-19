---
title: "System::Xml::XmlNodeList класс"
linktitle: "XmlNodeList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeList класс. Представляет упорядоченную коллекцию узлов в C++."
type: docs
weight: 2700
url: /ru/cpp/system.xml/xmlnodelist/
---
## XmlNodeList class


Представляет упорядоченную коллекцию узлов.

```cpp
class XmlNodeList : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                    public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_Count](./get_count/)() | Возвращает количество узлов в [XmlNodeList](./). |
| virtual [GetEnumerator](./getenumerator/)() | Обеспечивает поддержку итерации по коллекции узлов в [XmlNodeList](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Возвращает узел по указанному индексу. |
| virtual [Item](./item/)(int32_t) | Получает узел по указанному индексу. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
