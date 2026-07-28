---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un rectángulo."
type: docs
weight: 4100
url: /es/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Clase que representa un rectángulo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Constructor de Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Constructor de Rectangle. |

## Métodos

| Método | Descripción |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Interseca rectángulos. Método obsoleto. Por favor, use Intersect en su lugar. |
| [center](#center--) | Devuelve las coordenadas del centro del rectángulo. |
| [clone](#clone--) | Clona el objeto Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Determina si el punto dado está dentro del rectángulo. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Determina si el punto dado está dentro del rectángulo. |
| [containsLine](#containsLine-double-double-double-double-) | Determina si el rectángulo contiene una línea representada por dos puntos. |
| [containsPoint](#containsPoint-double-double-) | Determina si el punto dado está contenido dentro del rectángulo. |
| [deepClone](#deepClone--) | Clona el objeto Rectangle. |
| [equals](#equals-java.lang.Object-) | Comprueba si los rectángulos son iguales, es decir, tienen la misma posición y tamaño. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Calcula el área del rectángulo. |
| [getEmpty](#getEmpty--) | Obtiene un rectángulo vacío |
| [getHeight](#getHeight--) | Obtiene la altura del rectángulo. |
| [getLLX](#getLLX--) | Obtiene la coordenada X de la esquina inferior izquierda. |
| [getLLY](#getLLY--) | Obtiene la coordenada Y de la esquina inferior izquierda. |
| [getTrivial](#getTrivial--) | Inicializa un rectángulo trivial, es decir, un rectángulo con posición y tamaño cero. |
| [getURX](#getURX--) | Obtiene la coordenada X de la esquina superior derecha. |
| [getURY](#getURY--) | Obtiene la coordenada Y de la esquina superior derecha. |
| [getWidth](#getWidth--) | Obtiene el ancho del rectángulo. |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Interseca dos rectángulos. |
| [isEmpty](#isEmpty--) | Comprueba si el rectángulo está vacío. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Comprueba que este rectángulo incluye a otro rectángulo completo. Es decir, el otro rectángulo está dentro de este rectángulo. La diferencia con el método IsIntersect es que IsIntersect será verdadero para rectángulos parcialmente intersectados, pero IsInclude será falso. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Determina si este rectángulo intersecta con otro rectángulo. |
| [isPoint](#isPoint--) | Comprueba si el rectángulo es un punto, es decir, LLX es igual a URX y LLY es igual a URY. |
| [isTrivial](#isTrivial--) | Comprueba si el rectángulo es trivial, es decir, tiene tamaño y posición cero. |
| [join](#join-com.aspose.pdf.Rectangle-) | Une rectángulos. |
| [moveBy](#moveBy-double-double-) | Desplaza el rectángulo por los deltas especificados. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Comprueba si los rectángulos son casi iguales, es decir, tienen posición y tamaños casi idénticos (hasta delta). |
| [parse](#parse-java.lang.String-) | Intenta analizar la cadena y extraer de ella los componentes del rectángulo llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Rota el rectángulo por el ángulo especificado. |
| [rotateAngle](#rotateAngle-int-) | Rota el rectángulo por el ángulo especificado. |
| [setLLX](#setLLX-double-) | Establece la coordenada X de la esquina inferior izquierda. |
| [setLLY](#setLLY-double-) | Establece la coordenada Y de la esquina inferior izquierda. |
| [setURX](#setURX-double-) | Establece la coordenada X de la esquina superior derecha. |
| [setURY](#setURY-double-) | Establece la coordenada Y de la esquina superior derecha. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Convierte el rectángulo en una matriz de puntos ("QuadPoints"). |
| [toRect](#toRect--) | Convierte el rectángulo a una instancia de System.Drawing.Rectangle. Las posiciones y el tamaño en coma flotante se truncan. |
| [toString](#toString--) | Obtiene la representación en cadena del rectángulo. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Constructor de Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| llx |  | X de la esquina inferior izquierda. |
| lly |  | Y de la esquina inferior izquierda. |
| urx |  | X de la esquina superior derecha. |
| ury |  | Y de la esquina superior derecha. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Constructor de Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| llx |  | X de la esquina inferior izquierda. |
| lly |  | Y de la esquina inferior izquierda. |
| urx |  | X de la esquina superior derecha. |
| ury |  | Y de la esquina superior derecha. |
| normalizeCoordinates |  | Normaliza las coordenadas del rectángulo. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Interseca rectángulos. Método obsoleto. Por favor, use Intersect en su lugar.

### center {#center--}
```
public Point center()
```

Devuelve las coordenadas del centro del rectángulo.

**Returns:**
Punto que es el centro del rectángulo.

### clone {#clone--}
```
public Rectangle clone()
```

Clona el objeto Rectangle.

**Returns:**
Clonar objeto.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Determina si el punto dado está dentro del rectángulo.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Determina si el punto dado está dentro del rectángulo.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Determina si el rectángulo contiene una línea representada por dos puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 |  | La coordenada X del punto de inicio de la línea. |
| y1 |  | La coordenada Y del punto de inicio de la línea. |
| x2 |  | La coordenada X del punto final de la línea. |
| y2 |  | La coordenada Y del punto final de la línea. |

**Returns:**
{@code true} si el rectángulo contiene la línea; de lo contrario, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Determina si el punto dado está contenido dentro del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Coordenada X del punto. |
| y |  | Coordenada Y del punto. |

**Returns:**
{@code true} si el punto está contenido dentro del rectángulo; de lo contrario, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Clona el objeto Rectangle.

**Returns:**
Clonar objeto.

### equals {#equals-java.lang.Object-}
Comprueba si los rectángulos son iguales, es decir, tienen la misma posición y tamaño.

### fromRect {#fromRect-java.awt.Rectangle-}
Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Inicializa un nuevo rectángulo a partir de la instancia dada de System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Calcula el área del rectángulo.

**Returns:**
El área del rectángulo como un double, calculada multiplicando el ancho y la altura.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Obtiene un rectángulo vacío

**Returns:**
nuevo objeto Rectangle

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene la altura del rectángulo.

**Returns:**
valor double

### getLLX {#getLLX--}
```
public double getLLX()
```

Obtiene la coordenada X de la esquina inferior izquierda.

**Returns:**
valor double

### getLLY {#getLLY--}
```
public double getLLY()
```

Obtiene la coordenada Y de la esquina inferior izquierda.

**Returns:**
valor double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Inicializa un rectángulo trivial, es decir, un rectángulo con posición y tamaño cero.

**Returns:**
nuevo objeto Rectangle

### getURX {#getURX--}
```
public double getURX()
```

Obtiene la coordenada X de la esquina superior derecha.

**Returns:**
valor double

### getURY {#getURY--}
```
public double getURY()
```

Obtiene la coordenada Y de la esquina superior derecha.

**Returns:**
valor double

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho del rectángulo.

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Interseca dos rectángulos.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Comprueba si el rectángulo está vacío.

**Returns:**
valor booleano

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Comprueba que este rectángulo incluye a otro rectángulo completo. Es decir, el otro rectángulo está dentro de este rectángulo. La diferencia con el método IsIntersect es que IsIntersect será verdadero para rectángulos parcialmente intersectados, pero IsInclude será falso.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Determina si este rectángulo intersecta con otro rectángulo.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Comprueba si el rectángulo es un punto, es decir, LLX es igual a URX y LLY es igual a URY.

**Returns:**
valor booleano

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Comprueba si el rectángulo es trivial, es decir, tiene tamaño y posición cero.

**Returns:**
valor booleano

### join {#join-com.aspose.pdf.Rectangle-}
Une rectángulos.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Desplaza el rectángulo por los deltas especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx |  | Valor del desplazamiento por el eje X. |
| dy |  | Valor del desplazamiento por el eje Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Comprueba si los rectángulos son casi iguales, es decir, tienen posición y tamaños casi idénticos (hasta delta).

### parse {#parse-java.lang.String-}
Intenta analizar la cadena y extraer de ella los componentes del rectángulo llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Rota el rectángulo por el ángulo especificado.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Rota el rectángulo por el ángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle |  | Ángulo de rotación en grados entre 0 y 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Establece la coordenada X de la esquina inferior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Establece la coordenada Y de la esquina inferior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Establece la coordenada X de la esquina superior derecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Establece la coordenada Y de la esquina superior derecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Convierte el rectángulo en una matriz de puntos ("QuadPoints").

**Returns:**
Arreglo de puntos.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Convierte el rectángulo a una instancia de System.Drawing.Rectangle. Las posiciones y el tamaño en coma flotante se truncan.

**Returns:**
Resultado de la conversión.

### toString {#toString--}
```
public String toString()
```

Obtiene la representación en cadena del rectángulo.

**Returns:**
La cadena tiene el formato llx,lly,urx,ury.
