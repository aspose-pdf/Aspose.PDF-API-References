---
title: "System::Decimal::Round metod"
linktitle: "Round"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Decimal::Round metod. Avrundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal i C++."
type: docs
weight: 4400
url: /sv/cpp/system/decimal/round/
---
## Decimal::Round(const Decimal\&, int, MidpointRounding) method


Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const Decimal\& | Värdet att avrunda |
| decimaler | int | Antalet decimaler i det avrundade värdet |
| läge | MidpointRounding | Anger hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### ReturnValue

Numret med det angivna antalet siffror närmast **value**

## Se även

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Round(const Decimal\&, MidpointRounding) method


Avrundar det angivna värdet till närmaste heltal. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const Decimal\& | Värdet att avrunda |
| läge | MidpointRounding | Anger hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### ReturnValue

**d** rounded to the nearest integral value

## Se även

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
