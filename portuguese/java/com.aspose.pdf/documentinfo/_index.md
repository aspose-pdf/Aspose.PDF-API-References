---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa as metainformações de um documento PDF."
type: docs
weight: 1160
url: /pt/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Representa as metainformações de um documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Inicialize a instância de DocumentInfo. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Adiciona um elemento com a chave e o valor especificados à coleção. |
| [clear](#clear--) | Limpa as informações do documento. |
| [clearCustomData](#clearCustomData--) | Limpa apenas os dados personalizados, mantendo todos os outros valores predefinidos (Title, Author, etc.). |
| [get_Item](#get_Item-java.lang.String-) | Obtém o valor associado à chave especificada. |
| [getAuthor](#getAuthor--) | Obtém o autor do documento. |
| [getCreationDate](#getCreationDate--) | Obtém a data de criação do documento. |
| [getCreationTimeZone](#getCreationTimeZone--) | Fuso horário da data de criação em milissegundos. |
| [getCreator](#getCreator--) | Obtém o criador do documento. |
| [getKeywords](#getKeywords--) | Obtém as palavras‑chave do documento. |
| [getModDate](#getModDate--) | Obtém a data de modificação do documento. |
| [getModTimeZone](#getModTimeZone--) | Fuso horário da data de modificação. |
| [getProducer](#getProducer--) | Obtém o produtor do documento. |
| [getSubject](#getSubject--) | Obtém o assunto do documento. |
| [getTitle](#getTitle--) | Obtém o título do documento. |
| [getTrapped](#getTrapped--) | Obtém o sinalizador trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Determina se a chave é predefinida (Title, Author, etc.), não personalizada. |
| [remove](#remove-java.lang.String-) | Remove o elemento com a chave especificada da coleção. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Define o valor associado à chave especificada. |
| [setAuthor](#setAuthor-java.lang.String-) | Define o autor do documento. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Define a data de criação do documento. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Fuso horário da data de criação em milissegundos. |
| [setCreator](#setCreator-java.lang.String-) | Define o criador do documento. |
| [setKeywords](#setKeywords-java.lang.String-) | Define as palavras‑chave do documento. |
| [setModDate](#setModDate-java.util.Date-) | Define a data de modificação do documento. |
| [setModTimeZone](#setModTimeZone-double-) | Fuso horário da data de modificação. |
| [setProducer](#setProducer-java.lang.String-) | Define o produtor do documento. |
| [setSubject](#setSubject-java.lang.String-) | Define o assunto do documento. |
| [setTitle](#setTitle-java.lang.String-) | Define o título do documento. |
| [setTrapped](#setTrapped-java.lang.String-) | Define a bandeira de captura. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Inicialize a instância de DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
Adiciona um elemento com a chave e o valor especificados à coleção.

### clear {#clear--}
```
public void clear()
```

Limpa as informações do documento.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Limpa apenas os dados personalizados, mantendo todos os outros valores predefinidos (Title, Author, etc.).

### get_Item {#get_Item-java.lang.String-}
Obtém o valor associado à chave especificada.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtém o autor do documento.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtém a data de criação do documento.

**Returns:**
Objeto Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Fuso horário da data de criação em milissegundos.

**Returns:**
valor double

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtém o criador do documento.

**Returns:**
valor String

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtém as palavras‑chave do documento.

**Returns:**
valor String

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtém a data de modificação do documento.

**Returns:**
Objeto Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Fuso horário da data de modificação.

**Returns:**
valor double

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtém o produtor do documento.

**Returns:**
valor String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtém o assunto do documento.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém o título do documento.

**Returns:**
valor String

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Obtém o sinalizador trapped.

**Returns:**
valor String

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Determina se a chave é predefinida (Title, Author, etc.), não personalizada.

### remove {#remove-java.lang.String-}
Remove o elemento com a chave especificada da coleção.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Define o valor associado à chave especificada.

### setAuthor {#setAuthor-java.lang.String-}
Define o autor do documento.

### setCreationDate {#setCreationDate-java.util.Date-}
Define a data de criação do documento.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Fuso horário da data de criação em milissegundos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | em milissegundos |

### setCreator {#setCreator-java.lang.String-}
Define o criador do documento.

### setKeywords {#setKeywords-java.lang.String-}
Define as palavras‑chave do documento.

### setModDate {#setModDate-java.util.Date-}
Define a data de modificação do documento.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Fuso horário da data de modificação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setProducer {#setProducer-java.lang.String-}
Define o produtor do documento.

### setSubject {#setSubject-java.lang.String-}
Define o assunto do documento.

### setTitle {#setTitle-java.lang.String-}
Define o título do documento.

### setTrapped {#setTrapped-java.lang.String-}
Define a bandeira de captura.
