---
title: "Método System::IO::File::Create"
linktitle: "Crear"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::File::Create. Crea un archivo nuevo (o sobrescribe uno existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificadas en C++."
type: docs
weight: 500
url: /es/cpp/system.io/file/create/
---
## File::Create method


Crea un archivo nuevo (o sobrescribe el existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificados.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const String\& | La ruta del archivo a crear o sobrescribir |
| bufferSize | int32_t | El número de bytes almacenados en búfer al leer y escribir en el archivo |
| opciones | FileOptions | Especifica cómo crear o sobrescribir el archivo |

### ReturnValue

Un puntero compartido al objeto [FileStream](../../filestream/) asociado con el archivo especificado

## Ver también

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileOptions](../../fileoptions/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
