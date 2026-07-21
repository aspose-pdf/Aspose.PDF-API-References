---
title: "Clase Aspose::Pdf::LogicalStructure::AttributeName"
linktitle: "AttributeName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LogicalStructure::AttributeName. Representa la clase para valores de nombres de atributos en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class


Representa la clase para valores de nombres de atributos.

```cpp
class AttributeName : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [FromNameAttributeKey](./fromnameattributekey/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::LogicalStructure::AttributeKey\>\&) | Obtiene el nombre del atributo para la clave del atributo. |
| [get_AttributeKey](./get_attributekey/)() const | Obtiene la clave del atributo. |
| [get_Name](./get_name/)() const | Obtiene el valor del nombre del atributo. |
| [ToString](./tostring/)() const override | Devuelve una cadena que representa el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [BlockAlign_After](./blockalign_after/) | Atributo BlockAlign: After - Borde posterior del rectángulo de asignación del último hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static [BlockAlign_Before](./blockalign_before/) | Atributo BlockAlign: Before - Borde anterior del rectángulo de asignación del primer hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static [BlockAlign_Justify](./blockalign_justify/) | Atributo BlockAlign: Justify - Los hijos están alineados con ambos bordes, anterior y posterior, del rectángulo de contenido de la celda de la tabla. El primer hijo se colocará como se describe para Before y el último hijo como se describe para After, con un espaciado igual entre los hijos. Si solo hay un hijo, se alineará únicamente con el borde anterior, como en Before. |
| static [BlockAlign_Middle](./blockalign_middle/) | Atributo BlockAlign: Middle - Los hijos centrados dentro de la celda de la tabla. La distancia entre el borde anterior del rectángulo de asignación del primer hijo y el del rectángulo de contenido de la celda de la tabla será la misma que la distancia entre el borde posterior del rectángulo de asignación del último hijo y el del rectángulo de contenido de la celda de la tabla. |
| static [BorderStyle_Dashed](./borderstyle_dashed/) | Atributo BorderStyle: Dashed - El borde es una serie de segmentos de línea cortos. |
| static [BorderStyle_Dotted](./borderstyle_dotted/) | Atributo BorderStyle: Dotted - El borde es una serie de puntos. |
| static [BorderStyle_Double](./borderstyle_double/) | Atributo BorderStyle: Double - El borde consiste en dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas equivale al valor de BorderThickness. |
| static [BorderStyle_Groove](./borderstyle_groove/) | Atributo BorderStyle: Groove - El borde parece estar tallado en el lienzo. |
| static [BorderStyle_Hidden](./borderstyle_hidden/) | Atributo BorderStyle: Hidden - Igual que None, excepto en la resolución de conflictos de bordes para elementos de tabla. |
| static [BorderStyle_Inset](./borderstyle_inset/) | Atributo BorderStyle: Inset - El borde hace que todo el cuadro parezca incrustado en el lienzo. |
| static [BorderStyle_None](./borderstyle_none/) | Atributo BorderStyle: None - Sin borde. Obliga a que el valor calculado de BorderThickness sea 0. |
| static [BorderStyle_Outset](./borderstyle_outset/) | Atributo BorderStyle: Outset - El borde hace que todo el cuadro parezca salir del lienzo (lo contrario de Inset). |
| static [BorderStyle_Ridge](./borderstyle_ridge/) | Atributo BorderStyle: Ridge - El borde parece como si estuviera saliendo del lienzo (lo opuesto a Groove). |
| static [BorderStyle_Solid](./borderstyle_solid/) | Atributo BorderStyle: Solid - El borde es un segmento de línea único. |
| static [Checked_neutral](./checked_neutral/) | Atributo checked: Neutral - El estado de un botón de opción o campo de casilla de verificación. |
| static [Checked_off](./checked_off/) | Atributo checked: Off - El estado de un botón de opción o campo de casilla de verificación. |
| static [Checked_on](./checked_on/) | Atributo checked: On - El estado de un botón de opción o campo de casilla de verificación. |
| static [GlyphOrientationVertical_Auto](./glyphorientationvertical_auto/) | Atributo GlyphOrientationVertical: Auto - Especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto). |
| static [Height_Auto](./height_auto/) | Atributo Height: Auto - La altura del elemento se determinará por la altura intrínseca de su contenido. |
| static [InlineAlign_Center](./inlinealign_center/) | Atributo InlineAlign: [Center](../../aspose.pdf/center/) - Cada hijo centrado dentro de la celda de la tabla. La distancia entre los bordes iniciales del rectángulo de asignación del hijo y el rectángulo de contenido de la celda de la tabla será la misma que la distancia entre sus bordes finales. |
| static [InlineAlign_End](./inlinealign_end/) | Atributo InlineAlign: End - El borde final del rectángulo de asignación de cada hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static [InlineAlign_Start](./inlinealign_start/) | Atributo InlineAlign: Start - El borde inicial del rectángulo de asignación de cada hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static [LineHeight_Auto](./lineheight_auto/) | Atributo LineHeight: Auto - No se realizará ajuste para el valor de BaselineShift. |
| static [LineHeight_Normal](./lineheight_normal/) | Atributo LineHeight: Normal - Ajusta la altura de línea para incluir cualquier valor distinto de cero especificado para BaselineShift. |
| static [ListNumbering_Circle](./listnumbering_circle/) | Atributo ListNumbering: Circle - Viñeta circular abierta. |
| static [ListNumbering_Decimal](./listnumbering_decimal/) | Atributo ListNumbering: Decimal - Números arábigos decimales (1-9, 10-99, ...). |
| static [ListNumbering_Disc](./listnumbering_disc/) | Atributo ListNumbering: Disc - Viñeta circular sólida. |
| static [ListNumbering_LowerAlpha](./listnumbering_loweralpha/) | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| static [ListNumbering_LowerRoman](./listnumbering_lowerroman/) | Atributo ListNumbering: LowerRoman - Numerales romanos en minúscula (i, ii, iii, iv, ...). |
| static [ListNumbering_None](./listnumbering_none/) | Atributo ListNumbering: None - Sin autonumeración; los elementos Lbl (si están presentes) contienen texto arbitrario que no está sujeto a ningún esquema de numeración. |
| static [ListNumbering_Square](./listnumbering_square/) | Atributo ListNumbering: Square - Viñeta cuadrada sólida. |
| static [ListNumbering_UpperAlpha](./listnumbering_upperalpha/) | Atributo ListNumbering: UpperAlpha - Letras mayúsculas (A, B, C, ...). |
| static [ListNumbering_UpperRoman](./listnumbering_upperroman/) | Atributo ListNumbering: UpperRoman - Numerales romanos en mayúscula (I, II, III, IV, ...). |
| static [Placement_Before](./placement_before/) | Atributo Placement: Before - Colocado de modo que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia contenedora más cercana. |
| static [Placement_Block](./placement_block/) | Atributo Placement: Block - Apilado en la dirección de progresión de bloque dentro de un área de referencia contenedora o BLSE padre. |
| static [Placement_End](./placement_end/) | Atributo Placement: End - Colocado de modo que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia contenedora más cercana. |
| static [Placement_Inline](./placement_inline/) | Atributo Placement: Inline - Empaquetado en la dirección de progresión en línea dentro de un BLSE contenedor. |
| static [Placement_Start](./placement_start/) | Ubicación del atributo: Inicio - Colocado de modo que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo encierra. |
| static [Role_cb](./role_cb/) | Rol del atributo: cb - Casilla de verificación. |
| static [Role_pb](./role_pb/) | Rol del atributo: pb - Botón pulsador. |
| static [Role_rb](./role_rb/) | Rol del atributo: rb - Botón de opción. |
| static [Role_tv](./role_tv/) | Rol del atributo: tv - Campo de valor de texto. |
| static [RubyAlign_Center](./rubyalign_center/) | Alineación Ruby del atributo: [Centro](../../aspose.pdf/center/) - El contenido se centrará en la dirección de progresión en línea. |
| static [RubyAlign_Distribute](./rubyalign_distribute/) | Alineación Ruby del atributo: Distribuir - El contenido se expandirá para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se insertará espacio en el borde inicial y el borde final del texto. El espaciado se distribuirá usando una proporción 1:2:1 (inicio:inserto:fin). Cambiará a una proporción 0:1:1 si el ruby aparece al inicio de una línea de texto o a una proporción 1:1:0 si el ruby aparece al final de la línea de texto. |
| static [RubyAlign_End](./rubyalign_end/) | Alineación Ruby del atributo: Fin - El contenido se alineará en el borde final en la dirección de progresión en línea. |
| static [RubyAlign_Justify](./rubyalign_justify/) | Alineación Ruby del atributo: Justificar - El contenido se expandirá para llenar el ancho disponible en la dirección de progresión en línea. |
| static [RubyAlign_Start](./rubyalign_start/) | Alineación Ruby del atributo: Inicio - El contenido se alineará en el borde inicial en la dirección de progresión en línea. |
| static [RubyPosition_After](./rubyposition_after/) | Posición Ruby del atributo: Después - El contenido RT se alineará a lo largo del borde posterior del elemento. |
| static [RubyPosition_Before](./rubyposition_before/) | Posición Ruby del atributo: Antes - El contenido RT se alineará a lo largo del borde anterior del elemento. |
| static [RubyPosition_Inline](./rubyposition_inline/) | Posición Ruby del atributo: En línea - Los elementos RT y los RP asociados se formatearán como un comentario entre paréntesis, siguiendo al elemento RB. |
| static [RubyPosition_Warichu](./rubyposition_warichu/) | Posición Ruby del atributo: Warichu - Los elementos RT y los RP asociados se formatearán como un warichu, siguiendo al elemento RB. |
| static [Scope_Both](./scope_both/) | Ámbito del atributo: Ambos. |
| static [Scope_Column](./scope_column/) | Ámbito del atributo: Columna. |
| static [Scope_Row](./scope_row/) | Ámbito del atributo: [Fila](../../aspose.pdf/row/). |
| static [TextAlign_Center](./textalign_center/) | Alineación de texto del atributo: [Centro](../../aspose.pdf/center/) - Centrado entre los bordes inicial y final. |
| static [TextAlign_End](./textalign_end/) | Alineación de texto del atributo: Fin - Alineado con el borde final. |
| static [TextAlign_Justify](./textalign_justify/) | Alineación de texto del atributo: Justificar - Alineado con ambos bordes, inicial y final, con el espaciado interno dentro de cada línea expandido, si es necesario, para lograr dicha alineación. La última (o única) línea se alineará solo con el borde inicial. |
| static [TextAlign_Start](./textalign_start/) | Alineación de texto del atributo: Inicio - Alineado con el borde inicial. |
| static [TextDecorationType_LineThrough](./textdecorationtype_linethrough/) | Tipo de decoración de texto del atributo: Tachar - Una línea a través del medio del texto. |
| static [TextDecorationType_None](./textdecorationtype_none/) | Tipo de decoración de texto del atributo: Ninguno - Sin decoración de texto. |
| static [TextDecorationType_Overline](./textdecorationtype_overline/) | Tipo de decoración de texto del atributo: Sobreraya - Una línea sobre el texto. |
| static [TextDecorationType_Underline](./textdecorationtype_underline/) | Tipo de decoración de texto del atributo: Subrayado - Una línea debajo del texto. |
| static [Width_Auto](./width_auto/) | Atributo Width: Auto - el ancho del elemento se determinará por el ancho intrínseco de su contenido. |
| static [WritingMode_LrTb](./writingmode_lrtb/) | Atributo WritingMode: LrTb - Progresión en línea de izquierda a derecha; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura occidentales. |
| static [WritingMode_RlTb](./writingmode_rltb/) | Atributo WritingMode: RlTb - Progresión en línea de derecha a izquierda; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo. |
| static [WritingMode_TbRl](./writingmode_tbrl/) | Atributo WritingMode: TbRl - Progresión en línea de arriba a abajo; progresión de bloque de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura chino y japonés. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
