---
title: TeXMemoryOutputDirectory
second_title: Aspose.PDF for Java API Reference
description: Implements fetching an output stream from memory.
type: docs
weight: 358
url: /java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.tex.ITeXOutputDirectory
```
public class TeXMemoryOutputDirectory implements ITeXOutputDirectory
```

Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like to read it afterwards from memory.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXMemoryOutputDirectory()](#TeXMemoryOutputDirectory--) | Creates new instance. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Disposes the instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile(String fileName, String[] fullName)](#getFile-java.lang.String-java.lang.String---) | Returns the stream to read from. |
| [getFile(String fileName, String[] fullName, boolean searchSubdirectories)](#getFile-java.lang.String-java.lang.String---boolean-) | Returns the stream to read from. |
| [getOutputFile(String fileName, String[] fullName)](#getOutputFile-java.lang.String-java.lang.String---) | Returns the stream to write to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXMemoryOutputDirectory() {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```


Creates new instance.

### close() {#close--}
```
public void close()
```


Disposes the instance.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFile(String fileName, String[] fullName) {#getFile-java.lang.String-java.lang.String---}
```
public final InputStream getFile(String fileName, String[] fullName)
```


Returns the stream to read from.

Without to look for a file in subdirectories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. In this implementation has no effect. |

**Returns:**
java.io.InputStream - The stream.
### getFile(String fileName, String[] fullName, boolean searchSubdirectories) {#getFile-java.lang.String-java.lang.String---boolean-}
```
public InputStream getFile(String fileName, String[] fullName, boolean searchSubdirectories)
```


Returns the stream to read from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |
| searchSubdirectories | boolean | Indicates whether to look for a file in subdirectories. In this implementation has no effect. |

**Returns:**
java.io.InputStream - The stream.
### getOutputFile(String fileName, String[] fullName) {#getOutputFile-java.lang.String-java.lang.String---}
```
public OutputStream getOutputFile(String fileName, String[] fullName)
```


Returns the stream to write to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | String value The file name. |
| fullName | java.lang.String[] | String value in array The full file name. |

**Returns:**
java.io.OutputStream - OutputStream instance
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

