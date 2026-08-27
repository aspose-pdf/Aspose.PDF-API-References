---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de recursos externos que ocorre durante a conversão de PDF para outro formato (por exemplo, HTML)."
type: docs
weight: 4440
url: /pt/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de recursos externos que ocorre durante a conversão de PDF para outro formato (por exemplo, HTML).

## Métodos

| Método | Descrição |
| --- | --- |
| [getContentStream](#getContentStream--) | Definido pelo conversor. Representa o conteúdo binário do arquivo salvo. |
| [getResourceType](#getResourceType--) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo. |
| [getSupposedFileName](#getSupposedFileName--) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Esta bandeira deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não pelo código personalizado, mas pelo próprio código do conversor, de forma padrão para o conversor. Portanto, defini-la como true significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá-lo sozinho (tanto para salvar em algum lugar quanto para nomear o arquivo de referência). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Esta bandeira deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não pelo código personalizado, mas pelo próprio código do conversor, de forma padrão para o conversor. Portanto, defini-la como true significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá-lo sozinho (tanto para salvar em algum lugar quanto para nomear o arquivo de referência). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Definido pelo conversor. Representa o conteúdo binário do arquivo salvo.

**Returns:**
array de bytes

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo.

**Returns:**
Elemento NodeLevelResourceType @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo.

**Returns:**
valor String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Esta bandeira deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não pelo código personalizado, mas pelo próprio código do conversor, de forma padrão para o conversor. Portanto, defini-la como true significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá-lo sozinho (tanto para salvar em algum lugar quanto para nomear o arquivo de referência).

**Returns:**
valor booleano

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Esta bandeira deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não pelo código personalizado, mas pelo próprio código do conversor, de forma padrão para o conversor. Portanto, defini-la como true significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá-lo sozinho (tanto para salvar em algum lugar quanto para nomear o arquivo de referência).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| customProcessingCancelled |  | valor booleano |
