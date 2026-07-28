---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Implementa la obtención de un flujo de salida desde la memoria. Puedes usarlo, por ejemplo, cuando no deseas que la salida adjunta (como un archivo de registro) se escriba en disco pero sí lo deseas."
type: docs
weight: 4880
url: /es/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implementa la obtención de un flujo de salida desde la memoria. Puedes usarlo, por ejemplo, cuando no deseas que la salida adjunta (como un archivo de registro) se escriba en disco pero te gustaría leerla después desde la memoria.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Crea una nueva instancia. |

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Descarta la instancia. @throws IOException La excepción IOException podría lanzarse si ocurre un error de E/S. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Devuelve el flujo desde el cual leer. Sin buscar un archivo en subdirectorios. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Devuelve el flujo desde el cual leer. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Devuelve el flujo al que escribir. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Crea una nueva instancia.

### close {#close--}
```
public void close() throws IOException
```

Descarta la instancia. @throws IOException La excepción IOException podría lanzarse si ocurre un error de E/S.

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Devuelve el flujo desde el cual leer. Sin buscar un archivo en subdirectorios.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Devuelve el flujo desde el cual leer.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Devuelve el flujo al que escribir.
