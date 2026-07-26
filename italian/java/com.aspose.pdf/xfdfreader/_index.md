---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Classe che esegue la lettura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /it/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Classe che esegue la lettura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Analizza il file XFDF e restituisce le informazioni come hashtable. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa le annotazioni dal file XFDF e le inserisce nel documento. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importa i valori dei campi dal file XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Analizza il file XFDF e restituisce le informazioni come hashtable.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa le annotazioni dal file XFDF e le inserisce nel documento.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importa i valori dei campi dal file XFDF.
