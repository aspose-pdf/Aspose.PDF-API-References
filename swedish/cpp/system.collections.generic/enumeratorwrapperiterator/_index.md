---
title: "System::Collections::Generic::EnumeratorWrapperIterator klass"
linktitle: "EnumeratorWrapperIterator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::EnumeratorWrapperIterator klass. En iterator som omsluter den förhandsskapade enumeratorn och omdirigerar alla anrop till den i C++."
type: docs
weight: 1500
url: /sv/cpp/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator class


Iterator som omsluter den förhandsskapade enumeratorn och omdirigerar alla anrop till den.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


| Parameter | Beskrivning |
| --- | --- |
| Element | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const SharedPtr\<IEnumerator\<Element\>\>\&) |  |
| [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. Måste uppdatera m_is_end och m_pointer. |
| [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Kontrollerar om två iteratorer pekar på samma objekt. |
| virtual [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destruktor. |

## Se även

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
