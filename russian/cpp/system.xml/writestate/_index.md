---
title: "System::Xml::WriteState enum"
linktitle: "WriteState"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::WriteState enum. Указывает состояние XmlWriter в C++."
type: docs
weight: 5700
url: /ru/cpp/system.xml/writestate/
---
## WriteState enum


Указывает состояние [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Start | 0 | Указывает, что метод XmlWriter::Write ещё не был вызван. |
| Преамбула | 1 | Указывает, что пролог записывается. |
| Элемент | 2 | Указывает, что записывается начальный тег элемента. |
| Атрибут | 3 | Указывает, что записывается значение атрибута. |
| Содержание | 4 | Указывает, что содержимое элемента записывается. |
| Closed | 5 | Указывает, что метод [XmlWriter::Close](../xmlwriter/close/) был вызван. |
| Error | 6 | Было выброшено исключение, которое оставило [XmlWriter](../xmlwriter/) в недопустимом состоянии. Вы можете вызвать метод [XmlWriter::Close](../xmlwriter/close/), чтобы перевести [XmlWriter](../xmlwriter/) в состояние [WriteState::Closed](./). Любые другие вызовы методов [XmlWriter](../xmlwriter/) приводят к InvalidOperationException. |

## См. также

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
