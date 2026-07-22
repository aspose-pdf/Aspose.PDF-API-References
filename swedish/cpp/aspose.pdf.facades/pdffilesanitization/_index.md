---
title: "Aspose::Pdf::Facades::PdfFileSanitization-klass"
linktitle: "PdfFileSanitization"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSanitization class. Representerar sanerings- och återställnings-API. Använd den om du inte kan skapa/öppna dokument på något annat sätt i C++."
type: docs
weight: 2300
url: /sv/cpp/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class


Representerar sanerings- och återställnings-API. Använd den om du inte kan skapa/öppna dokument på annat sätt.

```cpp
class PdfFileSanitization : public Aspose::Pdf::Facades::SaveableFacade,
                            public Aspose::Pdf::Sanitization::IRecovery
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Kopplar en [Pdf](../../aspose.pdf/) fil för sanering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Kopplar en [Pdf](../../aspose.pdf/) ström för sanering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initierar fasaden. |
| [Close](./close/)() override | Stänger fasaden. |
| [get_Log](./get_log/)() override | Efter att filen har sparats kan du kontrollera vad som gjordes med filen. |
| [get_UseRebuildXrefAndTrailer](./get_userebuildxrefandtrailer/)() const | Tillåter att generera ny xref och trailer för dokumentet. |
| [get_UseTrimBottom](./get_usetrimbottom/)() const | Tillåter att ta bort data efter pdf-data. |
| [get_UseTrimTop](./get_usetrimtop/)() const | Tillåter att ta bort data före pdf-data. |
| [PdfFileSanitization](./pdffilesanitization/)() | Initierar en ny instans. |
| [RebuildXrefAndTrailer](./rebuildxrefandtrailer/)() | Tar bort gammal xref med trailer och skapar en ny xref med trailer. |
| [Recover](./recover/)() override | Återställer dokumentet. Använd egenskaper för att anpassa. |
| [Save](./save/)(System::String) override | Sparar den resulterande PDF-filen till en fil. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar den resulterande PDF-filen till en ström. |
| [set_UseRebuildXrefAndTrailer](./set_userebuildxrefandtrailer/)(bool) | Tillåter att generera ny xref och trailer för dokumentet. |
| [set_UseTrimBottom](./set_usetrimbottom/)(bool) | Tillåter att ta bort data efter pdf-data. |
| [set_UseTrimTop](./set_usetrimtop/)(bool) | Tillåter att ta bort data före pdf-data. |
| [TrimBottom](./trimbottom/)() override | Tar bort data efter sista %EOF. |
| [TrimTop](./trimtop/)() override | Tar bort data före PDF. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Class [IRecovery](../../aspose.pdf.sanitization/irecovery/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
