---
title: "Clase Aspose::Pdf::PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::PptxSaveOptions. Opciones de guardado para exportar al formato SVG en C++."
type: docs
weight: 15800
url: /es/cpp/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class


Opciones de guardado para exportar al formato SVG.

```cpp
class PptxSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CustomProgressHandler](./get_customprogresshandler/)() const | Este controlador se puede usar para manejar eventos de progreso de conversión, por ejemplo, puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas; un ejemplo del código del controlador que muestra el progreso en la consola es: |
| [get_ImageResolution](./get_imageresolution/)() const | Obtiene la resolución de la imagen (dpi). El valor predeterminado es 192 dpi. |
| [get_OptimizeTextBoxes](./get_optimizetextboxes/)() const | Alterna el reconocimiento de columnas de texto. |
| [get_SeparateImages](./get_separateimages/)() const | Si se establece en true, las imágenes se separan de todos los demás gráficos. |
| [get_SlidesAsImages](./get_slidesasimages/)() const | Si se establece en true, todo el contenido se reconoce como imágenes (una por página). |
| [PptxSaveOptions](./pptxsaveoptions/)() | Constructor. |
| [set_CustomProgressHandler](./set_customprogresshandler/)(UnifiedSaveOptions::ConversionProgressEventHandler) | Este controlador se puede usar para manejar eventos de progreso de conversión, por ejemplo, puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas; un ejemplo del código del controlador que muestra el progreso en la consola es: |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Establece la resolución de la imagen (dpi). El valor predeterminado es 192 dpi. |
| [set_OptimizeTextBoxes](./set_optimizetextboxes/)(bool) | Alterna el reconocimiento de columnas de texto. |
| [set_SeparateImages](./set_separateimages/)(bool) | Si se establece en true, las imágenes se separan de todos los demás gráficos. |
| [set_SlidesAsImages](./set_slidesasimages/)(bool) | Si se establece en true, todo el contenido se reconoce como imágenes (una por página). |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
