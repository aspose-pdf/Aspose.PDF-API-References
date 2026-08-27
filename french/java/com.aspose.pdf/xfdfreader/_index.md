---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Classe qui effectue la lecture du format XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /fr/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> Classe qui effectue la lecture du format XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | Analyse le fichier XFDF et renvoie les informations sous forme de table de hachage. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | Importe les annotations du fichier XFDF et les place dans le document. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | Importe les valeurs des champs du fichier XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
Analyse le fichier XFDF et renvoie les informations sous forme de table de hachage.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
Importe les annotations du fichier XFDF et les place dans le document.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
Importe les valeurs des champs du fichier XFDF.
