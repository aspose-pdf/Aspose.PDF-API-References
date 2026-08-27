---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um enum para o nível de cobertura fornecido por assinaturas digitais em um documento."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Representa um enum para o nível de cobertura fornecido por assinaturas digitais em um documento.

## Campos

| Campo | Descrição |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indica que o documento está totalmente coberto por assinaturas digitais. Este valor significa que todas as partes necessárias do documento foram assinadas e nenhuma assinatura está comprometida. |
| [PartiallySigned](#PartiallySigned) | Indica que o documento está parcialmente assinado, ou seja, que parte de seu conteúdo está coberto por assinaturas digitais, mas não todo. Este valor é usado quando certas partes do documento permanecem não assinadas ou são excluídas da cobertura de assinatura. |
| [Undefined](#Undefined) | Indica que o estado da cobertura das assinaturas digitais no documento é indefinido. Este valor é tipicamente usado quando uma ou mais assinaturas no documento estão comprometidas ou não podem ser verificadas, impedindo uma avaliação definitiva da cobertura de assinatura do documento. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indica que o documento está totalmente coberto por assinaturas digitais. Este valor significa que todas as partes necessárias do documento foram assinadas e nenhuma assinatura está comprometida.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indica que o documento está parcialmente assinado, ou seja, que parte de seu conteúdo está coberto por assinaturas digitais, mas não todo. Este valor é usado quando certas partes do documento permanecem não assinadas ou são excluídas da cobertura de assinatura.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indica que o estado da cobertura das assinaturas digitais no documento é indefinido. Este valor é tipicamente usado quando uma ou mais assinaturas no documento estão comprometidas ou não podem ser verificadas, impedindo uma avaliação definitiva da cobertura de assinatura do documento.
