---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para valores de nombres de atributos."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Representa una clase para valores de nombres de atributos.

## Campos

| Campo | Descripción |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - Borde posterior del rectángulo de asignación del último hijo alineado con el del rectángulo de contenido de la celda de tabla. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - Borde anterior del rectángulo de asignación del primer hijo alineado con el del rectángulo de contenido de la celda de tabla. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - Los hijos están alineados con ambos bordes, anterior y posterior, del rectángulo de contenido de la celda de tabla. El primer hijo se coloca como se describe para Before y el último hijo como se describe para After, con un espaciado igual entre los hijos. Si solo hay un hijo, se alineará únicamente con el borde anterior, como en Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle- Los hijos centrados dentro de la celda de tabla. La distancia entre el borde anterior del rectángulo de asignación del primer hijo y el del rectángulo de contenido de la celda de tabla será la misma que la distancia entre el borde posterior del rectángulo de asignación del último hijo y el del rectángulo de contenido de la celda de tabla. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - El borde es una serie de segmentos de línea cortos. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - El borde es una serie de puntos. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - El borde son dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas equivale al valor de BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - El borde parece estar tallado en el lienzo. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - Igual que None, excepto en cuanto a la resolución de conflictos de bordes para elementos de tabla. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - El borde hace que todo el cuadro parezca estar incrustado en el lienzo. |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - Sin borde. Obliga al valor calculado de BorderThicknessto a ser 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - El borde hace que todo el cuadro parezca salir del lienzo (lo opuesto a Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - El borde parece salir del lienzo (lo opuesto a Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - El borde es un único segmento de línea. |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - El estado de un campo de botón de opción o casilla de verificación. |
| [Checked_off](#Checked_off) | Atributo checked: Off - El estado de un campo de botón de opción o casilla de verificación. |
| [Checked_on](#Checked_on) | Atributo checked: On - El estado de un campo de botón de opción o casilla de verificación. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Atributo GlyphOrientationVertical: Auto - Especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto). |
| [Height_Auto](#Height_Auto) | Atributo Height: Auto - La altura del elemento se determinará por la altura intrínseca de su contenido. |
| [InlineAlign_Center](#InlineAlign_Center) | Atributo InlineAlign: Center - Cada hijo centrado dentro de la celda de la tabla. La distancia entre los bordes iniciales del rectángulo de asignación del hijo y el rectángulo de contenido de la celda de la tabla será la misma que la distancia entre sus bordes finales. |
| [InlineAlign_End](#InlineAlign_End) | Atributo InlineAlign: End - El borde final del rectángulo de asignación de cada hijo se alinea con el del rectángulo de contenido de la celda de la tabla. |
| [InlineAlign_Start](#InlineAlign_Start) | Atributo InlineAlign: Start - El borde inicial del rectángulo de asignación de cada hijo se alinea con el del rectángulo de contenido de la celda de la tabla. |
| [LineHeight_Auto](#LineHeight_Auto) | Atributo LineHeight: Auto - No se realizará ajuste para el valor de BaselineShift. |
| [LineHeight_Normal](#LineHeight_Normal) | Atributo LineHeight: Normal - Ajusta la altura de línea para incluir cualquier valor distinto de cero especificado para BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Atributo ListNumbering: Circle - Viñeta circular abierta. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Atributo ListNumbering: Decimal - Números arábigos decimales (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Atributo ListNumbering: Disc - Viñeta circular sólida. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Atributo ListNumbering: LowerRoman - Numerales romanos en minúscula (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Atributo ListNumbering: None - Sin numeración automática; los elementos Lbl (si están presentes) contienen texto arbitrario que no está sujeto a ningún esquema de numeración. |
| [ListNumbering_Square](#ListNumbering_Square) | Atributo ListNumbering: Square - Viñeta cuadrada sólida. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Atributo ListNumbering: UpperAlpha - Letras mayúsculas (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Atributo ListNumbering: UpperRoman - Numerales romanos en mayúscula (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Atributo Placement: Before - Colocado de modo que el borde anterior del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene. |
| [Placement_Block](#Placement_Block) | Atributo Placement: Block - Apilado en la dirección de progresión de bloque dentro de un área de referencia que lo contiene o del BLSE padre. |
| [Placement_End](#Placement_End) | Atributo Placement: End - Colocado de modo que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene. |
| [Placement_Inline](#Placement_Inline) | Atributo Placement: Inline - Compactado en la dirección de progresión en línea dentro de un BLSE que lo contiene. |
| [Placement_Start](#Placement_Start) | Atributo Placement: Start - Colocado de modo que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene. |
| [Role_cb](#Role_cb) | Atributo Role: cb - Casilla de verificación. |
| [Role_pb](#Role_pb) | Atributo Role: pb - Botón pulsador. |
| [Role_rb](#Role_rb) | Atributo Role: rb - Botón de opción. |
| [Role_tv](#Role_tv) | Atributo Role: tv - Campo de texto-valor. |
| [RubyAlign_Center](#RubyAlign_Center) | Atributo RubyAlign: Center - El contenido debe centrarse en la dirección de progresión en línea. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Atributo RubyAlign: Distribute - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se insertará espacio en el borde inicial y el borde final del texto. El espaciado se distribuirá usando una proporción 1:2:1 (inicio:infix:fin). Se cambiará a una proporción 0:1:1 si el ruby aparece al inicio de una línea de texto o a una proporción 1:1:0 si el ruby aparece al final de la línea de texto. |
| [RubyAlign_End](#RubyAlign_End) | Atributo RubyAlign: End - El contenido debe alinearse en el borde final en la dirección de progresión en línea. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Atributo RubyAlign: Justify - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. |
| [RubyAlign_Start](#RubyAlign_Start) | Atributo RubyAlign: Start - El contenido debe alinearse en el borde inicial en la dirección de progresión en línea. |
| [RubyPosition_After](#RubyPosition_After) | Atributo RubyPosition: After - El contenido RT debe alinearse a lo largo del borde posterior del elemento. |
| [RubyPosition_Before](#RubyPosition_Before) | Atributo RubyPosition: Before - El contenido RT debe alinearse a lo largo del borde anterior del elemento. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Atributo RubyPosition: Inline - Los elementos RT y RP asociados deben formatearse como un comentario entre paréntesis, siguiendo al elemento RB. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Atributo RubyPosition: Warichu - Los elementos RT y RP asociados deben formatearse como un warichu, siguiendo al elemento RB. |
| [Scope_Both](#Scope_Both) | Atributo Scope: Ambos. |
| [Scope_Column](#Scope_Column) | Atributo Scope: Columna. |
| [Scope_Row](#Scope_Row) | Atributo Scope: Fila. |
| [TextAlign_Center](#TextAlign_Center) | Atributo TextAlign: Center - Centrado entre los bordes inicial y final. |
| [TextAlign_End](#TextAlign_End) | Atributo TextAlign: End - Alineado con el borde final. |
| [TextAlign_Justify](#TextAlign_Justify) | Atributo TextAlign: Justify - Alineado con ambos bordes inicial y final, con el espaciado interno dentro de cada línea expandido, si es necesario, para lograr tal alineación. La última (o única) línea debe alinearse solo con el borde inicial. |
| [TextAlign_Start](#TextAlign_Start) | Atributo TextAlign: Start - Alineado con el borde inicial. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Atributo TextDecorationType: LineThrough - Una línea a través del medio del texto. |
| [TextDecorationType_None](#TextDecorationType_None) | Atributo TextDecorationType: None - Sin decoración de texto. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Atributo TextDecorationType: Overline - Una línea sobre el texto. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Atributo TextDecorationType: Underline - Una línea bajo el texto. |
| [Width_Auto](#Width_Auto) | Atributo Width: Auto - El ancho del elemento se determinará por el ancho intrínseco de su contenido. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Atributo WritingMode: LrTb - Progresión en línea de izquierda a derecha; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura occidentales. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Atributo WritingMode: RlTb - Progresión en línea de derecha a izquierda; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Atributo WritingMode: TbRl - Progresión en línea de arriba a abajo; progresión de bloque de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura chinos y japoneses. |

## Métodos

| Método | Descripción |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Obtiene el nombre del atributo para la clave del atributo. |
| [getAttributeKey](#getAttributeKey--) | Obtiene la clave del atributo. |
| [getName](#getName--) | Obtiene el valor del nombre del atributo. |
| [toString](#toString--) | Devuelve una cadena que representa el objeto actual. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - Borde posterior del rectángulo de asignación del último hijo alineado con el del rectángulo de contenido de la celda de tabla.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - Borde anterior del rectángulo de asignación del primer hijo alineado con el del rectángulo de contenido de la celda de tabla.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - Los hijos están alineados con ambos bordes, anterior y posterior, del rectángulo de contenido de la celda de tabla. El primer hijo se coloca como se describe para Before y el último hijo como se describe para After, con un espaciado igual entre los hijos. Si solo hay un hijo, se alineará únicamente con el borde anterior, como en Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle- Los hijos centrados dentro de la celda de tabla. La distancia entre el borde anterior del rectángulo de asignación del primer hijo y el del rectángulo de contenido de la celda de tabla será la misma que la distancia entre el borde posterior del rectángulo de asignación del último hijo y el del rectángulo de contenido de la celda de tabla.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - El borde es una serie de segmentos de línea cortos.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - El borde es una serie de puntos.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - El borde son dos líneas sólidas. La suma de las dos líneas y el espacio entre ellas equivale al valor de BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - El borde parece estar tallado en el lienzo.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - Igual que None, excepto en cuanto a la resolución de conflictos de bordes para elementos de tabla.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - El borde hace que todo el cuadro parezca estar incrustado en el lienzo.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - Sin borde. Obliga al valor calculado de BorderThicknessto a ser 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - El borde hace que todo el cuadro parezca salir del lienzo (lo opuesto a Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - El borde parece salir del lienzo (lo opuesto a Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - El borde es un único segmento de línea.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - El estado de un campo de botón de opción o casilla de verificación.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Atributo checked: Off - El estado de un campo de botón de opción o casilla de verificación.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Atributo checked: On - El estado de un campo de botón de opción o casilla de verificación.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Atributo GlyphOrientationVertical: Auto - Especifica una orientación predeterminada para el texto, dependiendo de si es de ancho completo (tan ancho como alto).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Atributo Height: Auto - La altura del elemento se determinará por la altura intrínseca de su contenido.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Atributo InlineAlign: Center - Cada hijo centrado dentro de la celda de la tabla. La distancia entre los bordes iniciales del rectángulo de asignación del hijo y el rectángulo de contenido de la celda de la tabla será la misma que la distancia entre sus bordes finales.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Atributo InlineAlign: End - El borde final del rectángulo de asignación de cada hijo se alinea con el del rectángulo de contenido de la celda de la tabla.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Atributo InlineAlign: Start - El borde inicial del rectángulo de asignación de cada hijo se alinea con el del rectángulo de contenido de la celda de la tabla.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Atributo LineHeight: Auto - No se realizará ajuste para el valor de BaselineShift.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Atributo LineHeight: Normal - Ajusta la altura de línea para incluir cualquier valor distinto de cero especificado para BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Atributo ListNumbering: Circle - Viñeta circular abierta.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Atributo ListNumbering: Decimal - Números arábigos decimales (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Atributo ListNumbering: Disc - Viñeta circular sólida.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Atributo ListNumbering: LowerRoman - Numerales romanos en minúscula (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Atributo ListNumbering: None - Sin numeración automática; los elementos Lbl (si están presentes) contienen texto arbitrario que no está sujeto a ningún esquema de numeración.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Atributo ListNumbering: Square - Viñeta cuadrada sólida.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Atributo ListNumbering: UpperAlpha - Letras mayúsculas (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Atributo ListNumbering: UpperRoman - Numerales romanos en mayúscula (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Atributo Placement: Before - Colocado de modo que el borde anterior del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Atributo Placement: Block - Apilado en la dirección de progresión de bloque dentro de un área de referencia que lo contiene o del BLSE padre.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Atributo Placement: End - Colocado de modo que el borde final del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Atributo Placement: Inline - Compactado en la dirección de progresión en línea dentro de un BLSE que lo contiene.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Atributo Placement: Start - Colocado de modo que el borde inicial del rectángulo de asignación del elemento coincida con el del área de referencia más cercana que lo contiene.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Atributo Role: cb - Casilla de verificación.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Atributo Role: pb - Botón pulsador.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Atributo Role: rb - Botón de opción.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Atributo Role: tv - Campo de texto-valor.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Atributo RubyAlign: Center - El contenido debe centrarse en la dirección de progresión en línea.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Atributo RubyAlign: Distribute - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea. Sin embargo, también se insertará espacio en el borde inicial y el borde final del texto. El espaciado se distribuirá usando una proporción 1:2:1 (inicio:infix:fin). Se cambiará a una proporción 0:1:1 si el ruby aparece al inicio de una línea de texto o a una proporción 1:1:0 si el ruby aparece al final de la línea de texto.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Atributo RubyAlign: End - El contenido debe alinearse en el borde final en la dirección de progresión en línea.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Atributo RubyAlign: Justify - El contenido debe expandirse para llenar el ancho disponible en la dirección de progresión en línea.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Atributo RubyAlign: Start - El contenido debe alinearse en el borde inicial en la dirección de progresión en línea.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Atributo RubyPosition: After - El contenido RT debe alinearse a lo largo del borde posterior del elemento.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Atributo RubyPosition: Before - El contenido RT debe alinearse a lo largo del borde anterior del elemento.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Atributo RubyPosition: Inline - Los elementos RT y RP asociados deben formatearse como un comentario entre paréntesis, siguiendo al elemento RB.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Atributo RubyPosition: Warichu - Los elementos RT y RP asociados deben formatearse como un warichu, siguiendo al elemento RB.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Atributo Scope: Ambos.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Atributo Scope: Columna.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Atributo Scope: Fila.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Atributo TextAlign: Center - Centrado entre los bordes inicial y final.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Atributo TextAlign: End - Alineado con el borde final.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Atributo TextAlign: Justify - Alineado con ambos bordes inicial y final, con el espaciado interno dentro de cada línea expandido, si es necesario, para lograr tal alineación. La última (o única) línea debe alinearse solo con el borde inicial.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Atributo TextAlign: Start - Alineado con el borde inicial.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Atributo TextDecorationType: LineThrough - Una línea a través del medio del texto.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Atributo TextDecorationType: None - Sin decoración de texto.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Atributo TextDecorationType: Overline - Una línea sobre el texto.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Atributo TextDecorationType: Underline - Una línea bajo el texto.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Atributo Width: Auto - El ancho del elemento se determinará por el ancho intrínseco de su contenido.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Atributo WritingMode: LrTb - Progresión en línea de izquierda a derecha; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura occidentales.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Atributo WritingMode: RlTb - Progresión en línea de derecha a izquierda; progresión de bloque de arriba a abajo. Este es el modo de escritura típico para los sistemas de escritura árabe y hebreo.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Atributo WritingMode: TbRl - Progresión en línea de arriba a abajo; progresión de bloque de derecha a izquierda. Este es el modo de escritura típico para los sistemas de escritura chinos y japoneses.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Obtiene el nombre del atributo para la clave del atributo.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Obtiene la clave del atributo.

**Returns:**
Instancia de AttributeKey

### getName {#getName--}
```
public final String getName()
```

Obtiene el valor del nombre del atributo.

**Returns:**
valor String

### toString {#toString--}
```
public String toString()
```

Devuelve una cadena que representa el objeto actual.

**Returns:**
Cadena que representa el objeto actual.
