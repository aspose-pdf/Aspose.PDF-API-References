---
title: "Clase System::IO::Path"
linktitle: "Ruta"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::Path. Proporciona métodos para manipular rutas. Este es un tipo estático sin servicios de instancia. Nunca deberías crear instancias de ella por ningún medio en C++."
type: docs
weight: 1900
url: /es/cpp/system.io/path/
---
## Path class


Proporciona métodos para manipular rutas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Path
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Cambia la extensión en la ruta de archivo especificada. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Determina si la ruta especificada es válida comprobando si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Combina los segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [Combine](./combine/)(const String\&, const String\&) | Combina dos segmentos de ruta especificados en una única ruta insertando el carácter separador de directorio entre los segmentos si es necesario. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Combina tres segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Combina cuatro segmentos de ruta especificados en una única ruta insertando caracteres separadores de directorio entre los segmentos si es necesario. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Devuelve el nombre del directorio referenciado por la ruta especificada. |
| static [GetExtension](./getextension/)(const String\&) | Devuelve la extensión del archivo referenciado por la ruta especificada. |
| static [GetFileName](./getfilename/)(const String\&) | Devuelve el nombre del archivo referenciado por la ruta especificada. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Devuelve el nombre sin extensión del archivo referenciado por la ruta especificada. |
| static [GetFullPath](./getfullpath/)(const String\&) | Convierte la ruta especificada en una ruta absoluta. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Devuelve una matriz que contiene los caracteres que no están permitidos en los nombres de archivos. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Devuelve una matriz que contiene los caracteres que no están permitidos en los nombres de rutas. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Devuelve el directorio raíz de la ruta especificada. |
| static [GetRandomFileName](./getrandomfilename/)() | Devuelve un nombre de archivo generado aleatoriamente. |
| static [GetTempFileName_](./gettempfilename_/)() | Crea un nuevo archivo con un nombre único y devuelve una ruta completa hacia él. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Crea un nuevo archivo con un nombre único y devuelve una ruta completa hacia él. Es sinónimo del método [GetTempFileName_()](./gettempfilename_/). |
| static [GetTempPath](./gettemppath/)() | Devuelve la ruta del directorio temporal del usuario actual. |
| static [HasExtension](./hasextension/)(const String\&) | Determina si la ruta especificada hace referencia a un archivo con extensión. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Determina si la ruta especificada contiene una raíz. |
| static [NormalizePath](./normalizepath/)(const String\&) | Normaliza la ruta especificada. |
| static [ToBoost](./toboost/)(const String\&) | Devuelve una instancia de la clase boost::filesystem::path que representa la ruta especificada. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Devuelve una representación en cadena del objeto path de Boost especificado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Un carácter alternativo usado para separar los niveles de directorio en una ruta. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Un carácter usado para separar los niveles de directorio en una ruta. |
| static [PathSeparator](./pathseparator/) | Un carácter separador usado para separar cadenas de rutas en variables de entorno. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Un carácter separador de volumen. |
## Observaciones



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Generar un nombre de archivo aleatorio.
  auto filename = Path::GetRandomFileName();

  // Imprimir información sobre el nombre de archivo.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
