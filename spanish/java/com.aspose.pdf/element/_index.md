---
title: "Elemento"
linktitle: "Elemento"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el elemento base de la estructura lógica."
type: docs
weight: 1180
url: /es/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Clase que representa el elemento base de la estructura lógica.

## Métodos

| Método | Descripción |
| --- | --- |
| [getActualText](#getActualText--) | (Opcional; PDF 1.4) Texto que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos. |
| [getAlt](#getAlt--) | (Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos. |
| [getChildren](#getChildren--) | Obtiene la colección de elementos hijos. |
| [getE](#getE--) | (Opcional; PDF 1.5) La forma expandida de una abreviatura. |
| [getLang](#getLang--) | (Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde se sobrescriba por especificaciones de idioma para elementos de estructura anidados o contenido marcado. |
| [remove](#remove--) | Eliminar elemento. |
| [setActualText](#setActualText-java.lang.String-) | (Opcional; PDF 1.4) Texto que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos. |
| [setAlt](#setAlt-java.lang.String-) | (Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos. |
| [setE](#setE-java.lang.String-) | (Opcional; PDF 1.5) La forma expandida de una abreviatura. |
| [setLang](#setLang-java.lang.String-) | (Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde se sobrescriba por especificaciones de idioma para elementos de estructura anidados o contenido marcado. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Opcional; PDF 1.4) Texto que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos.

**Returns:**
Objeto String

### getAlt {#getAlt--}
```
public String getAlt()
```

(Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos.

**Returns:**
Objeto String

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Obtiene la colección de elementos hijos.

**Returns:**
Instancia de ElementCollection

### getE {#getE--}
```
public String getE()
```

(Opcional; PDF 1.5) La forma expandida de una abreviatura.

**Returns:**
Objeto String

### getLang {#getLang--}
```
public String getLang()
```

(Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde se sobrescriba por especificaciones de idioma para elementos de estructura anidados o contenido marcado.

**Returns:**
Objeto String

### remove {#remove--}
```
public final void remove()
```

Eliminar elemento.

### setActualText {#setActualText-java.lang.String-}
(Opcional; PDF 1.4) Texto que es un reemplazo exacto del elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad posible de contenido) es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos.

### setAlt {#setAlt-java.lang.String-}
(Opcional) Una descripción alternativa del elemento de estructura y sus hijos en forma legible por humanos, que es útil al extraer el contenido del documento en apoyo de la accesibilidad para usuarios con discapacidades o para otros propósitos.

### setE {#setE-java.lang.String-}
(Opcional; PDF 1.5) La forma expandida de una abreviatura.

### setLang {#setLang-java.lang.String-}
(Opcional; PDF 1.4) Un idioma que especifica la lengua natural para todo el texto en el elemento de estructura, excepto donde se sobrescriba por especificaciones de idioma para elementos de estructura anidados o contenido marcado.
