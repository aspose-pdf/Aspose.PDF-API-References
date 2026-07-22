---
title: "Aspose::Pdf::Forms::XFA::idx_get metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::XFA::idx_get metod. Hämtar eller sätter datanodens värde enligt sökväg i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf.forms/xfa/idx_get/
---
## XFA::idx_get method


Hämtar eller sätter värdet på datanoden enligt *path*.

```cpp
System::String Aspose::Pdf::Forms::XFA::idx_get(const System::String &path)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökväg till datanoden, t.ex. form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Se till att inkludera index även om data bara innehåller ett enda förekomst av varje nod, d.v.s. skriv node1[0].node2[0]... istället för node1.node2... |

### ReturnValue

Värde för datanod.

## Se även

* Class [String](../../../system/string/)
* Class [XFA](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
