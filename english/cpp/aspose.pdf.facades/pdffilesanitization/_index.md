---
title: Aspose::Pdf::Facades::PdfFileSanitization class
linktitle: PdfFileSanitization
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSanitization class. Represents sanitization and recovery API. Use it if you can''t create/open documents in any other way in C++.'
type: docs
weight: 2300
url: /cpp/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class


Represents sanitization and recovery API. Use it if you can't create/open documents in any other way.

```cpp
class PdfFileSanitization : public Aspose::Pdf::Facades::SaveableFacade,
                            public Aspose::Pdf::Sanitization::IRecovery
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Binds a [Pdf](../../aspose.pdf/) file for Sanitize. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds a [Pdf](../../aspose.pdf/) stream for Sanitize. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initializes the facade. |
| [Close](./close/)() override | Closes the facade. |
| [get_Log](./get_log/)() override | After file has Saved you can check what was done with file. |
| [get_UseRebuildXrefAndTrailer](./get_userebuildxrefandtrailer/)() const | Allows to generate new xref and trailer for document. |
| [get_UseTrimBottom](./get_usetrimbottom/)() const | Allows to remove data after pdf data. |
| [get_UseTrimTop](./get_usetrimtop/)() const | Allows to remove data before pdf data. |
| [PdfFileSanitization](./pdffilesanitization/)() | Initializes a new instance. |
| [RebuildXrefAndTrailer](./rebuildxrefandtrailer/)() | Removes old xref with trailer and creates a new xref with trailer. |
| [Recover](./recover/)() override | Recovers document. Use properties to customize. |
| [Save](./save/)(System::String) override | Saves the result PDF to file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the result PDF to stream. |
| [set_UseRebuildXrefAndTrailer](./set_userebuildxrefandtrailer/)(bool) | Allows to generate new xref and trailer for document. |
| [set_UseTrimBottom](./set_usetrimbottom/)(bool) | Allows to remove data after pdf data. |
| [set_UseTrimTop](./set_usetrimtop/)(bool) | Allows to remove data before pdf data. |
| [TrimBottom](./trimbottom/)() override | Removes data after last %EOF. |
| [TrimTop](./trimtop/)() override | Removes data before PDF. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Class [IRecovery](../../aspose.pdf.sanitization/irecovery/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
