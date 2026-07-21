---
title: "Constructor System::IO::StreamReader::StreamReader"
linktitle: "StreamReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::IO::StreamReader::StreamReader. Construye una instancia del objeto StreamReader que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes en C++."
type: docs
weight: 100
url: /es/cpp/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente del que leer caracteres |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente del que leer caracteres |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del flujo, de lo contrario - false |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del flujo, de lo contrario - false |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del flujo, de lo contrario - false |
| bufferSize | int | El tamaño mínimo del búfer en bytes |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const System::String\& | La ruta del archivo del que leer caracteres |

## Ver también

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, bool) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const System::String\& | La ruta del archivo del que leer caracteres |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del archivo, de lo contrario - false |

## Ver también

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const System::String\& | La ruta del archivo del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const System::String\& | La ruta del archivo del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del archivo, de lo contrario - false |

## Ver también

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor


Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si debe habilitarse la detección de marcas de orden de bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const System::String\& | La ruta del archivo del que leer caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |
| detectEncodingFromByteOrderMarks | bool | True para buscar marcas de orden de bytes al inicio del archivo, de lo contrario - false |
| bufferSize | int | El tamaño mínimo del búfer en bytes |

## Ver también

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
