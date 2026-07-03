---
title: TeXMemoryOutputDirectory
second_title: Aspose.PDF for Java API Reference
description: Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like.
type: docs
weight: 4880
url: /java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like to read it afterwards from memory.

## Constructors

| Constructor | Description |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | Creates new instance. |

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Disposes the instance. @throws IOException IOException exception could be thrown if an I/O error occurs |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | Returns the stream to read from. Without to look for a file in subdirectories. |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | Returns the stream to read from. |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | Returns the stream to write to. |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

Creates new instance.

### close {#close--}
```
public void close() throws IOException
```

Disposes the instance. @throws IOException IOException exception could be thrown if an I/O error occurs

### getFile {#getFile-java.lang.String-java.lang.String:A-}
Returns the stream to read from. Without to look for a file in subdirectories.

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
Returns the stream to read from.

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
Returns the stream to write to.
