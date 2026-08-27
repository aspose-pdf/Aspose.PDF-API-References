---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bellekten bir çıktı akışı almayı uygular. Örneğin, eşlik eden çıktının (günlük dosyası gibi) diske yazılmasını istemediğinizde, ancak yine de kullanmak istediğinizde bunu kullanabilirsiniz."
type: docs
weight: 4880
url: /tr/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Bellekten bir çıktı akışı almayı uygular. Örneğin, eşlik eden çıktının (günlük dosyası gibi) diske yazılmasını istemediğinizde, ancak daha sonra bellekte okuyabilmek istediğinizde kullanabilirsiniz.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Yeni bir örnek oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | Örneği serbest bırakır. @throws IOException I/O hatası oluşursa IOException istisnası fırlatılabilir. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Okunacak akışı döndürür. Alt dizinlerde dosya aramadan. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Okunacak akışı döndürür. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Yazılacak akışı döndürür. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Yeni bir örnek oluşturur.

### close {#close--}
```
public void close() throws IOException
```

Örneği serbest bırakır. @throws IOException I/O hatası oluşursa IOException istisnası fırlatılabilir.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Okunacak akışı döndürür. Alt dizinlerde dosya aramadan.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Okunacak akışı döndürür.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Yazılacak akışı döndürür.
