---
title: "AttributeName"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para valores de nombres de atributos."
type: docs
weight: 50
url: /es/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Representa una clase para valores de nombres de atributos.

El tipo AttributeName expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| name | Obtiene el valor del nombre del atributo. |
| attribute_key | Obtiene la clave del atributo. |
| PLACEMENT_BLOCK | Ubicación del atributo: Block - Apilado en la dirección de progresión de bloque dentro de un área de referencia contenedora o BLSE padre. |
| PLACEMENT_INLINE | Ubicación del atributo: Inline - Compactado en la dirección de progresión en línea dentro de un BLSE contenedor. |
| PLACEMENT_BEFORE | Ubicación del atributo: Before - Colocado de modo que el borde anterior del rectángulo de asignación del elemento coincida con el del área de referencia contenedora más cercana. |
| PLACEMENT_START | Ubicación del atributo: Start - Colocado de modo que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia contenedora más cercana. |
| PLACEMENT_END | Ubicación del atributo: End - Colocado de modo que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia contenedora más cercana. |
| WRITING_MODE_LR_TB | Modo de escritura del atributo: LrTb - Progresión en línea de izquierda a derecha; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura occidentales. |
| WRITING_MODE_RL_TB | Modo de escritura del atributo: RlTb - Progresión en línea de derecha a izquierda; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo. |
| WRITING_MODE_TB_RL | Modo de escritura del atributo: TbRl - Progresión en línea de arriba a abajo; progresión de bloque de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura chino y japonés. |
| BORDER_STYLE_NONE | Estilo de borde del atributo: None - Sin borde. Obliga al valor calculado de BorderThicknessto a ser 0. |
| BORDER_STYLE_HIDDEN | Estilo de borde del atributo: Hidden - Igual que None, excepto en términos de resolución de conflictos de borde para elementos de tabla. |
| BORDER_STYLE_DOTTED | Estilo de borde del atributo: Dotted - El borde es una serie de puntos. |
| BORDER_STYLE_DASHED | Atributo BorderStyle: Dashed - El borde es una serie de segmentos de línea cortos. |
| BORDER_STYLE_SOLID | Atributo BorderStyle: Solid - El borde es un único segmento de línea. |
| BORDER_STYLE_DOUBLE | Atributo BorderStyle: Double - El borde son dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas equivale al valor de BorderThickness. |
| BORDER_STYLE_GROOVE | Atributo BorderStyle: Groove - El borde parece estar tallado en el lienzo. |
| BORDER_STYLE_RIDGE | Atributo BorderStyle: Ridge - El borde parece sobresalir del lienzo (lo opuesto a Groove). |
| BORDER_STYLE_INSET | Atributo BorderStyle: Inset - El borde hace que todo el cuadro parezca estar incrustado en el lienzo. |
| BORDER_STYLE_OUTSET | Atributo BorderStyle: Outset - El borde hace que todo el cuadro parezca sobresalir del lienzo (lo opuesto a Inset). |
| TEXT_ALIGN_START | Atributo TextAlign: Start - Alineado con el borde inicial. |
| TEXT_ALIGN_CENTER | Atributo TextAlign: Center - Centrado entre los bordes inicial y final. |
| TEXT_ALIGN_END | Atributo TextAlign: End - Alineado con el borde final. |
| TEXT_ALIGN_JUSTIFY | Atributo TextAlign: Justify - Alineado con ambos bordes, inicial y final, con el espaciado interno de cada línea ampliado, si es necesario, para lograr dicha alineación. La última (o única) línea se alineará solo con el borde inicial. |
| WIDTH_AUTO | Atributo Width: Auto - el ancho del elemento se determinará por el ancho intrínseco de su contenido. |
| HEIGHT_AUTO | Atributo Height: Auto - La altura del elemento se determinará por la altura intrínseca de su contenido. |
| BLOCK_ALIGN_BEFORE | Atributo BlockAlign: Before - El borde anterior del rectángulo de asignación del primer hijo se alinea con el del rectángulo de contenido de la celda de la tabla. |
| BLOCK_ALIGN_MIDDLE | Atributo BlockAlign: Medio - Los niños centrados dentro de la celda de la tabla. La distancia entre el borde anterior del rectángulo de asignación del primer niño y el del rectángulo de contenido de la celda de la tabla deberá ser la misma que la distancia entre el borde posterior del rectángulo de asignación del último niño y el del rectángulo de contenido de la celda de la tabla. |
| BLOCK_ALIGN_AFTER | Atributo BlockAlign: Después - El borde posterior del rectángulo de asignación del último niño alineado con el del rectángulo de contenido de la celda de la tabla. |
| BLOCK_ALIGN_JUSTIFY | Atributo BlockAlign: Justificar - Los niños alineados con ambos bordes, anterior y posterior, del rectángulo de contenido de la celda de la tabla. El primer niño se colocará como se describe para Antes y el último niño como se describe para Después, con un espaciado igual entre los niños. Si solo hay un niño, se alineará solo con el borde anterior, como en Antes. |
| INLINE_ALIGN_START | Atributo InlineAlign: Inicio - El borde inicial del rectángulo de asignación de cada niño alineado con el del rectángulo de contenido de la celda de la tabla. |
| INLINE_ALIGN_CENTER | Atributo InlineAlign: Centro - Cada niño centrado dentro de la celda de la tabla. La distancia entre los bordes iniciales del rectángulo de asignación del niño y el rectángulo de contenido de la celda de la tabla deberá ser la misma que la distancia entre sus bordes finales. |
| INLINE_ALIGN_END | Atributo InlineAlign: Fin - El borde final del rectángulo de asignación de cada niño alineado con el del rectángulo de contenido de la celda de la tabla. |
| LINE_HEIGHT_NORMAL | Atributo LineHeight: Normal - Ajustar la altura de línea para incluir cualquier valor distinto de cero especificado para BaselineShift. |
| LINE_HEIGHT_AUTO | Atributo LineHeight: Auto - No se realizará ajuste para el valor de BaselineShift. |
| TEXT_DECORATION_TYPE_NONE | Atributo TextDecorationType: Ninguno - Sin decoración de texto. |
| TEXT_DECORATION_TYPE_UNDERLINE | Atributo TextDecorationType: Subrayado - Una línea debajo del texto. |
| TEXT_DECORATION_TYPE_OVERLINE | Atributo TextDecorationType: Sobrelineado - Una línea encima del texto. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Atributo TextDecorationType: Tachar - Una línea a través del medio del texto. |
| RUBY_ALIGN_START | Atributo RubyAlign: Inicio - El contenido debe alinearse en el borde inicial en la dirección de progresión en línea. |
| RUBY_ALIGN_CENTER | Atributo RubyAlign: Centro - El contenido debe centrarse en la dirección de progresión en línea. |
| RUBY_ALIGN_END | Atributo RubyAlign: Final - El contenido debe alinearse en el borde final en la dirección de progresión en línea. |
| RUBY_ALIGN_JUSTIFY | Atributo RubyAlign: Justificar - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. |
| RUBY_ALIGN_DISTRIBUTE | Atributo RubyAlign: Distribuir - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se insertará espacio en el borde inicial y en el borde final del texto. El espaciado se distribuirá usando una proporción 1:2:1 (inicio:inserto:final). Se cambiará a una proporción 0:1:1 si el ruby aparece al inicio de una línea de texto o a una proporción 1:1:0 si el ruby aparece al final de la línea de texto. |
| RUBY_POSITION_BEFORE | Atributo RubyPosition: Antes - El contenido RT debe alinearse a lo largo del borde anterior del elemento. |
| RUBY_POSITION_AFTER | Atributo RubyPosition: Después - El contenido RT debe alinearse a lo largo del borde posterior del elemento. |
| RUBY_POSITION_WARICHU | Atributo RubyPosition: Warichu - Los elementos RT y RP asociados deben formatearse como un warichu, siguiendo al elemento RB. |
| RUBY_POSITION_INLINE | Atributo RubyPosition: En línea - Los elementos RT y RP asociados deben formatearse como un comentario entre paréntesis, siguiendo al elemento RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Atributo GlyphOrientationVertical: Auto - Especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto). |
| LIST_NUMBERING_NONE | Atributo ListNumbering: Ninguno - No hay numeración automática; los elementos Lbl (si están presentes) contienen texto arbitrario que no está sujeto a ningún esquema de numeración. |
| LIST_NUMBERING_DISC | Atributo ListNumbering: Disco - Viñeta circular sólida. |
| LIST_NUMBERING_CIRCLE | Atributo ListNumbering: Círculo - Viñeta circular abierta. |
| LIST_NUMBERING_SQUARE | Atributo ListNumbering: Square - Viñeta cuadrada sólida. |
| LIST_NUMBERING_DECIMAL | Atributo ListNumbering: Decimal - Números arábigos decimales (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Atributo ListNumbering: UpperRoman - Numerales romanos en mayúsculas (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Atributo ListNumbering: LowerRoman - Numerales romanos en minúsculas (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Atributo ListNumbering: UpperAlpha - Letras mayúsculas (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| ROLE_RB | Atributo Role: rb - Botón de opción. |
| ROLE_CB | Atributo Role: cb - Casilla de verificación. |
| ROLE_PB | Atributo Role: pb - Botón pulsador. |
| ROLE_TV | Atributo Role: tv - Campo de valor de texto. |
| CHECKED_ON | Atributo checked: On - El estado de un botón de opción o una casilla de verificación. |
| CHECKED_OFF | Atributo checked: Off - El estado de un botón de opción o una casilla de verificación. |
| CHECKED_NEUTRAL | Atributo verificado: Neutral - El estado de un botón de opción o casilla de verificación. |
| SCOPE_ROW | Ámbito del atributo: Fila. |
| SCOPE_COLUMN | Ámbito del atributo: Columna. |
| SCOPE_BOTH | Ámbito del atributo: Ambos. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Obtiene el nombre del atributo para la clave del atributo. |

### Ver también

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

