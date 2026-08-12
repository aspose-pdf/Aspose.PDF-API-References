---
title: "Clase Aspose::Pdf::Facades::Stamp"
linktitle: "Stamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::Stamp. Clase que representa un sello en C++."
type: docs
weight: 3500
url: /es/cpp/aspose.pdf.facades/stamp/
---
## Stamp class


Clase que representa una marca.

```cpp
class Stamp : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindImage](./bindimage/)(const System::String\&) | Establece la imagen como sello. |
| [BindImage](./bindimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece la imagen que se usará como sello. |
| [BindLogo](./bindlogo/)(const System::SharedPtr\<FormattedText\>\&) | Establece el texto como sello. |
| [BindPdf](./bindpdf/)(const System::String\&, int32_t) | Establece el archivo PDF y el número de página que se usarán como sello. |
| [BindPdf](./bindpdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Establece el archivo PDF y el número de página que se usarán como sello. |
| [BindTextState](./bindtextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Establece el estado del texto del sello. |
| [get_BlendingSpace](./get_blendingspace/)() const | Obtiene un valor de [BlendingColorSpace](../blendingcolorspace/) que define un espacio de color que se usa para realizar operaciones de transparencia y mezcla en la página. |
| [get_IsBackground](./get_isbackground/)() const | Obtiene el estado del fondo. Si es verdadero, el sello se colocará como fondo de la página sellada. Por defecto está configurado como falso. |
| [get_Opacity](./get_opacity/)() | Obtiene la opacidad del sello. |
| [get_PageNumber](./get_pagenumber/)() const | Obtiene el número de página. |
| [get_Pages](./get_pages/)() const | Obtiene una matriz con los números de página que serán afectados por el sello. Si Pages = null, todas las páginas del documento se ven afectadas. |
| [get_Quality](./get_quality/)() const | Obtiene la calidad del sello de imagen en porcentaje. Valores válidos 0..100%. |
| [get_Rotation](./get_rotation/)() const | Obtiene la rotación del sello en grados. |
| [get_StampId](./get_stampid/)() const | Obtiene el identificador del sello. |
| [set_BlendingSpace](./set_blendingspace/)(BlendingColorSpace) | Establece un valor de [BlendingColorSpace](../blendingcolorspace/) que define un espacio de color que se usa para realizar operaciones de transparencia y mezcla en la página. |
| [set_IsBackground](./set_isbackground/)(bool) | Establece el estado del fondo. Si es verdadero, el sello se colocará como fondo de la página sellada. Por defecto está configurado como falso. |
| [set_Opacity](./set_opacity/)(float) | Establece la opacidad del sello. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Establece el número de página. |
| [set_Pages](./set_pages/)(const System::ArrayPtr\<int32_t\>\&) | Establece una matriz con los números de página que serán afectados por el sello. Si Pages = null, todas las páginas del documento se ven afectadas. |
| [set_Quality](./set_quality/)(int32_t) | Establece la calidad del sello de imagen en porcentaje. Valores válidos 0..100%. |
| [set_Rotation](./set_rotation/)(float) | Establece la rotación del sello en grados. |
| [set_StampId](./set_stampid/)(int32_t) | Establece el identificador del sello. |
| [SetImageSize](./setimagesize/)(float, float) | Establece el tamaño del sello de imagen. [Image](../../aspose.pdf/image/) se escalará según los valores especificados. |
| [SetOrigin](./setorigin/)(float, float) | Establece la posición en la página donde se colocará el sello. |
| [Stamp](./stamp/)() | Constructor del objeto [Stamp](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
