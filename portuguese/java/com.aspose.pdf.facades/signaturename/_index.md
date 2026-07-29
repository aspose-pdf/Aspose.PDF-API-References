---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para um nome de assinatura. Representa um nome de assinatura mais preciso. Usado em vez de nomes de string. Permite apresentar assinaturas com os mesmos nomes de string."
type: docs
weight: 690
url: /pt/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Representa uma classe para um nome de assinatura. Representa um nome de assinatura mais preciso. Usado em vez de nomes de string. Permite apresentar assinaturas com os mesmos nomes de string.

## Campos

| Campo | Descrição |
| --- | --- |
| [FullName](#FullName) | Obtém o nome completo da assinatura, fornecendo um identificador único e preciso para o campo de assinatura. |
| [Name](#Name) | Obtém o nome de uma assinatura. |

## Métodos

| Método | Descrição |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina se esta instância e um objeto especificado são iguais. |
| [getSignatureDictionary](#getSignatureDictionary--) | Obtém o dicionário da assinatura. |
| [hashCode](#hashCode--) | Retorna um código hash para esta instância com base na propriedade FullName. |
| [hasSignature](#hasSignature--) | Indica se a assinatura está presente ou não. |
| [toString](#toString--) | Retorna uma representação em string da instância {@link SignatureName}, usando principalmente seu nome. |

### FullName {#FullName}
```
public final String FullName
```

Obtém o nome completo da assinatura, fornecendo um identificador único e preciso para o campo de assinatura.

### Name {#Name}
```
public final String Name
```

Obtém o nome de uma assinatura.

### equals {#equals-java.lang.Object-}
Determina se esta instância e um objeto especificado são iguais.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Obtém o dicionário da assinatura.

**Returns:**
O dicionário da assinatura ou null se não for encontrado.

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um código hash para esta instância com base na propriedade FullName.

**Returns:**
Um inteiro representando o código hash da propriedade FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Indica se a assinatura está presente ou não.

**Returns:**
valor booleano

### toString {#toString--}
```
public String toString()
```

Retorna uma representação em string da instância {@link SignatureName}, usando principalmente seu nome.

**Returns:**
Uma string representando o nome da assinatura.
