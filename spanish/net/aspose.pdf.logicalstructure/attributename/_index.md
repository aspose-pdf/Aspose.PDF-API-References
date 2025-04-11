---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.AttributeName. Representa la clase para los valores de nombre de atributo
type: docs
weight: 6220
url: /es/net/aspose.pdf.logicalstructure/attributename/
---
## Clase AttributeName

Representa la clase para los valores de nombre de atributo.

```csharp
public sealed class AttributeName
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Obtiene la clave del atributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Obtiene el valor del nombre del atributo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Obtiene el nombre del atributo para la clave del atributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Devuelve una cadena que representa el objeto actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Atributo BlockAlign: After - Borde posterior del rectángulo de asignación del último hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Atributo BlockAlign: Before - Borde anterior del rectángulo de asignación del primer hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Atributo BlockAlign: Justify - Hijos alineados con ambos bordes anterior y posterior del rectángulo de contenido de la celda de la tabla. El primer hijo se colocará como se describe para Before y el último hijo como se describe para After, con un espaciado igual entre los hijos. Si solo hay un hijo, se alineará solo con el borde anterior, como para Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Atributo BlockAlign: Middle- Hijos centrados dentro de la celda de la tabla. La distancia entre el borde anterior del rectángulo de asignación del primer hijo y el del rectángulo de contenido de la celda de la tabla será la misma que la distancia entre el borde posterior del rectángulo de asignación del último hijo y el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Atributo BorderStyle: Dashed - El borde es una serie de segmentos de línea cortos. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Atributo BorderStyle: Dotted - El borde es una serie de puntos. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Atributo BorderStyle: Double - El borde es dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas es igual al valor de BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Atributo BorderStyle: Groove - El borde parece estar tallado en el lienzo. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Atributo BorderStyle: Hidden - Igual que None, excepto en términos de resolución de conflictos de borde para elementos de tabla. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Atributo BorderStyle: Inset - El borde hace que toda la caja parezca estar incrustada en el lienzo. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Atributo BorderStyle: None - Sin borde. Obliga al valor calculado de BorderThickness a ser 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Atributo BorderStyle: Outset - El borde hace que toda la caja parezca estar saliendo del lienzo (lo opuesto a Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Atributo BorderStyle: Ridge - El borde parece estar saliendo del lienzo (lo opuesto a Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Atributo BorderStyle: Solid - El borde es un solo segmento de línea. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Atributo checked: Neutral - El estado de un campo de botón de opción o casilla de verificación. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Atributo checked: Off - El estado de un campo de botón de opción o casilla de verificación. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Atributo checked: On - El estado de un campo de botón de opción o casilla de verificación. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Atributo GlyphOrientationVertical: Auto - Especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Atributo Height: Auto - La altura del elemento se determinará por la altura intrínseca de su contenido. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Atributo InlineAlign: Center - Cada hijo centrado dentro de la celda de la tabla. La distancia entre los bordes de inicio del rectángulo de asignación del hijo y el rectángulo de contenido de la celda de la tabla será la misma que la distancia entre sus bordes finales. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Atributo InlineAlign: End - Borde final de cada rectángulo de asignación del hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Atributo InlineAlign: Start - Borde inicial de cada rectángulo de asignación del hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Atributo LineHeight: Auto - No se realizará ajuste para el valor de BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Atributo LineHeight: Normal - Ajusta la altura de la línea para incluir cualquier valor distinto de cero especificado para BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Atributo ListNumbering: Circle - Viñeta circular abierta. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Atributo ListNumbering: Decimal - Números arábigos decimales (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Atributo ListNumbering: Disc - Viñeta circular sólida. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Atributo ListNumbering: LowerRoman - Números romanos en minúscula (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Atributo ListNumbering: None - Sin numeración automática; los elementos Lbl (si están presentes) contienen texto arbitrario no sujeto a ningún esquema de numeración. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Atributo ListNumbering: Square - Viñeta cuadrada sólida. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Atributo ListNumbering: UpperAlpha - Letras mayúsculas (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Atributo ListNumbering: UpperRoman - Números romanos en mayúscula (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Atributo Placement: Before - Colocado de manera que el borde anterior del rectángulo de asignación del elemento coincida con el del área de referencia más cercana. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Atributo Placement: Block - Apilado en la dirección de progresión de bloque dentro de un área de referencia o BLSE padre que lo contenga. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Atributo Placement: End - Colocado de manera que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia más cercana. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Atributo Placement: Inline - Empacado en la dirección de progresión en línea dentro de un BLSE que lo contenga. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Atributo Placement: Start - Colocado de manera que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia más cercana. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Atributo Role: cb - Casilla de verificación. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Atributo Role: pb - Botón de presión. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Atributo Role: rb - Botón de opción. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Atributo Role: tv - Campo de texto-valor. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Atributo RubyAlign: Center - El contenido debe estar centrado en la dirección de progresión en línea. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Atributo RubyAlign: Distribute - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se debe insertar espacio en el borde de inicio y el borde final del texto. El espaciado se distribuirá utilizando una proporción de 1:2:1 (inicio:infix:final). Se cambiará a una proporción de 0:1:1 si el ruby aparece al inicio de una línea de texto o a una proporción de 1:1:0 si el ruby aparece al final de la línea de texto. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Atributo RubyAlign: End - El contenido debe estar alineado en el borde final en la dirección de progresión en línea. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Atributo RubyAlign: Justify - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Atributo RubyAlign: Start - El contenido debe estar alineado en el borde inicial en la dirección de progresión en línea. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Atributo RubyPosition: After - El contenido RT debe estar alineado a lo largo del borde posterior del elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Atributo RubyPosition: Before - El contenido RT debe estar alineado a lo largo del borde anterior del elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Atributo RubyPosition: Inline - Los elementos RT y RP asociados deben formatearse como un comentario entre paréntesis, siguiendo el elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Atributo RubyPosition: Warichu - Los elementos RT y RP asociados deben formatearse como un warichu, siguiendo el elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Atributo Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Atributo Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Atributo Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Atributo TextAlign: Center - Centrado entre los bordes inicial y final. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Atributo TextAlign: End - Alineado con el borde final. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Atributo TextAlign: Justify - Alineado con ambos bordes inicial y final, con espaciado interno dentro de cada línea expandido, si es necesario, para lograr dicha alineación. La última (o única) línea debe alinearse solo con el borde inicial. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Atributo TextAlign: Start - Alineado con el borde inicial. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Atributo TextDecorationType: LineThrough - Una línea a través del medio del texto. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Atributo TextDecorationType: None - Sin decoración de texto. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Atributo TextDecorationType: Overline - Una línea sobre el texto. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Atributo TextDecorationType: Underline - Una línea debajo del texto. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Atributo Width: Auto - la anchura del elemento se determinará por la anchura intrínseca de su contenido. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Atributo WritingMode: LrTb - Progresión en línea de izquierda a derecha; progresión de bloque de arriba hacia abajo. Este es el modo de escritura típico para los sistemas de escritura occidentales. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Atributo WritingMode: RlTb - Progresión en línea de derecha a izquierda; progresión de bloque de arriba hacia abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Atributo WritingMode: TbRl - Progresión en línea de arriba hacia abajo; progresión de bloque de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura china y japonesa. |

### Ver También

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)