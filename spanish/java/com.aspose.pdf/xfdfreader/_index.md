---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Clase que realiza la lectura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /es/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Clase que realiza la lectura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Analiza el archivo XFDF y devuelve la información como tabla hash. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa anotaciones del archivo XFDF y las inserta en el documento. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa valores de campos del archivo XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Analiza el archivo XFDF y devuelve la información como tabla hash.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa anotaciones del archivo XFDF y las inserta en el documento.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa valores de campos del archivo XFDF.
