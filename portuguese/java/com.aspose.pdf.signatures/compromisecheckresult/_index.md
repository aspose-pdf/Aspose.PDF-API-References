---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para verificar comprometimento de assinaturas digitais de documentos."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Representa uma classe para verificar comprometimento de assinaturas digitais de documentos.

## Campos

| Campo | Descrição |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Obtém uma coleção de assinaturas digitais que foram identificadas como comprometidas. Esta propriedade contém a lista de todas as assinaturas comprometidas detectadas no documento. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Obtém o estado de cobertura das assinaturas digitais em um documento. Se for igual a {@code SignaturesCoverage#Undefined}, então uma das assinaturas está comprometida. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indica se há alguma assinatura digital comprometida no documento. Retorna true se ao menos uma assinatura estiver comprometida; caso contrário, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Obtém uma coleção de assinaturas digitais que foram identificadas como comprometidas. Esta propriedade contém a lista de todas as assinaturas comprometidas detectadas no documento.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Obtém o estado de cobertura das assinaturas digitais em um documento. Se for igual a {@code SignaturesCoverage#Undefined}, então uma das assinaturas está comprometida.

**Returns:**
Elemento SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indica se há alguma assinatura digital comprometida no documento. Retorna true se ao menos uma assinatura estiver comprometida; caso contrário, false.

**Returns:**
valor booleano
