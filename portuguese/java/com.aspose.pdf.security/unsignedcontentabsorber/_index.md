---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para extrair conteúdo não assinado de um arquivo PDF gerenciado por assinaturas digitais."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Representa uma classe para extrair conteúdo não assinado de um arquivo PDF gerenciado por assinaturas digitais.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Representa uma classe usada para processar conteúdo não assinado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Tenta recuperar o conteúdo não assinado do documento associado. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Representa uma classe usada para processar conteúdo não assinado.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Tenta recuperar o conteúdo não assinado do documento associado.

**Returns:**
Um objeto {@link UnsignedContentAbsorber.Result} contendo detalhes sobre o conteúdo não assinado, a cobertura das assinaturas digitais, o status de sucesso da operação e uma mensagem informativa.
