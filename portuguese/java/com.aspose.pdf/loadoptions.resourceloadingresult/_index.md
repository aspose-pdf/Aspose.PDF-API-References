---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Referência da API Aspose.PDF para Java"
description: "Resultado do carregamento personalizado do recurso."
type: docs
weight: 2820
url: /pt/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Resultado do carregamento personalizado do recurso.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Cria uma instância do resultado de carregamento |

## Métodos

| Método | Descrição |
| --- | --- |
| [getData](#getData--) | Dados binários carregados com carregador personalizado - devem ser definidos após o carregamento |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Às vezes, a codificação do recurso é conhecida após ou durante o carregamento. Nesse caso, o código personalizado pode fornecer ao conversor esse conhecimento por meio deste parâmetro. Você pode deixar null neste parâmetro se a codificação for desconhecida ou não for relevante. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Às vezes, é impossível carregar o recurso solicitado por algum motivo. A indisponibilidade do recurso frequentemente não leva a falhas nas conversões e o documento resultante pode ser criado mesmo assim (mas talvez com qualidade um pouco pior, sem imagens etc.). Se uma exceção ocorrer durante o carregamento, basta capturá‑la e colocá‑la neste parâmetro – às vezes essa informação é útil para o conversor ao renderizar o resultado. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Às vezes, o conhecimento sobre o tipo MIME do recurso carregado é útil para o conversor. Você pode fornecer o tipo MIME (se for conhecido após o carregamento) neste parâmetro. Por favor, deixe o parâmetro igual a null quando o tipo MIME for desconhecido ou não for necessário fornecê‑lo. |
| [isLoadingCancelled](#isLoadingCancelled--) | Às vezes, por alguns motivos, o carregamento não deve ocorrer por código personalizado. Nesse caso, defina esta flag como True. Assim, o conversor tentará usar o carregador de recursos interno padrão para obter esse resultado (como se comporta na situação em que nenhuma estratégia personalizada é fornecida). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Às vezes, a codificação do recurso é conhecida após ou durante o carregamento. Nesse caso, o código personalizado pode fornecer ao conversor esse conhecimento por meio deste parâmetro. Você pode deixar null neste parâmetro se a codificação for desconhecida ou não for relevante. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Às vezes, é impossível carregar o recurso solicitado por algum motivo. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Às vezes, por alguns motivos, o carregamento não deve ocorrer por código personalizado. Nesse caso, defina esta flag como True. Assim, o conversor tentará usar o carregador de recursos interno padrão para obter esse resultado (como se comporta na situação em que nenhuma estratégia personalizada é fornecida). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Às vezes, o conhecimento sobre o tipo MIME do recurso carregado é útil para o conversor. Você pode fornecer o tipo MIME (se for conhecido após o carregamento) neste parâmetro. Por favor, deixe o parâmetro igual a null quando o tipo MIME for desconhecido ou não for necessário fornecê‑lo. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Cria uma instância do resultado de carregamento

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dados |  | O resultado do carregamento personalizado deve ser sempre fornecido; pode ser um array de comprimento zero se for impossível obter qualquer resultado. |

### getData {#getData--}
```
public byte[] getData()
```

Dados binários carregados com carregador personalizado - devem ser definidos após o carregamento

**Returns:**
array de valores byte

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Às vezes, a codificação do recurso é conhecida após ou durante o carregamento. Nesse caso, o código personalizado pode fornecer ao conversor esse conhecimento por meio deste parâmetro. Você pode deixar null neste parâmetro se a codificação for desconhecida ou não for relevante.

**Returns:**
Instância de Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Às vezes, é impossível carregar o recurso solicitado por algum motivo. A indisponibilidade do recurso frequentemente não leva a falhas nas conversões e o documento resultante pode ser criado mesmo assim (mas talvez com qualidade um pouco pior, sem imagens etc.). Se uma exceção ocorrer durante o carregamento, basta capturá‑la e colocá‑la neste parâmetro – às vezes essa informação é útil para o conversor ao renderizar o resultado.

**Returns:**
Exceção

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Às vezes, o conhecimento sobre o tipo MIME do recurso carregado é útil para o conversor. Você pode fornecer o tipo MIME (se for conhecido após o carregamento) neste parâmetro. Por favor, deixe o parâmetro igual a null quando o tipo MIME for desconhecido ou não for necessário fornecê‑lo.

**Returns:**
valor String

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Às vezes, por alguns motivos, o carregamento não deve ocorrer por código personalizado. Nesse caso, defina esta flag como True. Assim, o conversor tentará usar o carregador de recursos interno padrão para obter esse resultado (como se comporta na situação em que nenhuma estratégia personalizada é fornecida).

**Returns:**
valor booleano

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Às vezes, a codificação do recurso é conhecida após ou durante o carregamento. Nesse caso, o código personalizado pode fornecer ao conversor esse conhecimento por meio deste parâmetro. Você pode deixar null neste parâmetro se a codificação for desconhecida ou não for relevante.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Às vezes, é impossível carregar o recurso solicitado por algum motivo.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Às vezes, por alguns motivos, o carregamento não deve ocorrer por código personalizado. Nesse caso, defina esta flag como True. Assim, o conversor tentará usar o carregador de recursos interno padrão para obter esse resultado (como se comporta na situação em que nenhuma estratégia personalizada é fornecida).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| loadingCancelled |  | valor booleano |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Às vezes, o conhecimento sobre o tipo MIME do recurso carregado é útil para o conversor. Você pode fornecer o tipo MIME (se for conhecido após o carregamento) neste parâmetro. Por favor, deixe o parâmetro igual a null quando o tipo MIME for desconhecido ou não for necessário fornecê‑lo.
