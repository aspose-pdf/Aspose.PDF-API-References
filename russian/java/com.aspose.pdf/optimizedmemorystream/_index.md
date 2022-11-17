---
title: OptimizedMemoryStream
second_title: Aspose.PDF для справки по Java API
description: Определяет MemoryStream, который может содержать больше стандартной емкости
type: docs
weight: 236
url: /ru/java/com.aspose.pdf/optimizedmemorystream/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.IO.Stream
```
public class OptimizedMemoryStream extends System.IO.Stream
```

Определяет MemoryStream, который может содержать больше стандартной емкости
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OptimizedMemoryStream()](#OptimizedMemoryStream--) |  Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) учебный класс. |
| [OptimizedMemoryStream(int bufferSize, byte[] buffer)](#OptimizedMemoryStream-int-byte---) |  Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) класс на основе указанного массива байтов. |
| [OptimizedMemoryStream(int bufferSize)](#OptimizedMemoryStream-int-) |  Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) учебный класс. |
| [OptimizedMemoryStream(byte[] buffer)](#OptimizedMemoryStream-byte---) |  Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) класс на основе указанного массива байтов. |
## Поля

| Поле | Описание |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Значение размера буфера по умолчанию в байтах. |
| [Null](#Null) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [_synchronized(System.IO.Stream arg0)](#-synchronized-com.aspose.ms.System.IO.Stream-) |  |
| [beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [canRead()](#canRead--) | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток чтение. |
| [canSeek()](#canSeek--) | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток поиск. |
| [canTimeout()](#canTimeout--) |  |
| [canWrite()](#canWrite--) | При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток запись. |
| [close()](#close--) |  |
| [copyTo(System.IO.Stream arg0)](#copyTo-com.aspose.ms.System.IO.Stream-) |  |
| [copyTo(System.IO.Stream arg0, int arg1)](#copyTo-com.aspose.ms.System.IO.Stream-int-) |  |
| [dispose()](#dispose--) |  |
| [endRead(System.IAsyncResult arg0)](#endRead-com.aspose.ms.System.IAsyncResult-) |  |
| [endWrite(System.IAsyncResult arg0)](#endWrite-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Функция переопределена. |
| [fromJava(InputStream arg0)](#fromJava-java.io.InputStream-) |  |
| [getBufferSize()](#getBufferSize--) | Получает или задает размер базовых буферов. |
| [getClass()](#getClass--) |  |
| [getFreeOnDispose()](#getFreeOnDispose--) | Получает или задает значение, указывающее, следует ли освобождать базовые буферы при удалении. |
| [getLength()](#getLength--) | При переопределении в производном классе получает длину потока в байтах. |
| [getPosition()](#getPosition--) | При переопределении в производном классе получает или задает позицию в текущем потоке. |
| [getReadTimeout()](#getReadTimeout--) |  |
| [getWriteTimeout()](#getWriteTimeout--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | При переопределении в производном классе считывает последовательность байтов из текущего потока и перемещает позицию в потоке на число прочитанных байтов. |
| [readByte()](#readByte--) | Считывает байт из потока и перемещает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| [seek(long offset, int origin)](#seek-long-int-) | При переопределении в производном классе устанавливает позицию в текущем потоке. |
| [setBufferSize(int value)](#setBufferSize-int-) | Получает или задает размер базовых буферов. |
| [setFreeOnDispose(boolean value)](#setFreeOnDispose-boolean-) | Получает или задает значение, указывающее, следует ли освобождать базовые буферы при удалении. |
| [setLength(long value)](#setLength-long-) | При переопределении в производном классе устанавливает длину текущего потока. |
| [setPosition(long value)](#setPosition-long-) | При переопределении в производном классе получает или задает позицию в текущем потоке. |
| [setReadTimeout(int arg0)](#setReadTimeout-int-) |  |
| [setWriteTimeout(int arg0)](#setWriteTimeout-int-) |  |
| [toArray()](#toArray--) | Преобразует текущий поток в массив байтов. |
| [toInputStream()](#toInputStream--) |  |
| [toJava(System.IO.Stream arg0)](#toJava-com.aspose.ms.System.IO.Stream-) |  |
| [toOutputStream()](#toOutputStream--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | При переопределении в производном классе записывает последовательность байтов в текущий поток и сдвигает текущую позицию в этом потоке на количество записанных байтов. |
| [writeByte(byte value)](#writeByte-byte-) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| [writeTo(System.IO.Stream stream)](#writeTo-com.aspose.ms.System.IO.Stream-) | Записывает в указанный поток. |
### OptimizedMemoryStream() {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```


 Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) учебный класс.

### OptimizedMemoryStream(int bufferSize, byte[] buffer) {#OptimizedMemoryStream-int-byte---}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```


 Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) класс на основе указанного массива байтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bufferSize | int | Размер базовых буферов. |
| buffer | byte[] | Массив байтов без знака, из которого создается текущий поток. |

### OptimizedMemoryStream(int bufferSize) {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```


 Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) учебный класс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bufferSize | int | Размер базовых буферов. |

### OptimizedMemoryStream(byte[] buffer) {#OptimizedMemoryStream-byte---}
```
public OptimizedMemoryStream(byte[] buffer)
```


 Инициализирует новый экземпляр[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) класс на основе указанного массива байтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Массив байтов без знака, из которого создается текущий поток. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```


Значение размера буфера по умолчанию в байтах.

### Null {#Null}
```
public static System.IO.Stream Null
```


### _synchronized(System.IO.Stream arg0) {#-synchronized-com.aspose.ms.System.IO.Stream-}
```
public static System.IO.Stream _synchronized(System.IO.Stream arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**Возвращает:**
com.aspose.ms.System.IO.Stream
### beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Возвращает:**
com.aspose.ms.System.IAsyncResult
### beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Возвращает:**
com.aspose.ms.System.IAsyncResult
### canRead() {#canRead--}
```
public boolean canRead()
```


При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток чтение.

**Возвращает:**
boolean — true, если поток поддерживает чтение; в противном случае ложно. Ценность:
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток поиск.

**Возвращает:**
boolean - true, если поток поддерживает поиск; в противном случае ложно. Ценность:
### canTimeout() {#canTimeout--}
```
public boolean canTimeout()
```




**Возвращает:**
логический
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


При переопределении в производном классе получает значение, указывающее, поддерживает ли текущий поток запись.

**Возвращает:**
boolean — true, если поток поддерживает запись; в противном случае ложно. Ценность:
### close() {#close--}
```
public void close()
```




### copyTo(System.IO.Stream arg0) {#copyTo-com.aspose.ms.System.IO.Stream-}
```
public void copyTo(System.IO.Stream arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

### copyTo(System.IO.Stream arg0, int arg1) {#copyTo-com.aspose.ms.System.IO.Stream-int-}
```
public void copyTo(System.IO.Stream arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |
| arg1 | int |  |

### dispose() {#dispose--}
```
public void dispose()
```




### endRead(System.IAsyncResult arg0) {#endRead-com.aspose.ms.System.IAsyncResult-}
```
public int endRead(System.IAsyncResult arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

**Возвращает:**
инт
### endWrite(System.IAsyncResult arg0) {#endWrite-com.aspose.ms.System.IAsyncResult-}
```
public void endWrite(System.IAsyncResult arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### flush() {#flush--}
```
public void flush()
```


Функция переопределена.

### fromJava(InputStream arg0) {#fromJava-java.io.InputStream-}
```
public static System.IO.Stream fromJava(InputStream arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.io.InputStream |  |

**Возвращает:**
com.aspose.ms.System.IO.Stream
### getBufferSize() {#getBufferSize--}
```
public final int getBufferSize()
```


Получает или задает размер базовых буферов.

Значение: размер буферов.

**Возвращает:**
интервал - целочисленное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFreeOnDispose() {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```


Получает или задает значение, указывающее, следует ли освобождать базовые буферы при удалении.

**Возвращает:**
boolean - логическое значение
### getLength() {#getLength--}
```
public long getLength()
```


При переопределении в производном классе получает длину потока в байтах.

**Возвращает:**
long — длинное значение, представляющее длину потока в байтах. Ценность:
### getPosition() {#getPosition--}
```
public long getPosition()
```


При переопределении в производном классе получает или задает позицию в текущем потоке.

**Возвращает:**
long - Текущая позиция в потоке. Ценность:
### getReadTimeout() {#getReadTimeout--}
```
public int getReadTimeout()
```




**Возвращает:**
инт
### getWriteTimeout() {#getWriteTimeout--}
```
public int getWriteTimeout()
```




**Возвращает:**
инт
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


При переопределении в производном классе считывает последовательность байтов из текущего потока и перемещает позицию в потоке на число прочитанных байтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Массив байтов. Когда этот метод возвращает значение, буфер содержит указанный массив байтов со значениями |
| offset | int | Отсчитываемое от нуля смещение в байтах, с которого начинается сохранение данных, считанных из текущего потока. |
| count | int | Максимальное количество байтов, которые нужно прочитать из текущего потока. |

**Возвращает:**
int — общее количество байтов, прочитанных в буфер. Это может быть меньше количества запрошенных байтов, если такое количество байтов в настоящее время недоступно, или ноль (0), если достигнут конец потока.
### readByte() {#readByte--}
```
public int readByte()
```


Считывает байт из потока и перемещает позицию в потоке на один байт или возвращает -1, если в конце потока.

**Возвращает:**
int - байт или -1 если в конце потока.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


При переопределении в производном классе устанавливает позицию в текущем потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | long | Байтовое смещение относительно исходного параметра. |
| origin | int |  Значение типа[SeekOrigin](../../com.aspose.pdf/seekorigin) указывая опорную точку, используемую для получения нового положения. |

**Возвращает:**
long — новая позиция в текущем потоке.
### setBufferSize(int value) {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```


Получает или задает размер базовых буферов.

Значение: размер буферов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFreeOnDispose(boolean value) {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```


Получает или задает значение, указывающее, следует ли освобождать базовые буферы при удалении.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


При переопределении в производном классе устанавливает длину текущего потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Желаемая длина текущего потока в байтах. |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


При переопределении в производном классе получает или задает позицию в текущем потоке.

Текущая позиция в потоке. Ценность:

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### setReadTimeout(int arg0) {#setReadTimeout-int-}
```
public void setReadTimeout(int arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | int |  |

### setWriteTimeout(int arg0) {#setWriteTimeout-int-}
```
public void setWriteTimeout(int arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | int |  |

### toArray() {#toArray--}
```
public final byte[] toArray()
```


Преобразует текущий поток в массив байтов.

**Возвращает:**
байт[] - Массив байтов
### toInputStream() {#toInputStream--}
```
public InputStream toInputStream()
```




**Возвращает:**
java.io.InputStream
### toJava(System.IO.Stream arg0) {#toJava-com.aspose.ms.System.IO.Stream-}
```
public static InputStream toJava(System.IO.Stream arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**Возвращает:**
java.io.InputStream
### toOutputStream() {#toOutputStream--}
```
public OutputStream toOutputStream()
```




**Возвращает:**
java.io.OutputStream
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


При переопределении в производном классе записывает последовательность байтов в текущий поток и сдвигает текущую позицию в этом потоке на количество записанных байтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Массив байтов. Этот метод копирует количество байтов из буфера в текущий поток. |
| offset | int | Отсчитываемое от нуля смещение байтов в буфере, с которого начинается копирование байтов в текущий поток. |
| count | int | Количество байтов, которые необходимо записать в текущий поток. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Байт для записи в поток. |

### writeTo(System.IO.Stream stream) {#writeTo-com.aspose.ms.System.IO.Stream-}
```
public final void writeTo(System.IO.Stream stream)
```


Записывает в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
