---
title: "System::Collections::Generic::operator== metod"
linktitle: "operator=="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::operator== metod. Jämför två nyckel‑värde‑par med hjälp av ''equals''‑semantik. Använder operator == eller EqualsTo‑metoden för både nycklar och värden, beroende på vad som är definierat i C++."
type: docs
weight: 5600
url: /sv/cpp/system.collections.generic/operator==/
---
## System::Collections::Generic::operator== method


Jämför två nyckel‑värde‑par med hjälp av 'equals'-semantik. Använder operator == eller EqualsTo‑metoden för både nycklar och värden, beroende på vad som är definierat.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | const KeyValuePair\<TKey, TValue\>\& | Vänster operand. |
| höger | const KeyValuePair\<TKey, TValue\>\& | Höger operand. |

### ReturnValue

Sant om både nycklar och värden matchar, falskt annars.

## Se även

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
