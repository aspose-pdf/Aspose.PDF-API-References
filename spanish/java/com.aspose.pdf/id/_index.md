---
title: "Id"
linktitle: "Id"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa la estructura del identificador de archivo. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /es/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Representa la estructura del identificador de archivo. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Métodos

| Método | Descripción |
| --- | --- |
| [getModified](#getModified--) | Cambiando el identificador basado en el contenido del documento en el momento de su última actualización. |
| [getOriginal](#getOriginal--) | Identificador permanente basado en el contenido del documento en el momento en que fue creado originalmente. |

### getModified {#getModified--}
```
public String getModified()
```

Cambiando el identificador basado en el contenido del documento en el momento de su última actualización.

**Returns:**
valor String

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Identificador permanente basado en el contenido del documento en el momento en que fue creado originalmente.

**Returns:**
valor String
