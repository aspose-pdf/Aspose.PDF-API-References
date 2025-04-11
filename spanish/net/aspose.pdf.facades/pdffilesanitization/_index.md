---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileSanitization. Representa la API de sanitización y recuperación. Úsala si no puedes crear/abrir documentos de ninguna otra manera.
type: docs
weight: 4540
url: /es/net/aspose.pdf.facades/pdffilesanitization/
---
## Clase PdfFileSanitization

Representa la API de sanitización y recuperación. Úsala si no puedes crear/abrir documentos de ninguna otra manera.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene el documento en el que está trabajando la fachada. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Después de que el archivo ha sido guardado, puedes verificar qué se hizo con el archivo. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Permite generar un nuevo xref y trailer para el documento. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Permite eliminar datos después de los datos pdf. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Permite eliminar datos antes de los datos pdf. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Vincula un flujo Pdf para sanitizar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Vincula un archivo Pdf para sanitizar. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Cierra la fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Elimina el xref antiguo con trailer y crea un nuevo xref con trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Recupera el documento. Usa propiedades para personalizar. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Guarda el PDF resultante en el flujo. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Guarda el PDF resultante en un archivo. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Elimina datos después del último %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Elimina datos antes de %PDF. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)