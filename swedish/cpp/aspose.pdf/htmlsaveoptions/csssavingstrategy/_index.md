---
title: "Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy typedef"
linktitle: "CssSavingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy typedef. Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparning av en del av CSS som skapades under konverteringen av PDF till HTML. I sådant fall måste bearbetning (t.ex. sparning till ström eller disk) göras i den anpassade koden i C++."
type: docs
weight: 4700
url: /sv/cpp/aspose.pdf/htmlsaveoptions/csssavingstrategy/
---
## CssSavingStrategy typedef


Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparande av en del av CSS som skapades under konvertering av PDF till HTML. I så fall måste bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden.

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy =  System::MulticastDelegate<void(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssSavingInfo>&)>
```


## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
