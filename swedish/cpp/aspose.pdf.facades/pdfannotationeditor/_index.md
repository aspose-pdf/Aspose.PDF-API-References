---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor klass"
linktitle: "PdfAnnotationEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor klass. Representerar en klass för arbete med PDF-dokumentanteckningar (kommentarer) i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class


Representerar en klass för arbete med PDF-dokumentanteckningar (kommentarer).

```cpp
class PdfAnnotationEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DeleteAnnotation](./deleteannotation/)(const System::String\&) | Tar bort anteckningen med angivet anteckningsnamn. |
| [DeleteAnnotations](./deleteannotations/)() | Tar bort alla anteckningar i dokumentet. |
| [DeleteAnnotations](./deleteannotations/)(const System::String\&) | Tar bort alla anteckningar av den angivna typen i dokumentet. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporterar anteckningar till ström. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Exporterar innehållet för de angivna anteckningstyperna till XFDF. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Exporterar innehållet för de angivna anteckningstyperna till XFDF. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Hämtar listan över anteckningar av de angivna typerna. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Hämtar listan över anteckningar av de angivna typerna. |
| [FlatteningAnnotations](./flatteningannotations/)() | Plattar till alla anteckningar i dokumentet. |
| [FlatteningAnnotations](./flatteningannotations/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Plattar till alla anteckningar i dokumentet. |
| [FlatteningAnnotations](./flatteningannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Plattar till anteckningarna av de angivna typerna. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&) | Importerar alla anteckningar från XFDF‑fil. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importerar de angivna anteckningarna från XFDF‑fil. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importerar de angivna anteckningarna från XFDF‑datastream. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar alla anteckningar från XFDF‑datastream. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF‑dokument. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&) | Importerar anteckningar till dokumentet från en matris av andra PDF‑dokument. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF‑dokumentströmmar. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Importerar anteckningar till dokumentet från en matris av andra PDF‑dokumentströmmar. |
| [ImportAnnotationsFromFdf](./importannotationsfromfdf/)(const System::String\&) | Importerar alla anteckningar från FDF‑fil. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Importerar alla anteckningar från XFDF‑fil. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar alla anteckningar från XFDF‑datastream. |
| [ModifyAnnotations](./modifyannotations/)(int32_t, int32_t, const System::SharedPtr\<Annotations::Annotation\>\&) | Modifierar annoteringarna av den angivna typen på det angivna sidintervallet. Den stöder att modifiera följande annoteringsegenskaper: Modified, Title, Contents, [Color](../../aspose.pdf/color/), Subject och Open. |
| [ModifyAnnotationsAuthor](./modifyannotationsauthor/)(int32_t, int32_t, const System::String\&, const System::String\&) | Modifierar författaren till annoteringar på det angivna sidintervallet. |
| [PdfAnnotationEditor](./pdfannotationeditor/)() | Initierar ett nytt [PdfAnnotationEditor](./) objekt. |
| [PdfAnnotationEditor](./pdfannotationeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfAnnotationEditor](./) objekt baserat på *document*. |
| [RedactArea](./redactarea/)(int32_t, System::SharedPtr\<Rectangle\>, System::Drawing::Color) | Raderar område på den angivna sidan. Allt innehåll tas bort. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
