---
title: AttributeName
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa la clase para los valores de nombre de atributo.
type: docs
weight: 4050
url: /es/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Representa la clase para los valores de nombre de atributo.

```csharp
public sealed class AttributeName
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Obtiene clave de atributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Obtiene el valor del nombre del atributo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Obtiene el nombre de atributo para la clave de atributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Devuelve una cadena que representa el objeto actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Atributo BlockAlign: After - Después del borde del rectángulo de asignación del último elemento secundario alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Atributo BlockAlign: Antes - Antes del borde del rectángulo de asignación del primer hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Atributo BlockAlign: Justificar: elementos secundarios alineados con los bordes anteriores y posteriores del rectángulo de contenido de la celda de la tabla. El primer niño se colocará como se describe para Antes y el último niño como se describe para Después, con el mismo espacio entre los niños. Si solo hay un hijo, se alineará solo con el borde anterior, como para Antes. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Atributo BlockAlign: Middle- Children centrado dentro de la celda de la tabla. La distancia entre el borde anterior del rectángulo de asignación del primer niño y el del rectángulo de contenido de la celda de la tabla será la misma que la distancia entre el borde posterior del rectángulo de asignación del último niño y el del rectángulo de contenido de la celda de la tabla. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribute BorderStyle: Discontinuo: el borde es una serie de segmentos de línea cortos. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribute BorderStyle: Dotted: el borde es una serie de puntos. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attribute BorderStyle: Double: el borde consta de dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas es igual al valor de BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribute BorderStyle: Groove: el borde parece tallado en el lienzo. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribute BorderStyle: Hidden - Igual que Ninguno, excepto en términos de resolución de conflictos de borde para elementos de tabla. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribute BorderStyle: Inset: el borde hace que todo el cuadro se vea como si estuviera incrustado en el lienzo. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Atributo BorderStyle: Ninguno: sin borde. Obliga al valor calculado de BorderThickness a ser 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribute BorderStyle: Outset: el borde hace que todo el cuadro se vea como si saliera del lienzo (lo opuesto a Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribute BorderStyle: Ridge: el borde parece salir del lienzo (lo opuesto a Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Atributo BorderStyle: Sólido: el borde es un segmento de una sola línea. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Atributo marcado: Neutral: el estado de un botón de opción o campo de casilla de verificación. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Atributo marcado: Desactivado: el estado de un botón de opción o campo de casilla de verificación. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Atributo marcado: Activado: el estado de un botón de opción o campo de casilla de verificación. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Atributo GlyphOrientationVertical: Auto: especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Altura del atributo: Auto - La altura del elemento será determinada por la altura intrínseca de su contenido. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Atributo InlineAlign: Center: cada hijo centrado dentro de la celda de la tabla. La distancia entre los bordes iniciales del rectángulo de asignación del hijo y el rectángulo de contenido de la celda de la tabla será la misma que la distancia entre sus bordes finales. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Atributo InlineAlign: Fin: borde final del rectángulo de asignación de cada elemento secundario alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Atributo InlineAlign: Inicio: borde inicial del rectángulo de asignación de cada hijo alineado con el del rectángulo de contenido de la celda de la tabla. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attribute LineHeight: Auto - No se realizará el ajuste del valor de BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attribute LineHeight: Normal: ajuste la altura de la línea para incluir cualquier valor distinto de cero especificado para BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Numeración de lista de atributos: Círculo - Viñeta circular abierta. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Numeración de lista de atributos: Decimal - Números arábigos decimales (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Numeración de lista de atributos: Disco - Viñeta circular sólida. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Numeración de lista de atributos: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Atributo ListNumbering: LowerRoman - Números romanos en minúsculas (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Numeración de lista de atributos: Ninguno: sin numeración automática; Los elementos Lbl (si están presentes) contienen texto arbitrario que no está sujeto a ningún esquema de numeración. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Numeración de lista de atributos: Cuadrado - Viñeta cuadrada sólida. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Numeración de lista de atributos: UpperAlpha - Letras mayúsculas (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Atributo ListNumbering: UpperRoman - Números romanos en mayúsculas (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Ubicación del atributo: antes: colocado de manera que el borde anterior del rectángulo de asignación del elemento coincida con el del área de referencia envolvente más cercana. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Ubicación del atributo: Bloque: apilado en la dirección de progresión del bloque dentro de un área de referencia envolvente o BLSE principal. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Ubicación del atributo: Fin: colocado de manera que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia envolvente más cercana. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Ubicación del atributo: en línea: empaquetado en la dirección de progresión en línea dentro de un BLSE envolvente. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Ubicación del atributo: Inicio: colocado de manera que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia envolvente más cercana. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Rol de atributo: cb - Casilla de verificación. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Atributo Rol: pb - Pulsador. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Rol de atributo: rb - Botón de radio. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Rol de atributo: tv - Campo de valor de texto. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Atributo RubyAlign: Centro: el contenido se centrará en la dirección de progresión en línea. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Atributo RubyAlign: Distribuir: el contenido se expandirá para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se insertará un espacio en el borde inicial y final del texto. El espaciado se distribuirá utilizando una proporción de 1:2:1 (inicio:infijo:final). Se cambiará a una proporción de 0:1:1 si el rubí aparece al principio de una línea de texto o a una proporción de 1:1:0 si el rubí aparece al final de la línea de texto. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Atributo RubyAlign: Fin: el contenido se alineará en el borde final en la dirección de progresión en línea. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Atributo RubyAlign: Justificar: el contenido se expandirá para llenar el ancho disponible en la dirección de progresión en línea. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Atributo RubyAlign: Inicio: el contenido se alineará en el borde de inicio en la dirección de progresión en línea. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attribute RubyPosition: After: el contenido de RT se alineará a lo largo del borde posterior del elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attribute RubyPosition: Before: el contenido de RT se alineará a lo largo del borde anterior del elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attribute RubyPosition: Inline: el RT y los elementos RP asociados se formatearán como un comentario entre paréntesis, después del elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Atributo RubyPosition: Warichu: el RT y los elementos RP asociados se formatearán como un warichu, después del elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Ámbito de atributo: Ambos. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Ámbito de atributo: Columna. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Ámbito de atributo: Fila. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Atributo TextAlign: Centro: centrado entre los bordes inicial y final. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Atributo TextAlign: End - Alineado con el borde final. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Atributo TextAlign: Justificar: alineado con los bordes inicial y final, con el espacio interno dentro de cada línea expandido, si es necesario, para lograr dicha alineación. La última (o única) línea se alineará únicamente con el borde inicial. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Atributo TextAlign: Inicio - Alineado con el borde inicial. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Atributo TextDecorationType: LineThrough - Una línea a través del medio del texto. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Atributo TextDecorationType: Ninguno - Sin decoración de texto. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Atributo TextDecorationType: Overline: una línea encima del texto. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Atributo TextDecorationType: Subrayado: una línea debajo del texto. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Ancho del atributo: Auto - el ancho del elemento será determinado por el ancho intrínseco de su contenido. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Modo de escritura del atributo: LrTb - Progresión en línea de izquierda a derecha; bloquear la progresión de arriba hacia abajo. Este es el modo de escritura típico de los sistemas de escritura occidentales. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Modo de escritura del atributo: RlTb - Progresión en línea de derecha a izquierda; bloquear la progresión de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Modo de escritura del atributo: TbRl: progresión en línea de arriba a abajo; bloquear la progresión de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura chinos y japoneses. |

### Ver también

* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
