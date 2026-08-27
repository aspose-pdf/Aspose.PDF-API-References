---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o resultado de um processo de validação de um certificado. A classe ValidationResult fornece informações sobre o resultado da validação de um certificado, incluindo seu."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Representa o resultado de um processo de validação de um certificado. A classe ValidationResult fornece informações sobre o resultado da validação de um certificado, incluindo seu status e uma mensagem descrevendo quaisquer problemas encontrados durante a validação.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Cria uma instância da classe {@link ValidationResult}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getMessage](#getMessage--) | Representa a mensagem associada ao resultado da validação. A propriedade Message fornece contexto adicional ou informações sobre o estado do resultado da validação. |
| [getStatus](#getStatus--) | Obtém o status do processo de validação de um certificado. A propriedade Status indica o resultado da validação do certificado. Valores possíveis são definidos na enumeração {@link ValidationStatus}, como Valid, Invalid ou Undefined. Ela fornece uma visão sobre se o certificado passou ou não nas verificações de validação. |
| [setMessage](#setMessage-java.lang.String-) | Representa a mensagem associada ao resultado da validação. A propriedade Message fornece contexto adicional ou informações sobre o estado do resultado da validação. |
| [setStatus](#setStatus-int-) | Obtém o status do processo de validação de um certificado. A propriedade Status indica o resultado da validação do certificado. Valores possíveis são definidos na enumeração {@link ValidationStatus}, como Valid, Invalid ou Undefined. Ela fornece uma visão sobre se o certificado passou ou não nas verificações de validação. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Cria uma instância da classe {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Representa a mensagem associada ao resultado da validação. A propriedade Message fornece contexto adicional ou informações sobre o estado do resultado da validação.

**Returns:**
valor String

### getStatus {#getStatus--}
```
public final int getStatus()
```

Obtém o status do processo de validação de um certificado. A propriedade Status indica o resultado da validação do certificado. Valores possíveis são definidos na enumeração {@link ValidationStatus}, como Valid, Invalid ou Undefined. Ela fornece uma visão sobre se o certificado passou ou não nas verificações de validação.

**Returns:**
Elemento ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Representa a mensagem associada ao resultado da validação. A propriedade Message fornece contexto adicional ou informações sobre o estado do resultado da validação.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Obtém o status do processo de validação de um certificado. A propriedade Status indica o resultado da validação do certificado. Valores possíveis são definidos na enumeração {@link ValidationStatus}, como Valid, Invalid ou Undefined. Ela fornece uma visão sobre se o certificado passou ou não nas verificações de validação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ValidationStatus |
