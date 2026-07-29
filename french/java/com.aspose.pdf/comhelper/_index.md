---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Fournit des méthodes pour les clients COM afin de charger un document dans Aspose.PDF. </p> <hr> <p> Utilisez la classe ComHelper pour charger un document depuis un fichier ou un flux dans un objet Document."
type: docs
weight: 760
url: /fr/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Fournit des méthodes pour les clients COM afin de charger un document dans Aspose.PDF. </p> <hr> <p> Utilisez la classe ComHelper pour charger un document depuis un fichier ou un flux dans un objet Document dans une application COM. La classe Document fournit un constructeur par défaut pour créer un nouveau document et propose également des constructeurs surchargés pour charger un document depuis un fichier ou un flux. Si vous utilisez Aspose.Words depuis une application .NET, vous pouvez utiliser directement tous les constructeurs de Document, mais si vous utilisez Aspose.PDF depuis une application COM, seul le constructeur par défaut de Document est disponible. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Il suffit de créer et de retourner un Document en utilisant {@code filename}. Identique à {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Ouvrez un document existant à partir d'un fichier en fournissant les options de conversion nécessaires pour obtenir un document PDF. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Initialisez et retournez une nouvelle instance de la classe {@code Document} pour travailler avec un document chiffré. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Initialisez une nouvelle instance de la classe {@code Document} pour travailler avec un document chiffré. |
| [openStream](#openStream-java.io.InputStream-) | Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Ouvrez et retournez un document existant à partir d'un flux en fournissant la conversion nécessaire pour obtenir un document PDF. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Il suffit de créer et de retourner un Document en utilisant {@code filename}. Identique à {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Ouvrez un document existant à partir d'un fichier en fournissant les options de conversion nécessaires pour obtenir un document PDF.

### openFile {#openFile-java.lang.String-java.lang.String-}
Initialisez et retournez une nouvelle instance de la classe {@code Document} pour travailler avec un document chiffré.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Initialisez une nouvelle instance de la classe {@code Document} pour travailler avec un document chiffré.

### openStream {#openStream-java.io.InputStream-}
Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}.

### openStream {#openStream-java.io.InputStream-boolean-}
Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Ouvrez et retournez un document existant à partir d'un flux en fournissant la conversion nécessaire pour obtenir un document PDF.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Initialisez et retournez une nouvelle instance de Document à partir du flux {@code input}.
