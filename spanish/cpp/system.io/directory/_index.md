---
title: "Clase System::IO::Directory"
linktitle: "Directory"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::Directory. Contiene métodos para manipular directorios. Es un tipo estático sin servicios de instancia. Nunca debe crear instancias de ella por ningún medio en C++."
type: docs
weight: 1100
url: /es/cpp/system.io/directory/
---
## Directory class


Contiene métodos para manipular directorios. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Directory
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateDirectory_](./createdirectory_/)(const String\&) | Crea todos los directorios en la ruta especificada si no existen. |
| static [Delete](./delete/)(const String\&, bool) | Elimina el archivo o directorio especificado. No lanza excepciones. |
| static [EnumerateDirectories](./enumeratedirectories/)(const String\&, const String\&, SearchOption) | Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [EnumerateFiles](./enumeratefiles/)(const String\&, const String\&, SearchOption) | Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const String\&, const String\&, SearchOption) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [Exists](./exists/)(const String\&) | Determina si la ruta especificada se refiere a un directorio existente. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Devuelve la hora de creación de la entidad especificada en hora local. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Devuelve la hora de creación de la entidad especificada en hora UTC. |
| static [GetCurrentDirectory](./getcurrentdirectory/)() | Devuelve el nombre completo (incluyendo la ruta) del directorio actual. |
| static [GetDirectories](./getdirectories/)(const String\&, const String\&, SearchOption) | Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [GetDirectoryRoot](./getdirectoryroot/)(const String\&) | Devuelve el directorio raíz de la ruta especificada. |
| static [GetFiles](./getfiles/)(const String\&, const String\&, SearchOption) | Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [GetFileSystemEntries](./getfilesystementries/)(const String\&, const String\&, SearchOption) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios raíz del directorio especificado. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Devuelve la hora de último acceso de la entidad especificada en hora local. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Devuelve la hora de último acceso de la entidad especificada en hora UTC. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Devuelve la hora de última escritura de la entidad especificada en hora local. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Devuelve la hora de última escritura de la entidad especificada en hora UTC. |
| static [GetLogicalDrives](./getlogicaldrives/)() | NO IMPLEMENTADO. |
| static [GetParent](./getparent/)(const String\&) | Devuelve un puntero compartido al objeto [DirectoryInfo](../directoryinfo/) que representa el directorio padre de la entidad especificada. |
| static [Move](./move/)(const String\&, const String\&) | Mueve la entidad especificada a la nueva ubicación. Si la entidad a mover es un directorio, se traslada con todo su contenido. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | Establece la hora de creación de la entidad especificada como hora local. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | Establece la hora de creación de la entidad especificada como hora UTC. |
| static [SetCurrentDirectory](./setcurrentdirectory/)(const String\&) | Establece el directorio actual. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | Establece la hora de último acceso de la entidad especificada como hora local. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | Establece la hora de último acceso de la entidad especificada como hora UTC. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Establece la hora de última escritura de la entidad especificada como hora local. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Establece la hora de última escritura de la entidad especificada como hora UTC. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Un alias para un puntero compartido a un objeto IEnumerable que enumera un conjunto de objetos [String](../../system/string/). |
## Observaciones



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Crea cadenas que contienen rutas a directorios.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Comprueba si los directorios existen.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Imprime la información del directorio temporal.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
