---
title: "Clase Aspose::Pdf::FloatingBox"
linktitle: "FloatingBox"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::FloatingBox. Representa un FloatingBox en un documento Pdf. FloatingBox se posiciona de forma personalizada en C++."
type: docs
weight: 5700
url: /es/cpp/aspose.pdf/floatingbox/
---
## FloatingBox class


Representa un [FloatingBox](./) en un documento [Pdf](../). [FloatingBox](./) se posiciona de forma personalizada.

```cpp
class FloatingBox : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona un nuevo objeto [FloatingBox](./). Los [Paragraphs](../paragraphs/) en la caja flotante no se clonan. |
| [FloatingBox](./floatingbox/)(float, float) | Inicializa una nueva instancia de la clase [FloatingBox](./) con el ancho y alto especificados. |
| [FloatingBox](./floatingbox/)() | Inicializa una nueva instancia de la clase [FloatingBox](./). |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene un objeto [Aspose::Pdf::Color](../color/) que indica el color de fondo de la caja flotante. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Obtiene la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| [get_Border](./get_border/)() const | Obtiene un objeto [BorderInfo](../borderinfo/) que indica la información del borde de la caja flotante. |
| [get_ColumnInfo](./get_columninfo/)() const | Obtiene la información de la columna. |
| [get_Height](./get_height/)() const | Obtiene un valor float que indica la altura de la caja flotante. |
| [get_IsNeedRepeating](./get_isneedrepeating/)() const | Obtiene un valor bool que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es false. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows. |
| [get_Left](./get_left/)() const | Obtiene la coordenada izquierda de la tabla. |
| [get_Padding](./get_padding/)() const | Obtiene un objeto [MarginInfo](../margininfo/) que indica el relleno de la caja flotante. |
| [get_Paragraphs](./get_paragraphs/)() const | Obtiene una colección [Paragraphs](../paragraphs/) que indica todos los párrafos en la celda. |
| [get_PositioningMode](./get_positioningmode/)() const | Especifica la variante para determinar la ubicación del [FloatingBox](./) en la página. |
| [get_Top](./get_top/)() const | Obtiene la coordenada superior de la tabla. |
| [get_Width](./get_width/)() const | Obtiene un valor float que indica el ancho de la caja flotante. |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Establece un objeto [Aspose::Pdf::Color](../color/) que indica el color de fondo de la caja flotante. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Image\>\&) | Establece la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| [set_Border](./set_border/)(const System::SharedPtr\<BorderInfo\>\&) | Establece un objeto [BorderInfo](../borderinfo/) que indica la información del borde de la caja flotante. |
| [set_ColumnInfo](./set_columninfo/)(const System::SharedPtr\<Aspose::Pdf::ColumnInfo\>\&) | Establece la información de la columna. |
| [set_Height](./set_height/)(double) | Establece un valor float que indica la altura de la caja flotante. |
| [set_IsNeedRepeating](./set_isneedrepeating/)(bool) | Establece un valor bool que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es false. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows. |
| [set_Left](./set_left/)(double) | Establece la coordenada izquierda de la tabla. |
| [set_Padding](./set_padding/)(const System::SharedPtr\<MarginInfo\>\&) | Establece un objeto [MarginInfo](../margininfo/) que indica el relleno de la caja flotante. |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Establece una colección [Paragraphs](../paragraphs/) que indica todos los párrafos en la celda. |
| [set_PositioningMode](./set_positioningmode/)(ParagraphPositioningMode) | Especifica la variante para determinar la ubicación del [FloatingBox](./) en la página. |
| [set_Top](./set_top/)(double) | Establece la coordenada superior de la tabla. |
| [set_Width](./set_width/)(double) | Establece un valor flotante que indica el ancho del cuadro flotante. |
## Ver también

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
