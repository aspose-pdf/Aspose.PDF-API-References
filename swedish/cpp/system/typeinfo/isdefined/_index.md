---
title: "System::TypeInfo::IsDefined metod"
linktitle: "IsDefined"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TypeInfo::IsDefined metod. INTE IMPLEMENTERAD. Anger om ett eller flera attribut av den angivna typen eller dess avledda typer har tillämpats på detta medlem i C++."
type: docs
weight: 4400
url: /sv/cpp/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined method


INTE IMPLEMENTERAD. Indikerar om ett eller flera attribut av den angivna typen eller av dess avledda typer är tillämpade på detta medlem.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeType | const TypeInfo\& | Typen av anpassat attribut att söka efter. Söket inkluderar avledda typer. |
| inherit | bool | true för att söka i detta medlems arvskedja för att hitta attributen; annars false. Denna parameter ignoreras för egenskaper och händelser. |

### ReturnValue

true om ett eller flera instanser av attributeType eller någon av dess avledda typer har tillämpats på detta medlem; annars false.

## Se även

* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
