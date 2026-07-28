---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Encapsula elementos de contenido no firmado extraídos de un documento PDF. Esta clase proporciona acceso a páginas, campos de formulario, XForms y anotaciones que forman parte de lo no firmado."
type: docs
weight: 50
url: /es/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Encapsula los elementos de contenido no firmado extraídos de un documento PDF. Esta clase brinda acceso a páginas, campos de formulario, XForms y anotaciones que forman parte del contenido no firmado dentro del documento.

## Métodos

| Método | Descripción |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Obtiene un diccionario de anotaciones modificadas que pueden haber sido cambiadas o añadidas. |
| [getForms](#getForms--) | Obtiene campos de formulario que han sido modificados o añadidos de forma incremental. |
| [getPages](#getPages--) | Obtiene una lista de páginas cuyo contenido no está firmado o ha sido cambiado incrementalmente. La página se considera modificada y los XForms no se verifican y no aparecen en la lista de XForms. |
| [getXForms](#getXForms--) | Obtiene un diccionario de objetos XForm modificados que pueden haber cambiado, aunque la propia página no haya cambiado (no está en la lista de Pages). |
| [setXForms](#setXForms-java.util.HashMap-) | Un diccionario de objetos XForm modificados que pueden haber cambiado, aunque la propia página no haya cambiado (no está en la lista de Pages). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Obtiene un diccionario de anotaciones modificadas que pueden haber sido cambiadas o añadidas.

**Returns:**
un diccionario de anotaciones modificadas que pueden haber cambiado o añadido.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Obtiene campos de formulario que han sido modificados o añadidos de forma incremental.

**Returns:**
campos de formulario que han sido cambiados o añadidos incrementalmente.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Obtiene una lista de páginas cuyo contenido no está firmado o ha sido cambiado incrementalmente. La página se considera modificada y los XForms no se verifican y no aparecen en la lista de XForms.

**Returns:**
una lista de páginas cuyo contenido no está firmado o ha sido cambiado incrementalmente.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Obtiene un diccionario de objetos XForm modificados que pueden haber cambiado, aunque la propia página no haya cambiado (no está en la lista de Pages).

**Returns:**
un diccionario de objetos XForm modificados que pueden haber cambiado, aunque la propia página no haya cambiado (no está en la lista de Pages).

### setXForms {#setXForms-java.util.HashMap-}
Un diccionario de objetos XForm modificados que pueden haber cambiado, aunque la propia página no haya cambiado (no está en la lista de Pages).
