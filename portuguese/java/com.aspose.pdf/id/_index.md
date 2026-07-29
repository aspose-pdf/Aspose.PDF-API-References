---
title: "Id"
linktitle: "Id"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a estrutura de identificador de arquivo. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /pt/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Representa a estrutura de identificador de arquivo. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Métodos

| Método | Descrição |
| --- | --- |
| [getModified](#getModified--) | Alterando o identificador com base no conteúdo do documento no momento da última atualização. |
| [getOriginal](#getOriginal--) | Identificador permanente com base no conteúdo do documento no momento em que foi criado originalmente. |

### getModified {#getModified--}
```
public String getModified()
```

Alterando o identificador com base no conteúdo do documento no momento da última atualização.

**Returns:**
valor String

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Identificador permanente com base no conteúdo do documento no momento em que foi criado originalmente.

**Returns:**
valor String
