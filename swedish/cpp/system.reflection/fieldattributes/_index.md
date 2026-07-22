---
title: "System::Reflection::FieldAttributes enum"
linktitle: "FieldAttributes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::FieldAttributes enum. Reflekterade fältattribut i C++."
type: docs
weight: 1200
url: /sv/cpp/system.reflection/fieldattributes/
---
## FieldAttributes enum


Reflekterade fältattribut.

```cpp
enum class FieldAttributes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| FieldAccessMask | 7 | Medlemsåtkomstmask. Använd denna mask för att hämta åtkomstinformation. |
| PrivateScope | 0 | Icke-refererbara medlemmar. |
| Privat | 1 | Privata medlemmar. |
| FamANDAssem | 2 | Privata och assembly-avgränsade medlemmar. |
| Assembly | 3 | Assembly-avgränsade medlemmar. |
| Family | 4 | Medlemmar som är åtkomliga av typ och subtyper. |
| FamORAssem | 5 | Medlemmar som är åtkomliga av typ, subtyper och assembly. |
| Publik | 6 | Medlemmar som är åtkomliga för alla. |
| Statisk | 16 | Statisk medlemmar som motsats till instansmedlemmar. |
| InitOnly | 32 | Const-medlemmar som bara kan initieras men inte ändras. |
| Literal | 64 | Konstanta medlemmar vid kompileringstid. |
| NotSerialized | 128 | Ej serialiserade medlemmar. |
| SpecialName | 512 | Speciellt fält av ett av nedanstående namn. |
| PinvokeImpl | 8192 | Interop vidarebefordrad implementation. |
| ReservedMask | 38144 | Reserverade flaggor endast för körningstid. |
| RTSpecialName | 1024 | Runtim bör kontrollera namnkodning. |
| HasFieldMarshal | 4096 | Marshalingsinformation finns. |
| HasDefault | 32768 | Standardvärde finns. |
| HasFieldRVA | 256 | RVA finns. |

## Se även

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
