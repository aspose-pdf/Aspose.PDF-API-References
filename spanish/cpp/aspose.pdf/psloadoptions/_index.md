---
title: "Aspose::Pdf::PsLoadOptions class"
linktitle: "PsLoadOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PsLoadOptions class. Representa opciones para cargar/importar archivos .mht en un documento pdf en C++."
type: docs
weight: 16100
url: /es/cpp/aspose.pdf/psloadoptions/
---
## PsLoadOptions class


Representa opciones para cargar/importar un archivo .mht en un documento pdf.

```cpp
class PsLoadOptions : public Aspose::Pdf::LoadOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ConvertFontsToTTF](./get_convertfontstottf/)() const | Especifica si guardar fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostScript a imagen. |
| [get_FontsFolders](./get_fontsfolders/)() const | Obtiene las rutas de las carpetas de fuentes. |
| [PsLoadOptions](./psloadoptions/)() | Crea opciones de carga para convertir PostScript en un documento pdf con ruta base vacía. |
| [set_ConvertFontsToTTF](./set_convertfontstottf/)(bool) | Especifica si guardar fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostScript a imagen. |
| [set_FontsFolders](./set_fontsfolders/)(const System::ArrayPtr\<System::String\>\&) | Establece las rutas de las carpetas de fuentes. |
## Ver también

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
