---
title: "Clase System::IO::FileInfo"
linktitle: "FileInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::FileInfo. Representa una ruta a un archivo y un archivo referenciado por esa ruta y proporciona métodos para manipularlo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.io/fileinfo/
---
## FileInfo class


Representa una ruta a un archivo y un archivo referenciado por esa ruta y proporciona métodos para manipularlo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AppendText](./appendtext/)() | Abre un archivo representado por el objeto actual para escribir texto usando codificación UTF-8, en modo 'Append' sin compartir. |
| [CopyTo](./copyto/)(const String\&) | Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla. |
| [CopyTo](./copyto/)(const String\&, bool) | Copia el archivo representado por el objeto actual a la ubicación especificada. Un parámetro indica si el archivo de destino existente debe sobrescribirse. |
| [Create](./create/)() | Crea un archivo en la ubicación especificada por la ruta representada por el objeto actual y lo abre para lectura y escritura, en modo truncado y sin compartir. |
| [CreateText](./createtext/)() | Crea un archivo en la ubicación especificada por la ruta representada por el objeto actual y lo abre para escribir texto usando codificación UTF-8 sin compartir. |
| [Decrypt](./decrypt/)() | NO IMPLEMENTADO. |
| [Delete](./delete/)() override | Elimina el archivo representado por el objeto actual. |
| [Encrypt](./encrypt/)() | NO IMPLEMENTADO. |
| [FileInfo](./fileinfo/)(const String\&) | Construye una nueva instancia de la clase [FileInfo](./) que representa el archivo especificado. |
| [get_Directory](./get_directory/)() | Devuelve un objeto [DirectoryInfo](../directoryinfo/) que representa un directorio en el que se encuentra el archivo representado por el objeto actual. |
| [get_DirectoryName](./get_directoryname/)() | Devuelve el nombre completo del directorio en el que se encuentra el archivo representado por el objeto actual. |
| [get_Exists](./get_exists/)() override | Devuelve un valor que indica si el archivo existe. |
| [get_IsReadOnly](./get_isreadonly/)() | Devuelve un valor que indica si el atributo ReadOnly está establecido. |
| [get_Length](./get_length/)() | Devuelve el tamaño del archivo en bytes. |
| [get_Name](./get_name/)() override | Devuelve el nombre del archivo. |
| [MoveTo](./moveto/)(const String\&) | Mueve el archivo representado por el objeto actual a la ubicación especificada. |
| [Open](./open/)(FileMode) | Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura y sin compartir. |
| [Open](./open/)(FileMode, FileAccess) | Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y sin compartir. |
| [Open](./open/)(FileMode, FileAccess, FileShare) | Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y la opción de compartir. |
| [OpenRead](./openread/)() | Abre un archivo representado por el objeto actual solo para lectura, en modo 'Open' con acceso compartido para lectura. |
| [OpenText](./opentext/)() | Abre el archivo existente en la ubicación especificada por la ruta representada por el objeto actual para leer texto usando codificación UTF-8 sin compartir. |
| [OpenWrite](./openwrite/)() | Abre un archivo representado por el objeto actual solo para escritura, en modo 'OpenOrCreate' sin compartir. |
| [Replace](./replace/)(const String\&, const String\&) | Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](./) actual y crea una copia de seguridad del archivo reemplazado. |
| [Replace](./replace/)(const String\&, const String\&, bool) | Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](./) actual y crea una copia de seguridad del archivo reemplazado. |
| [set_IsReadOnly](./set_isreadonly/)(bool) | Establece o elimina el atributo ReadOnly del archivo. |
| [ToString](./tostring/)() const override | Devuelve una ruta representada por el objeto actual. |
## Ver también

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
