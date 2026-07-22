---
title: "Aspose::Pdf::CollectionSort klass"
linktitle: "CollectionSort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionSort klass. Representerar en klass för en samlingssorteringsdefinition i C++."
type: docs
weight: 2700
url: /sv/cpp/aspose.pdf/collectionsort/
---
## CollectionSort class


Representerar en klass för en sorteringsdefinition av en samling.

```cpp
class CollectionSort : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CollectionSort](./collectionsort/)() | Skapar en instans av samlingssorteringsklassen. |
| [CollectionSort](./collectionsort/)(const System::SharedPtr\<Engine::Data::IPdfDictionary\>\&) | Skapar en instans av samlingssorteringsklassen. |
| [get_A](./get_a/)() const | Hämtar sorteringsordningsvärdet. Om värdet är en boolesk typ anger det om den interaktiva PDF-processorn ska sortera objekten i samlingen i stigande ordning (true) eller fallande ordning (false). Om värdet är en array ska varje element i arrayen vara ett booleskt värde som anger om posten på samma index i S‑arrayen ska sorteras i stigande eller fallande ordning. Om antalet poster i A‑arrayen är större än antalet poster i S‑arrayen ska de extra posterna i A‑arrayen ignoreras. Om antalet poster i A‑arrayen är mindre än antalet poster i S‑arrayen ska de saknade posterna i A‑arrayen antas vara true. Standardvärde: **true** |
| [get_S](./get_s/)() const | Hämtar namn eller namn på fält som den interaktiva PDF-processorn ska använda för att sortera objekten i samlingen. Om värdet är ett namn identifierar det ett fält som beskrivs i den överordnade samlingsordboken. Om värdet är en array ska varje element i arrayen vara ett namn som identifierar ett fält som beskrivs i den överordnade samlingsordboken. Arrayformen ska användas för att låta ytterligare fält bidra till sorteringen, där varje extra fält används för att bryta lika resultat. Mer specifikt, om flera samlingsobjektsordböcker har samma värde för det första fältet som anges i arrayen, ska värdena för efterföljande fält som anges i arrayen användas för sortering, tills en unik ordning har fastställts eller tills de namngivna fälten är uttömda. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
