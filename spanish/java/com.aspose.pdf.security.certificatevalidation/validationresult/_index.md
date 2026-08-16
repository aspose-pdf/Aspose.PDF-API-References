---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el resultado de un proceso de validación de un certificado. La clase ValidationResult proporciona información sobre el resultado de validar un certificado, incluyendo su."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Representa el resultado de un proceso de validación de un certificado. La clase ValidationResult proporciona información sobre el resultado de validar un certificado, incluyendo su estado y un mensaje que describe cualquier problema encontrado durante la validación.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Crea una instancia de la clase {@link ValidationResult}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getMessage](#getMessage--) | Representa el mensaje asociado al resultado de la validación. La propiedad Message proporciona contexto adicional o información sobre el estado del resultado de la validación. |
| [getStatus](#getStatus--) | Obtiene el estado del proceso de validación de un certificado. La propiedad Status indica el resultado de la validación del certificado. Los valores posibles están definidos en la enumeración {@link ValidationStatus}, como Valid, Invalid o Undefined. Proporciona una visión de si el certificado pasó o no las comprobaciones de validación. |
| [setMessage](#setMessage-java.lang.String-) | Representa el mensaje asociado al resultado de la validación. La propiedad Message proporciona contexto adicional o información sobre el estado del resultado de la validación. |
| [setStatus](#setStatus-int-) | Obtiene el estado del proceso de validación de un certificado. La propiedad Status indica el resultado de la validación del certificado. Los valores posibles están definidos en la enumeración {@link ValidationStatus}, como Valid, Invalid o Undefined. Proporciona una visión de si el certificado pasó o no las comprobaciones de validación. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Crea una instancia de la clase {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Representa el mensaje asociado al resultado de la validación. La propiedad Message proporciona contexto adicional o información sobre el estado del resultado de la validación.

**Returns:**
valor String

### getStatus {#getStatus--}
```
public final int getStatus()
```

Obtiene el estado del proceso de validación de un certificado. La propiedad Status indica el resultado de la validación del certificado. Los valores posibles están definidos en la enumeración {@link ValidationStatus}, como Valid, Invalid o Undefined. Proporciona una visión de si el certificado pasó o no las comprobaciones de validación.

**Returns:**
Elemento ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Representa el mensaje asociado al resultado de la validación. La propiedad Message proporciona contexto adicional o información sobre el estado del resultado de la validación.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Obtiene el estado del proceso de validación de un certificado. La propiedad Status indica el resultado de la validación del certificado. Los valores posibles están definidos en la enumeración {@link ValidationStatus}, como Valid, Invalid o Undefined. Proporciona una visión de si el certificado pasó o no las comprobaciones de validación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ValidationStatus |
