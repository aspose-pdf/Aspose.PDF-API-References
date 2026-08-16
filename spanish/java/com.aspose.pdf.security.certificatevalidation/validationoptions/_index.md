---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para validar una firma digital en un documento PDF."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Representa opciones para validar una firma digital en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Crea una instancia de la clase {@link ValidationOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. Cuando la propiedad está establecida, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será {@link ValidationStatus#Undefined}, lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en {@code false}. El valor predeterminado es {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Obtiene o establece la duración del tiempo de espera, en milisegundos, para las operaciones relacionadas con la red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o los servidores OCSP. |
| [getValidationMethod](#getValidationMethod--) | Obtiene o establece el método utilizado para validar un certificado. |
| [getValidationMode](#getValidationMode--) | Obtiene o establece el modo de validación de firmas digitales en un documento PDF. La propiedad ValidationMode determina el nivel de rigurosidad del proceso de validación. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. Cuando la propiedad está establecida, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será {@link ValidationStatus#Undefined}, lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en {@code false}. El valor predeterminado es {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Obtiene o establece la duración del tiempo de espera, en milisegundos, para las operaciones relacionadas con la red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o los servidores OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Obtiene o establece el método utilizado para validar un certificado. |
| [setValidationMode](#setValidationMode-int-) | Obtiene o establece el modo de validación de firmas digitales en un documento PDF. La propiedad ValidationMode determina el nivel de rigurosidad del proceso de validación. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Crea una instancia de la clase {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. Cuando la propiedad está establecida, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será {@link ValidationStatus#Undefined}, lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en {@code false}. El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Obtiene o establece la duración del tiempo de espera, en milisegundos, para las operaciones relacionadas con la red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o los servidores OCSP.

**Returns:**
valor int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Obtiene o establece el método utilizado para validar un certificado.

**Returns:**
Elemento ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Obtiene o establece el modo de validación de firmas digitales en un documento PDF. La propiedad ValidationMode determina el nivel de rigurosidad del proceso de validación.

**Returns:**
Elemento ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Obtiene o establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. Cuando la propiedad está establecida, se comprobará la existencia de una cadena de certificados; si está ausente, el resultado de la verificación será {@link ValidationStatus#Undefined}, lo que corresponde al comportamiento de Adobe Acrobat. Si solo desea comprobar el estado de revocación en línea, establezca el campo en {@code false}. El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Obtiene o establece la duración del tiempo de espera, en milisegundos, para las operaciones relacionadas con la red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o los servidores OCSP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Obtiene o establece el método utilizado para validar un certificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Obtiene o establece el modo de validación de firmas digitales en un documento PDF. La propiedad ValidationMode determina el nivel de rigurosidad del proceso de validación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ValidationMode |
