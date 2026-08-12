---
title: "Aspose::Pdf::LowCode::PdfAConverter::Process metod"
linktitle: "Process"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfAConverter::Process metod. Påbörjar en PDF/A‑konverterings‑ eller valideringsprocess med angivna alternativ i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.lowcode/pdfaconverter/process/
---
## PdfAConverter::Process method


Påbörjar en PDF/A-konverterings- eller valideringsprocess med angivna alternativ.

```cpp
System::SharedPtr<ResultContainer> Aspose::Pdf::LowCode::PdfAConverter::Process(System::SharedPtr<IPluginOptions> options) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | System::SharedPtr\<IPluginOptions\> | Ett alternativobjekt som innehåller instruktioner för plugin‑et. Måste vara en instans av klassen [PdfAConvertOptions](../../pdfaconvertoptions/) eller [PdfAValidateOptions](../../pdfavalidateoptions/) klass. |

### ReturnValue

Ett [ResultContainer](../../resultcontainer/)‑objekt som innehåller resultatet av bearbetningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ResultContainer](../../resultcontainer/)
* Class [IPluginOptions](../../ipluginoptions/)
* Class [PdfAConverter](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
