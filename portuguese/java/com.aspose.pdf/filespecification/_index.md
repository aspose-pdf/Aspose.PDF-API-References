---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um arquivo incorporado."
type: docs
weight: 1510
url: /pt/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Classe que representa um arquivo incorporado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Cria uma nova especificação de arquivo vazia. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Relacionamento de arquivo associado. |
| [getCollectionItem](#getCollectionItem--) | Obtém um item da coleção da especificação de arquivo. |
| [getContents](#getContents--) | Obtém o arquivo de conteúdo. |
| [getContentsInternal](#getContentsInternal--) | Obtém o arquivo de conteúdo. |
| [getDescription](#getDescription--) | Obtém o texto associado à especificação do arquivo. |
| [getEncoding](#getEncoding--) | Obtém o formato de codificação. Valores possíveis: Zip - o arquivo está compactado com ZIP, None - o arquivo não está compactado. |
| [getEncryptedPayload](#getEncryptedPayload--) | Obtém a carga útil criptografada. |
| [getEngineDict](#getEngineDict--) | Dicionário PDF contendo informações sobre o arquivo. Apenas interno |
| [getEngineObj](#getEngineObj--) | Somente interno |
| [getFileSystem](#getFileSystem--) | Obtém o nome do sistema de arquivos. |
| [getMIMEType](#getMIMEType--) | Obtém o subtipo do arquivo incorporado |
| [getName](#getName--) | Obtém o nome da especificação do arquivo. |
| [getParams](#getParams--) | Obtém os parâmetros do arquivo. |
| [getStreamContents](#getStreamContents--) | Obtém o conteúdo do arquivo como fluxo. O conteúdo não é carregado na memória, o que permite reduzir o uso de memória. Porém, esse fluxo não suporta posicionamento nem a propriedade Length. Se precisar desses recursos, use a propriedade Contents em vez disso. |
| [getUnicodeName](#getUnicodeName--) | Obtém o nome Unicode da especificação do arquivo. |
| [getValue](#getValue-java.lang.String-) | Obtém o parâmetro específico da aplicação. |
| [isIncludeContents](#isIncludeContents--) | Se verdadeiro, o conteúdo do arquivo será incluído na especificação do arquivo. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Relacionamento de arquivo associado. |
| [setContents](#setContents-byte:A-) | Define o conteúdo do arquivo. |
| [setContents](#setContents-java.io.InputStream-) | Define o conteúdo do arquivo. |
| [setDescription](#setDescription-java.lang.String-) | Define o texto associado à especificação do arquivo. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Define o formato de codificação. Valores possíveis: Zip - o arquivo está compactado com ZIP, None - o arquivo não está compactado. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Define o nome do sistema de arquivos. |
| [setIncludeContents](#setIncludeContents-boolean-) | Se verdadeiro, o conteúdo do arquivo será incluído na especificação do arquivo. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Define o MIMEType. |
| [setName](#setName-java.lang.String-) | Define o nome da especificação do arquivo. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Define os parâmetros do arquivo. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Define o nome Unicode da especificação do arquivo. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Define o parâmetro específico da aplicação. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Cria uma nova especificação de arquivo vazia.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Cria uma nova especificação de arquivo vazia.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Relacionamento de arquivo associado.

**Returns:**
Elemento AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Obtém um item da coleção da especificação de arquivo.

**Returns:**
Instância CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtém o arquivo de conteúdo.

**Returns:**
objeto InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtém o arquivo de conteúdo.

**Returns:**
Objeto Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

Obtém o texto associado à especificação do arquivo.

**Returns:**
valor String

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Obtém o formato de codificação. Valores possíveis: Zip - o arquivo está compactado com ZIP, None - o arquivo não está compactado.

**Returns:**
valor int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Obtém a carga útil criptografada.

**Returns:**
Instância EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Dicionário PDF contendo informações sobre o arquivo. Apenas interno

**Returns:**
Objeto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Somente interno

**Returns:**
Objeto IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Obtém o nome do sistema de arquivos.

**Returns:**
valor String

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Obtém o subtipo do arquivo incorporado

**Returns:**
valor de string

### getName {#getName--}
```
public String getName()
```

Obtém o nome da especificação do arquivo.

**Returns:**
valor String

### getParams {#getParams--}
```
public FileParams getParams()
```

Obtém os parâmetros do arquivo.

**Returns:**
objeto FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Obtém o conteúdo do arquivo como fluxo. O conteúdo não é carregado na memória, o que permite reduzir o uso de memória. Porém, esse fluxo não suporta posicionamento nem a propriedade Length. Se precisar desses recursos, use a propriedade Contents em vez disso.

**Returns:**
objeto InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Obtém o nome Unicode da especificação do arquivo.

**Returns:**
valor String

### getValue {#getValue-java.lang.String-}
Obtém o parâmetro específico da aplicação.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Se verdadeiro, o conteúdo do arquivo será incluído na especificação do arquivo.

**Returns:**
valor booleano

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Relacionamento de arquivo associado.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Define o conteúdo do arquivo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de bytes |

### setContents {#setContents-java.io.InputStream-}
Define o conteúdo do arquivo.

### setDescription {#setDescription-java.lang.String-}
Define o texto associado à especificação do arquivo.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Define o formato de codificação. Valores possíveis: Zip - o arquivo está compactado com ZIP, None - o arquivo não está compactado.

### setFileSystem {#setFileSystem-java.lang.String-}
Define o nome do sistema de arquivos.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Se verdadeiro, o conteúdo do arquivo será incluído na especificação do arquivo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMIMEType {#setMIMEType-java.lang.String-}
Define o MIMEType.

### setName {#setName-java.lang.String-}
Define o nome da especificação do arquivo.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Define os parâmetros do arquivo.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Define o nome Unicode da especificação do arquivo.

### setValue {#setValue-java.lang.String-java.lang.String-}
Define o parâmetro específico da aplicação.
