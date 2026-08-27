---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Aspose.PDF för Java API-referens"
description: "Implementerar hämtning av en utdataström från minnet. Du kan använda den, till exempel när du inte vill att den medföljande utdata (som en loggfil) ska skrivas till disk men du ändå vill."
type: docs
weight: 4880
url: /sv/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implementerar hämtning av en utdataström från minnet. Du kan använda den till exempel när du inte vill att den medföljande utdata (som en loggfil) ska skrivas till disk men du vill läsa den senare från minnet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Skapar en ny instans. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Avslutar instansen. @throws IOException IOException‑undantag kan kastas om ett I/O‑fel inträffar |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Returnerar strömmen att läsa från. Utan att leta efter en fil i underkataloger. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Returnerar strömmen att läsa från. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Returnerar strömmen att skriva till. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Skapar en ny instans.

### close {#close--}
```
public void close() throws IOException
```

Avslutar instansen. @throws IOException IOException‑undantag kan kastas om ett I/O‑fel inträffar

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Returnerar strömmen att läsa från. Utan att leta efter en fil i underkataloger.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Returnerar strömmen att läsa från.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Returnerar strömmen att skriva till.
