---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para manejar la encapsulación de datos relacionados"
type: docs
weight: 5560
url: /es/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

Clase para manejar la encapsulación de datos relacionados

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Inicializa una nueva instancia de la clase {@code XfaParserOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBasePath](#getBasePath--) | Obtiene o establece la ruta base. Valor: La ruta base. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de analogías de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto. |
| [getPageSize](#getPageSize--) | Obtiene o establece el tamaño de la página. Valor: El tamaño de la página. |
| [getSigned](#getSigned--) | Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa será ignorado. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación que se usa para comprobar la firma. |
| [setBasePath](#setBasePath-java.net.URI-) | Obtiene o establece la ruta base. Valor: La ruta base. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de analogías de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Obtiene o establece el tamaño de la página. Valor: El tamaño de la página. |
| [setSigned](#setSigned-boolean-) | Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa será ignorado. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación que se usa para comprobar la firma. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Inicializa una nueva instancia de la clase {@code XfaParserOptions}.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Obtiene o establece la ruta base. Valor: La ruta base.

**Returns:**
Objeto URI

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de analogías de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto.

**Returns:**
valor booleano

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtiene o establece el tamaño de la página. Valor: El tamaño de la página.

**Returns:**
Objeto Dimension2D

### getSigned {#getSigned--}
```
public boolean getSigned()
```

Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa será ignorado. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación que se usa para comprobar la firma.

**Returns:**
valor booleano

### setBasePath {#setBasePath-java.net.URI-}
Obtiene o establece la ruta base. Valor: La ruta base.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de analogías de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Obtiene o establece el tamaño de la página. Valor: El tamaño de la página.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa será ignorado. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación que se usa para comprobar la firma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
