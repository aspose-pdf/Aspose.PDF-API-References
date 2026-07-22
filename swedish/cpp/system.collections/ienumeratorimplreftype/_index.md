---
title: "System::Collections::IEnumeratorImplRefType-klass"
linktitle: "IEnumeratorImplRefType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::IEnumeratorImplRefType-klass. Omslag som skapar icke-generisk IEnumerator-implementation över den generiska Iteratorn IEnumeratorImplRefType – omslag för referenstyper i C++."
type: docs
weight: 700
url: /sv/cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Omslag som skapar icke-generisk [IEnumerator](../ienumerator/)-implementation över den generiska Iteratorn [IEnumeratorImplRefType](./) – omslag för referenstyper.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Current](./get_current/)() const override | Hämtar aktuellt element. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | wrapper konstruktor |
| [MoveNext](./movenext/)() override | Flyttar enumerator till nästa element. Om inget element har refererats tidigare, sätts referensen till det första tillgängliga elementet. Om behållarens slut har nåtts, görs inget. |

## Se även

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
