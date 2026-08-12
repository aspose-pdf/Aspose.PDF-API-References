---
title: "clase System::IO::DirectoryInfo"
linktitle: "DirectoryInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::DirectoryInfo. Representa una ruta del sistema de archivos, un directorio al que se refiere dicha ruta y proporciona métodos de instancia para manipular directorios. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.io/directoryinfo/
---
## DirectoryInfo class


Representa una ruta del sistema de archivos, un directorio al que se refiere dicha ruta y proporciona métodos de instancia para manipular directorios. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Create](./create/)() | Crea un directorio en la ruta representada por el objeto actual. |
| [CreateSubdirectory](./createsubdirectory/)(const String\&) | Crea subdirectorios en la ruta especificada. |
| [Delete](./delete/)() override | Elimina el directorio al que se refiere la ruta representada por el objeto actual si el directorio está vacío. |
| [Delete](./delete/)(bool) | Elimina el directorio al que se refiere la ruta representada por el objeto actual. Un parámetro especifica si el contenido del directorio debe eliminarse recursivamente cuando el directorio no está vacío. |
| [DirectoryInfo](./directoryinfo/)(const String\&) | Construye una instancia de la clase [DirectoryInfo](./) en la ruta especificada. |
| [EnumerateDirectories](./enumeratedirectories/)() | Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&) | Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&, SearchOption) | Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [EnumerateFiles](./enumeratefiles/)() | Devuelve una colección enumerable que contiene todos los archivos ubicados en el directorio representado por el objeto actual. |
| [EnumerateFiles](./enumeratefiles/)(const String\&) | Busca los archivos que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [EnumerateFiles](./enumeratefiles/)(const String\&, SearchOption) | Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&, SearchOption) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [get_Exists](./get_exists/)() override | Determina si la ruta representada por el objeto actual se refiere a un directorio existente. |
| [get_Name](./get_name/)() override | Devuelve el nombre de la entidad a la que se refiere la ruta representada por el objeto actual. |
| [get_Parent](./get_parent/)() | Devuelve un puntero compartido a un objeto [DirectoryInfo](./) que representa una ruta que hace referencia al directorio padre del directorio representado por el objeto actual. |
| [get_Root](./get_root/)() | Devuelve un puntero compartido a un objeto [DirectoryInfo](./) que representa una ruta que hace referencia al directorio raíz del directorio representado por el objeto actual. |
| [GetDirectories](./getdirectories/)() | Devuelve una matriz que contiene punteros compartidos a objetos [DirectoryInfo](./) que representan todos los directorios ubicados en el directorio representado por el objeto actual. |
| [GetDirectories](./getdirectories/)(const String\&) | Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [GetDirectories](./getdirectories/)(const String\&, SearchOption) | Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [GetFiles](./getfiles/)() | Devuelve una matriz que contiene punteros compartidos a objetos [FileInfo](../fileinfo/) que representan todos los directorios ubicados en el directorio representado por el objeto actual. |
| [GetFiles](./getfiles/)(const String\&) | Busca los archivos que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [GetFiles](./getfiles/)(const String\&, SearchOption) | Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [GetFileSystemInfos](./getfilesysteminfos/)() | Devuelve una matriz que contiene punteros compartidos a objetos [FileSystemInfo](../filesysteminfo/) que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&, SearchOption) | Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [MoveTo](./moveto/)(const String\&) | Mueve el directorio representado por el objeto actual y todo su contenido a la ubicación especificada. |
| [ToString](./tostring/)() const override | Devuelve una cadena que contiene la ruta representada por el objeto actual. |
## Ver también

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
