---
title: "Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef"
linktitle: "CssUrlMakingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef. Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML‑dokumentet. T.ex. om du vill att CSS‑referensen i HTML ska vara \"otherPage.ASPX?CssID=zjjkklj\" måste en sådan anpassad strategi returnera \"otherPage.ASPX?CssID=zjjkklj\" i C++."
type: docs
weight: 4800
url: /sv/cpp/aspose.pdf/htmlsaveoptions/cssurlmakingstrategy/
---
## CssUrlMakingStrategy typedef


Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML‑dokumentet. T.ex. om du vill att CSS refereras i HTML t.ex. som "otherPage.ASPX?CssID=zjjkklj" måste en sådan anpassad strategi returnera "otherPage.ASPX?CssID=zjjkklj".

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssUrlRequestInfo>&)>
```


## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
