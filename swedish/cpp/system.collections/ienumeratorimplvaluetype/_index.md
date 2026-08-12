---
title: "System::Collections::IEnumeratorImplValueType klass"
linktitle: "IEnumeratorImplValueType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::IEnumeratorImplValueType klass. Wrapper som skapar icke‑generisk IEnumerator‑implementation över den generiska Iterator IEnumeratorImplRefType – omslag för värdetyper i C++."
type: docs
weight: 800
url: /sv/cpp/system.collections/ienumeratorimplvaluetype/
---
## IEnumeratorImplValueType class


Wrapper som skapar icke‑generisk [IEnumerator](../ienumerator/) implementation över den generiska Iteratorn [IEnumeratorImplRefType](../ienumeratorimplreftype/) - omslag för värdetyper.

```cpp
template<typename T>class IEnumeratorImplValueType : public System::Collections::IEnumerator
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Current](./get_current/)() const override | Hämtar aktuellt element. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<T\>\>) | wrapper konstruktor |
| [MoveNext](./movenext/)() override | Flyttar enumerator till nästa element. Om inget element har refererats tidigare, sätts referensen till det första tillgängliga elementet. Om behållarens slut har nåtts, görs inget. |

## Se även

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
