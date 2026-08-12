---
title: "System::Drawing::Region::Equals method"
linktitle: "Equals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Region::Equals method. Avgör om den angivna regionen är identisk med regionen som representeras av det aktuella objektet på den angivna ritytan i C++."
type: docs
weight: 600
url: /sv/cpp/system.drawing/region/equals/
---
## Region::Equals method


Bestämmer om den angivna regionen är identisk med den region som representeras av det aktuella objektet på den angivna ritytan.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | const SharedPtr\<Region\>\& | Regionen att jämföra denna region med |
| g | const SharedPtr\<Graphics\>\& | En ritningsyta |

### ReturnValue

Sant om innanmätet av den angivna regionen är identiskt med innanmätet av regionen som representeras av det aktuella objektet när den transformation som är associerad med parametern **g** tillämpas; annars - falskt

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Class [Region](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
