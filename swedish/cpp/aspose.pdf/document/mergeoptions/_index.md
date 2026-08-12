---
title: "Aspose::Pdf::Document::MergeOptions klass"
linktitle: "MergeOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::MergeOptions klass. Representerar alternativen för Merge‑metoder i C++."
type: docs
weight: 12700
url: /sv/cpp/aspose.pdf/document/mergeoptions/
---
## MergeOptions class


Representerar alternativen för Merge‑metoder.

```cpp
class MergeOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ConcatenationPacketSize](./get_concatenationpacketsize/)() const | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. Standardvärdet är 4. |
| [get_IsNeedPageTreeBalance](./get_isneedpagetreebalance/)() const | Hämtar och anger kravet på balansering av sidträdet. Det hela sidträdet i det resulterande dokumentet kommer att balanseras om. Det skapar ett balanserat sidträd för att snabba upp åtkomst till sidor. |
| [get_MaximumNodesInLevel](./get_maximumnodesinlevel/)() const | Hämtar och anger maximalt antal noder på en nivå i sidträdet. Standard är 10. |
| [get_UseDiskBuffer](./get_usediskbuffer/)() const | Om detta alternativ används kommer destinationsdokumentet att sparas på disk periodiskt och ytterligare sammanslagning kommer att tillämpas på det som inkrementella uppdateringar. Standardvärdet är **false**. |
| [MergeOptions](./mergeoptions/)() |  |
| [set_ConcatenationPacketSize](./set_concatenationpacketsize/)(int32_t) | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. Standardvärdet är 4. |
| [set_IsNeedPageTreeBalance](./set_isneedpagetreebalance/)(bool) | Hämtar och anger kravet på balansering av sidträdet. Det hela sidträdet i det resulterande dokumentet kommer att balanseras om. Det skapar ett balanserat sidträd för att snabba upp åtkomst till sidor. |
| [set_MaximumNodesInLevel](./set_maximumnodesinlevel/)(uint8_t) | Hämtar och anger maximalt antal noder på en nivå i sidträdet. Standard är 10. |
| [set_UseDiskBuffer](./set_usediskbuffer/)(bool) | Om detta alternativ används kommer destinationsdokumentet att sparas på disk periodiskt och ytterligare sammanslagning kommer att tillämpas på det som inkrementella uppdateringar. Standardvärdet är **false**. |
## Se även

* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
