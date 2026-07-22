---
title: "Aspose::Pdf::XImage::TrySetAlternativeText metod"
linktitle: "TrySetAlternativeText"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XImage::TrySetAlternativeText metod. Anger alternativ text för en XImage på sidan i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf/ximage/trysetalternativetext/
---
## XImage::TrySetAlternativeText method


Anger alternativ text för en [XImage](../) på sidan.

```cpp
bool Aspose::Pdf::XImage::TrySetAlternativeText(const System::String &alternativeText, const System::SharedPtr<Aspose::Pdf::Page> &page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativeText | const System::String\& | Den alternativa texten som ska specificeras. |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | [Page](../../page/) där [XImage](../) är placerad. |

### ReturnValue

Sant om alternativeText för [XImage](../) är angivet. Falskt om alternativeText för [XImage](../) inte är angivet.
## Anmärkningar



Metoden returnerar falskt i följande fall:* [XImage](../) hittas inte på den angivna sidan.
* The [XImage](../) appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.


## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [XImage](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
