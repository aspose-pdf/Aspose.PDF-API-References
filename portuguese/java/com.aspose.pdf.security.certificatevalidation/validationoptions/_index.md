---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para validar uma assinatura digital em um documento PDF."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Representa opções para validar uma assinatura digital em um documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Cria uma instância da classe {@link ValidationOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação. Quando a propriedade é definida, a existência de uma cadeia de certificados será verificada; se estiver ausente, o resultado da verificação será {@link ValidationStatus#Undefined}, o que corresponde ao comportamento do Adobe Acrobat. Se você quiser apenas verificar o status de revogação online, defina o campo como {@code false}. O valor padrão é {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Obtém ou define a duração do tempo limite, em milissegundos, para operações relacionadas à rede durante o processo de validação. A propriedade RequestTimeout define o tempo máximo que o sistema deve aguardar por uma resposta de rede ao acessar recursos online, como status de revogação ou servidores OCSP. |
| [getValidationMethod](#getValidationMethod--) | Obtém ou define o método usado para validar um certificado. |
| [getValidationMode](#getValidationMode--) | Obtém ou define o modo de validação para assinaturas digitais em um documento PDF. A propriedade ValidationMode determina o rigor do processo de validação. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação. Quando a propriedade é definida, a existência de uma cadeia de certificados será verificada; se estiver ausente, o resultado da verificação será {@link ValidationStatus#Undefined}, o que corresponde ao comportamento do Adobe Acrobat. Se você quiser apenas verificar o status de revogação online, defina o campo como {@code false}. O valor padrão é {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Obtém ou define a duração do tempo limite, em milissegundos, para operações relacionadas à rede durante o processo de validação. A propriedade RequestTimeout define o tempo máximo que o sistema deve aguardar por uma resposta de rede ao acessar recursos online, como status de revogação ou servidores OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Obtém ou define o método usado para validar um certificado. |
| [setValidationMode](#setValidationMode-int-) | Obtém ou define o modo de validação para assinaturas digitais em um documento PDF. A propriedade ValidationMode determina o rigor do processo de validação. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Cria uma instância da classe {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação. Quando a propriedade é definida, a existência de uma cadeia de certificados será verificada; se estiver ausente, o resultado da verificação será {@link ValidationStatus#Undefined}, o que corresponde ao comportamento do Adobe Acrobat. Se você quiser apenas verificar o status de revogação online, defina o campo como {@code false}. O valor padrão é {@code false}.

**Returns:**
valor booleano

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Obtém ou define a duração do tempo limite, em milissegundos, para operações relacionadas à rede durante o processo de validação. A propriedade RequestTimeout define o tempo máximo que o sistema deve aguardar por uma resposta de rede ao acessar recursos online, como status de revogação ou servidores OCSP.

**Returns:**
valor int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Obtém ou define o método usado para validar um certificado.

**Returns:**
Elemento ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Obtém ou define o modo de validação para assinaturas digitais em um documento PDF. A propriedade ValidationMode determina o rigor do processo de validação.

**Returns:**
Elemento ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação. Quando a propriedade é definida, a existência de uma cadeia de certificados será verificada; se estiver ausente, o resultado da verificação será {@link ValidationStatus#Undefined}, o que corresponde ao comportamento do Adobe Acrobat. Se você quiser apenas verificar o status de revogação online, defina o campo como {@code false}. O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Obtém ou define a duração do tempo limite, em milissegundos, para operações relacionadas à rede durante o processo de validação. A propriedade RequestTimeout define o tempo máximo que o sistema deve aguardar por uma resposta de rede ao acessar recursos online, como status de revogação ou servidores OCSP.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Obtém ou define o método usado para validar um certificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Obtém ou define o modo de validação para assinaturas digitais em um documento PDF. A propriedade ValidationMode determina o rigor do processo de validação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ValidationMode |
