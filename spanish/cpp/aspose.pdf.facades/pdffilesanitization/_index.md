---
title: "Aspose::Pdf::Facades::PdfFileSanitization clase"
linktitle: "PdfFileSanitization"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSanitization clase. Representa la API de sanitización y recuperación. Úsela si no puedes crear/abrir documentos de otra manera en C++."
type: docs
weight: 2300
url: /es/cpp/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class


Representa la API de sanitización y recuperación. Úsela si no puede crear/abrir documentos de otra manera.

```cpp
class PdfFileSanitization : public Aspose::Pdf::Facades::SaveableFacade,
                            public Aspose::Pdf::Sanitization::IRecovery
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Vincula un archivo [Pdf](../../aspose.pdf/) para sanitizar. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula un flujo [Pdf](../../aspose.pdf/) para sanitizar. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Inicializa la fachada. |
| [Close](./close/)() override | Cierra la fachada. |
| [get_Log](./get_log/)() override | Después de que el archivo se haya guardado, puedes comprobar qué se hizo con el archivo. |
| [get_UseRebuildXrefAndTrailer](./get_userebuildxrefandtrailer/)() const | Permite generar un nuevo xref y trailer para el documento. |
| [get_UseTrimBottom](./get_usetrimbottom/)() const | Permite eliminar datos después de los datos del pdf. |
| [get_UseTrimTop](./get_usetrimtop/)() const | Permite eliminar datos antes de los datos del pdf. |
| [PdfFileSanitization](./pdffilesanitization/)() | Inicializa una nueva instancia. |
| [RebuildXrefAndTrailer](./rebuildxrefandtrailer/)() | Elimina el xref antiguo con trailer y crea un nuevo xref con trailer. |
| [Recover](./recover/)() override | Recupera el documento. Utiliza propiedades para personalizar. |
| [Save](./save/)(System::String) override | Guarda el PDF resultante en un archivo. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el PDF resultante en un flujo. |
| [set_UseRebuildXrefAndTrailer](./set_userebuildxrefandtrailer/)(bool) | Permite generar un nuevo xref y trailer para el documento. |
| [set_UseTrimBottom](./set_usetrimbottom/)(bool) | Permite eliminar datos después de los datos del pdf. |
| [set_UseTrimTop](./set_usetrimtop/)(bool) | Permite eliminar datos antes de los datos del pdf. |
| [TrimBottom](./trimbottom/)() override | Elimina datos después del último %EOF. |
| [TrimTop](./trimtop/)() override | Elimina datos antes del PDF. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Class [IRecovery](../../aspose.pdf.sanitization/irecovery/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
