---
title: "System::IO::FileStream::FileStream constructor"
linktitle: "FileStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el constructor FileStream de la clase System::IO::FileStream en C++."
type: docs
weight: 100
url: /es/cpp/system.io/filestream/filestream/
---
## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Ver también

* Class [FileStream](../)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode) constructor


Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a abrir. |
| modo | FileMode | Especifica el modo en que se debe abrir el archivo. |

## Ver también

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a abrir. |
| modo | FileMode | Especifica el modo en que se debe abrir el archivo. |
| acceso | FileAccess | El tipo de acceso solicitado. |
| share | FileShare | El tipo de acceso que otros objetos [FileStream](../) tienen al archivo abierto. |
| buffer_size | int32_t | El número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| useAsync | bool | Especifica si se debe usar E/S asíncrona o E/S sincrónica. |
## Observaciones



El sistema operativo subyacente podría no soportar E/S asíncrona.

## Ver también

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a abrir. |
| modo | FileMode | Especifica el modo en que se debe abrir el archivo. |
| acceso | FileAccess | El tipo de acceso solicitado. |
| share | FileShare | El tipo de acceso que otros objetos [FileStream](../) tienen al archivo abierto. |
| buffer_size | int32_t | El número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| opciones | FileOptions | Opciones adicionales. |

## Ver también

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
