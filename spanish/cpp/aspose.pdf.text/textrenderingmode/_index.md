---
title: "Aspose::Pdf::Text::TextRenderingMode enum"
linktitle: "TextRenderingMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextRenderingMode enum. El modo de renderizado de texto, Tmode, determina si al mostrar texto se deben trazar los contornos de los glifos, rellenarlos, usarlos como límite de recorte, o alguna combinación de los tres en C++."
type: docs
weight: 6100
url: /es/cpp/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enum


El modo de renderizado de texto, Tmode, determina si mostrar texto hará que los contornos de los glifos se dibujen, se rellenen, se usen como límite de recorte, o alguna combinación de los tres.

```cpp
enum class TextRenderingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| FillText | 0 | Rellenar texto. |
| StrokeText | 1 | Trazar texto. |
| FillThenStrokeText | 2 | Rellenar, luego trazar texto. |
| Invisible | 3 | Ni rellenar ni trazar texto (invisible). |
| FillTextAndAddPathToClipping | 4 | Rellenar texto y añadir a la ruta para recorte (ver 9.3.6, "Modo de renderizado de texto,"). |
| StrokeTextAndAddPathToClipping | 5 | Trazar texto y añadir a la ruta para recorte. |
| FillThenStrokeTextAndAddPathToClipping | 6 | Rellenar, luego trazar texto y añadir a la ruta para recorte. |
| AddPathToClipping | 7 | Añadir texto a la ruta para recorte. |

## Ver también

* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
