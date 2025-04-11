---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Signatures.SignaturesCoverage. Representa o enum para o nível de cobertura fornecido por assinaturas digitais em um documento
type: docs
weight: 10110
url: /pt/net/aspose.pdf.signatures/signaturescoverage/
---
## Enumeração SignaturesCoverage

Representa o enum para o nível de cobertura fornecido por assinaturas digitais em um documento.

```csharp
public enum SignaturesCoverage
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Undefined | `0` | Indica que o estado da cobertura das assinaturas digitais no documento é indefinido. Este valor é tipicamente usado quando uma ou mais assinaturas no documento estão comprometidas ou não podem ser verificadas, impedindo uma avaliação definitiva da cobertura das assinaturas do documento. |
| EntirelySigned | `1` | Indica que o documento está totalmente coberto por assinaturas digitais. Este valor significa que todas as partes necessárias do documento foram assinadas e nenhuma assinatura está comprometida. |
| PartiallySigned | `2` | Indica que o documento está parcialmente assinado, significando que algumas, mas não todas, de suas partes estão cobertas por assinaturas digitais. Este valor é usado quando certas partes do documento permanecem não assinadas ou estão excluídas da cobertura da assinatura. |

### Veja Também

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)