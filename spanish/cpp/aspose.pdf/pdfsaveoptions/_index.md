---
title: "Clase Aspose::Pdf::PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::PdfSaveOptions. Opciones de guardado para exportar al formato Pdf en C++."
type: docs
weight: 15200
url: /es/cpp/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class


Opciones de guardado para exportar al formato [Pdf](../).

```cpp
class PdfSaveOptions : public Aspose::Pdf::SaveOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_DefaultFontName](./get_defaultfontname/)() const | Nombre de fuente usado por defecto para fuentes que están ausentes en el ordenador. Cuando el documento PDF que se guarda contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza esas fuentes con la fuente predeterminada (si se encuentra una fuente con [DefaultFontName](../) en el dispositivo). |
| [get_TempPath](./get_temppath/)() const | Ruta para archivos temporales. |
| [PdfSaveOptions](./pdfsaveoptions/)() | Constructor. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Nombre de fuente usado por defecto para fuentes que están ausentes en el ordenador. Cuando el documento PDF que se guarda contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza esas fuentes con la fuente predeterminada (si se encuentra una fuente con [DefaultFontName](../) en el dispositivo). |
| [set_TempPath](./set_temppath/)(const System::String\&) | Ruta para archivos temporales. |
## Ver también

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
