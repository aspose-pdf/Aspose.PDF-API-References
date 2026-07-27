---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Referência da API Aspose.PDF para Java"
description: "Implementa a obtenção de um fluxo de saída a partir da memória. Você pode usá-lo, por exemplo, quando não deseja que a saída associada (como um arquivo de log) seja gravada em disco, mas gostaria."
type: docs
weight: 4880
url: /pt/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implementa a obtenção de um fluxo de saída a partir da memória. Você pode usá-lo, por exemplo, quando não deseja que a saída associada (como um arquivo de log) seja gravada em disco, mas gostaria de lê-la posteriormente a partir da memória.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Cria uma nova instância. |

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Descarta a instância. @throws IOException A exceção IOException pode ser lançada se ocorrer um erro de E/S. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Retorna o fluxo para leitura. Sem procurar um arquivo em subdiretórios. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Retorna o fluxo para leitura. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Retorna o fluxo para gravação. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Cria uma nova instância.

### close {#close--}
```
public void close() throws IOException
```

Descarta a instância. @throws IOException A exceção IOException pode ser lançada se ocorrer um erro de E/S.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Retorna o fluxo para leitura. Sem procurar um arquivo em subdiretórios.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Retorna o fluxo para leitura.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Retorna o fluxo para gravação.
