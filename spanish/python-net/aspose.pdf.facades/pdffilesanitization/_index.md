---
title: "PdfFileSanitization"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa la API de sanitización y recuperación.<br/>            Úsela si no puede crear/abrir documentos de ninguna otra manera."
type: docs
weight: 290
url: /es/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Representa la API de sanitización y recuperación.<br/>            Úsela si no puede crear/abrir documentos de ninguna otra manera.

El tipo PdfFileSanitization expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileSanitization() | Inicializa una nueva instancia de la clase PdfFileSanitization |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| log | Después de que el archivo se haya guardado, puedes comprobar qué se hizo con el archivo. |
| use_trim_top | Permite eliminar datos antes de los datos del PDF. |
| use_trim_bottom | Permite eliminar datos después de los datos del PDF |
| use_rebuild_xref_and_trailer | Permite generar un nuevo xref y trailer para el documento. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(input_file) | Vincula un archivo PDF para sanitizar. |
| bind_pdf(input_stream) | Vincula un flujo PDF para sanitizar. |
| bind_pdf(src_doc) | Inicializa la fachada. |
| save(output_file) | Guarda el PDF resultante en un archivo. |
| save(output_stream) | Guarda el PDF resultante en un flujo. |
| close() | Cierra la fachada. |
| recover() | Recupera el documento.<br/>            Usa propiedades para personalizar. |
| trim_top() | Elimina datos antes de %PDF. |
| trim_bottom() | Elimina datos después del último %%EOF. |
| rebuild_xref_and_trailer() | Elimina el xref antiguo con trailer y crea un nuevo xref con trailer. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

