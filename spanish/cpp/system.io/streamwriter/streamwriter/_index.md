---
title: "Constructor System::IO::StreamWriter::StreamWriter"
linktitle: "StreamWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::IO::StreamWriter::StreamWriter. Construye una instancia del objeto StreamWriter que escribe caracteres en el flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes en C++."
type: docs
weight: 100
url: /es/cpp/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente donde escribir caracteres |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente donde escribir caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si el flujo subyacente debe cerrarse cuando el objeto [StreamWriter](../) se elimina.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<Stream\>\& | El flujo subyacente donde escribir caracteres |
| encoding | const EncodingPtr\& | La codificación a usar |
| buffer_size | int | El tamaño mínimo del búfer en bytes |
| leave_open | bool | Especifica si el flujo subyacente debe permanecer abierto después de que el objeto [StreamWriter](../) actual se elimine |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo donde escribir caracteres |

## Ver también

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando la codificación y el tamaño de búfer especificados. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo donde escribir caracteres |
| añadir | bool | Especifica si los datos deben añadirse al archivo especificado (true) o si el archivo debe sobrescribirse (false) |
| encoding | const EncodingPtr\& | La codificación a usar |
| buffer_size | int | El tamaño del búfer a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo donde escribir caracteres |
| añadir | bool | Especifica si los datos deben añadirse al archivo especificado (true) o si el archivo debe sobrescribirse (false) |
| encoding | const EncodingPtr\& | La codificación a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
