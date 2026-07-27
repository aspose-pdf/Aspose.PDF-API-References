---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Classe que realiza a leitura do formato XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /pt/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Classe que realiza a leitura do formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Analisa o arquivo XFDF e retorna as informações como hashtable. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa anotações do arquivo XFDF e as coloca no documento. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa valores de campos do arquivo XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Analisa o arquivo XFDF e retorna as informações como hashtable.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa anotações do arquivo XFDF e as coloca no documento.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa valores de campos do arquivo XFDF.
