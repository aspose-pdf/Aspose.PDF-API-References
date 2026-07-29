---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un párrafo."
type: docs
weight: 2880
url: /es/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Representa un párrafo.

## Métodos

| Método | Descripción |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Lista de números de página en los que el párrafo continúa. Coincidirá con la página donde el párrafo comenzó si continúa en la siguiente columna de la misma página. |
| [getFragments](#getFragments--) | <p> Colección de objetos {@code TextFragment} no vacíos del párrafo. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Líneas del párrafo. Cada línea está representada por una lista de fragmentos de texto. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Puntos del polígono que describe el párrafo. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [getSecondaryPoints](#getSecondaryPoints--) | Puntos del polígono secundario que describe la continuación del párrafo. No será nulo si el párrafo continúa en la siguiente columna o página. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [getText](#getText--) | Obtiene el objeto de texto {@code string} que representa el objeto {@code MarkupParagraph}. |
| [setText](#setText-java.lang.String-) | Obtiene o establece el texto del párrafo. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Lista de números de página en los que el párrafo continúa. Coincidirá con la página donde el párrafo comenzó si continúa en la siguiente columna de la misma página.

**Returns:**
lista de Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Colección de objetos {@code TextFragment} no vacíos del párrafo. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).

**Returns:**
lista de instancias de TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Líneas del párrafo. Cada línea está representada por una lista de fragmentos de texto. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).

**Returns:**
lista de instancias de TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Puntos del polígono que describe el párrafo. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria.

**Returns:**
matriz de instancias de Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Puntos del polígono secundario que describe la continuación del párrafo. No será nulo si el párrafo continúa en la siguiente columna o página. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria.

**Returns:**
lista de Point[]

### getText {#getText--}
```
public String getText()
```

Obtiene el objeto de texto {@code string} que representa el objeto {@code MarkupParagraph}.

**Returns:**
valor String

### setText {#setText-java.lang.String-}
Obtiene o establece el texto del párrafo.
