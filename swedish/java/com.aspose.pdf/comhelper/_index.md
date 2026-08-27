---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Tillhandahåller metoder för COM-klienter att ladda ett dokument i Aspose.PDF. </p> <hr> <p> Använd ComHelper-klassen för att ladda ett dokument från en fil eller ström till ett Document-objekt i."
type: docs
weight: 760
url: /sv/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Tillhandahåller metoder för COM-klienter att läsa in ett dokument i Aspose.PDF. </p> <hr> <p> Använd ComHelper-klassen för att läsa in ett dokument från en fil eller ström till ett Document-objekt i en COM-applikation. Document-klassen erbjuder en standardkonstruktor för att skapa ett nytt dokument och erbjuder även överlagrade konstruktorer för att läsa in ett dokument från en fil eller ström. Om du använder Aspose.Words från en .NET-applikation kan du använda alla Document-konstruktorer direkt, men om du använder Aspose.PDF från en COM-applikation är endast standardkonstruktorn för Document tillgänglig. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Skapa bara och returnera Document med {@code filename}. Samma som {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Öppna ett befintligt dokument från en fil och tillhandahålla nödvändiga konverteringsalternativ för att få pdf-dokument. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Initiera och returnera en ny instans av {@code Document}-klassen för att arbeta med krypterat dokument. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Initiera en ny instans av {@code Document}-klassen för att arbeta med krypterat dokument. |
| [openStream](#openStream-java.io.InputStream-) | Initiera och returnera en ny Document-instans från {@code input}-strömmen. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Initiera och returnera en ny Document-instans från {@code input}-strömmen. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Öppna och returnera ett befintligt dokument från en ström och tillhandahålla nödvändig konvertering för att få pdf-dokument. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Initiera och returnera en ny Document-instans från {@code input}-strömmen. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Initiera och returnera en ny Document-instans från {@code input}-strömmen. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Skapa bara och returnera Document med {@code filename}. Samma som {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Öppna ett befintligt dokument från en fil och tillhandahålla nödvändiga konverteringsalternativ för att få pdf-dokument.

### openFile {#openFile-java.lang.String-java.lang.String-}
Initiera och returnera en ny instans av {@code Document}-klassen för att arbeta med krypterat dokument.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Initiera en ny instans av {@code Document}-klassen för att arbeta med krypterat dokument.

### openStream {#openStream-java.io.InputStream-}
Initiera och returnera en ny Document-instans från {@code input}-strömmen.

### openStream {#openStream-java.io.InputStream-boolean-}
Initiera och returnera en ny Document-instans från {@code input}-strömmen.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Öppna och returnera ett befintligt dokument från en ström och tillhandahålla nödvändig konvertering för att få pdf-dokument.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Initiera och returnera en ny Document-instans från {@code input}-strömmen.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Initiera och returnera en ny Document-instans från {@code input}-strömmen.
