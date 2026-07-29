---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Referência da API Aspose.PDF para Java"
description: "O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros de formatação."
type: docs
weight: 5790
url: /pt/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros de formatação.

## Campos

| Campo | Descrição |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Este é o método mais ágil - o código personalizado deve fornecer (na propriedade WarningCallback) um manipulador especial que será chamado quando um erro de formatação for detectado. Esse manipulador pode, por exemplo, registrar ou contar erros etc e fornecerá a decisão se o processamento pode ser continuado para este ou aquele erro. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | Neste caso, a conversão será interrompida imediatamente e a exceção será lançada imediatamente após a detecção do primeiro erro de formatação. |
| [TryIgnore](#TryIgnore) | Neste caso, o conversor será instruído a tentar prosseguir com a conversão e ignorar os erros de formatação encontrados. Neste caso, o sucesso não é garantido, problemas graves podem ocorrer mais tarde no conversor, e nesse caso será lançada uma exceção com a lista de erros de formatação encontrados. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Este é o método mais ágil - o código personalizado deve fornecer (na propriedade WarningCallback) um manipulador especial que será chamado quando um erro de formatação for detectado. Esse manipulador pode, por exemplo, registrar ou contar erros etc e fornecerá a decisão se o processamento pode ser continuado para este ou aquele erro.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

Neste caso, a conversão será interrompida imediatamente e a exceção será lançada imediatamente após a detecção do primeiro erro de formatação.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

Neste caso, o conversor será instruído a tentar prosseguir com a conversão e ignorar os erros de formatação encontrados. Neste caso, o sucesso não é garantido, problemas graves podem ocorrer mais tarde no conversor, e nesse caso será lançada uma exceção com a lista de erros de formatação encontrados.
