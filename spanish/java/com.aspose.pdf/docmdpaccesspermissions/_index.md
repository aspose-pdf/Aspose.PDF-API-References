---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Los permisos de acceso concedidos para este documento. Los valores válidos son: 1 - No se permiten cambios al documento; cualquier cambio al documento invalida la firma. 2 -."
type: docs
weight: 1010
url: /es/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Los permisos de acceso concedidos para este documento. Los valores válidos son: 1 - No se permiten cambios en el documento; cualquier cambio en el documento invalida la firma. 2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma. 3 - Los cambios permitidos son los mismos que para el 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma.

## Campos

| Campo | Descripción |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Los cambios permitidos son los mismos que para 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma. |
| [FillingInForms](#FillingInForms) | 2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma. |
| [NoChanges](#NoChanges) | 1 - No se permiten cambios al documento; cualquier cambio al documento invalida la firma. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Los cambios permitidos son los mismos que para 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - No se permiten cambios al documento; cualquier cambio al documento invalida la firma.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
