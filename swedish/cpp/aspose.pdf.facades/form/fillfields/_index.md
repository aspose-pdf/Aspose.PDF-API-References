---
title: "Aspose::Pdf::Facades::Form::FillFields metod"
linktitle: "FillFields"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::Form::FillFields metod. Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Obs: Endast tillämpas på Text Box. Både fältens namn och värden är skiftlägeskänsliga i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.facades/form/fillfields/
---
## Form::FillFields method


Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Obs: Endast tillämpas på [Text](../../../aspose.pdf.text/) Box. Både fältens namn och värden är skiftlägeskänsliga.

```cpp
bool Aspose::Pdf::Facades::Form::FillFields(const System::ArrayPtr<System::String> &fieldNames, const System::ArrayPtr<System::String> &fieldValues, System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldNames | const System::ArrayPtr\<System::String\>\& | Namnen på fälten. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | Nya värden för fälten. |
| output | System::SharedPtr\<System::IO::Stream\>\& | Ström där dokumentet kommer att sparas. |

### ReturnValue

true om fälten hittades och fylldes framgångsrikt.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
