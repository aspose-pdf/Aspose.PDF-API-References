---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Referência da API Aspose.PDF para Java"
description: "Encapsula o resultado de uma operação que tenta extrair conteúdo não assinado de um documento PDF. Esta classe fornece informações sobre o sucesso da operação, detalhes de."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Encapsula o resultado de uma operação que tenta extrair conteúdo não assinado de um documento PDF. Esta classe fornece informações sobre o sucesso da operação, detalhes do conteúdo não assinado, uma mensagem descrevendo o resultado e o status de cobertura das assinaturas do documento.

## Métodos

| Método | Descrição |
| --- | --- |
| [getCoverage](#getCoverage--) | Obtém um valor que indica a extensão em que o documento está coberto por assinaturas digitais válidas. |
| [getMessage](#getMessage--) | Obtém uma mensagem que descreve o resultado da operação. |
| [getSuccess](#getSuccess--) | Obtém um valor que indica se a operação de recuperar conteúdo não assinado do documento foi bem-sucedida. |
| [getUnsignedContent](#getUnsignedContent--) | Obtém um conteúdo não assinado. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Obtém um valor que indica a extensão em que o documento está coberto por assinaturas digitais válidas.

**Returns:**
um valor que indica a extensão em que o documento está coberto por assinaturas digitais válidas.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Obtém uma mensagem que descreve o resultado da operação.

**Returns:**
uma mensagem que descreve o resultado da operação.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Obtém um valor que indica se a operação de recuperar conteúdo não assinado do documento foi bem-sucedida.

**Returns:**
um valor que indica se a operação de recuperar conteúdo não assinado do documento foi bem-sucedida.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Obtém um conteúdo não assinado.

**Returns:**
um conteúdo não assinado.
