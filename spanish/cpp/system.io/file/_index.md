---
title: "clase System::IO::File"
linktitle: "File"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "clase System::IO::File. Proporciona métodos para manipular archivos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de ella por ningún medio en C++."
type: docs
weight: 1300
url: /es/cpp/system.io/file/
---
## File class


Proporciona métodos para manipular archivos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class File
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [AppendAllLines](./appendalllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Añade cadenas de la colección de cadenas especificada al archivo especificado usando la codificación especificada, escribiendo cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas. |
| static [AppendAllText](./appendalltext/)(const String\&, const String\&, const EncodingPtr\&) | Añade la cadena especificada al archivo especificado usando la codificación especificada. |
| static [AppendText](./appendtext/)(const String\&) | Crea un objeto [StreamWriter](../streamwriter/) que añade texto al archivo especificado usando codificación UTF-8. Si el archivo especificado no existe, se crea. |
| static [Copy](./copy/)(const String\&, const String\&, bool) | Copia el archivo especificado a la ubicación especificada. Si el archivo de destino ya existe, un parámetro indica si debe sobrescribirse. |
| static [Create](./create/)(const String\&, int32_t, FileOptions) | Crea un archivo nuevo (o sobrescribe el existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificados. |
| static [CreateText](./createtext/)(const String\&) | Crea un archivo nuevo o abre el existente para escribir texto codificado en UTF-8. |
| static [Decrypt](./decrypt/)(const String\&) | NO IMPLEMENTADO. |
| static [Delete](./delete/)(const String\&) | Elimina el archivo o directorio especificado. |
| static [Encrypt](./encrypt/)(const String\&) | NO IMPLEMENTADO. |
| static [Exists](./exists/)(const String\&) | Determina si la ruta especificada hace referencia a un archivo existente. |
| static [GetAttributes](./getattributes/)(const String\&) | Devuelve los atributos de la entidad especificada. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Devuelve la hora de creación de la entidad especificada en hora local. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Devuelve la hora de creación de la entidad especificada en hora UTC. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Devuelve la hora de último acceso de la entidad especificada en hora local. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Devuelve la hora de último acceso de la entidad especificada en hora UTC. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Devuelve la hora de última escritura de la entidad especificada en hora local. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Devuelve la hora de última escritura de la entidad especificada en hora UTC. |
| static [Move](./move/)(const String\&, const String\&) | Mueve el archivo especificado a la nueva ubicación. |
| static [Open](./open/)(const String\&, FileMode) | Abre el archivo especificado en el modo especificado para lectura y escritura y sin compartir. |
| static [Open](./open/)(const String\&, FileMode, FileAccess, FileShare) | Abre el archivo especificado en el modo especificado, con el tipo de acceso y la opción de compartición especificados. |
| static [OpenRead](./openread/)(const String\&) | Abre el archivo especificado solo para lectura, en modo 'Open' con acceso compartido para lectura. |
| static [OpenText](./opentext/)(const String\&, const EncodingPtr\&) | Abre el archivo existente especificado para leer texto usando la codificación UTF-8 sin compartir. |
| static [OpenWrite](./openwrite/)(const String\&) | Abre el archivo especificado solo para escritura, en modo 'OpenOrCreate' sin compartir. |
| static [ReadAllBytes](./readallbytes/)(const String\&) | Lee el contenido del archivo binario especificado a un arreglo de bytes. |
| static [ReadAllLines](./readalllines/)(const String\&, const EncodingPtr\&) | Lee el contenido del archivo de texto especificado línea por línea a una matriz de cadenas usando la codificación de caracteres especificada. |
| static [ReadAllText](./readalltext/)(const String\&, const EncodingPtr\&) | Lee el contenido del archivo de texto especificado a un único [String](../../system/string/) objeto usando la codificación de caracteres especificada. |
| static [ReadLines](./readlines/)(const String\&, const EncodingPtr\&) | Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una sola línea del contenido del archivo. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, bool) | Reemplaza el contenido de un archivo con otro y crea una copia de seguridad del archivo reemplazado. |
| static [SetAttributes](./setattributes/)(const String\&, FileAttributes) | Establece los atributos especificados en el archivo especificado. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | NO IMPLEMENTADO. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | NO IMPLEMENTADO. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | NO IMPLEMENTADO. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | NO IMPLEMENTADO. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Establece la hora de última escritura de la entidad especificada como hora local. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Establece la hora de última escritura de la entidad especificada como hora UTC. |
| static [WriteAllBytes](./writeallbytes/)(const String\&, const ArrayPtr\<uint8_t\>\&) | Sobrescribe el archivo binario especificado y escribe los bytes especificados en él. |
| static [WriteAllLines](./writealllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas de la colección enumerable de cadenas especificada en él, cada cadena en una nueva línea, usando la codificación especificada. |
| static [WriteAllLines](./writealllines/)(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) | Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas del arreglo de cadenas especificado en él, cada cadena en una nueva línea, usando la codificación especificada. |
| static [WriteAllText](./writealltext/)(const String\&, const String\&, const EncodingPtr\&) | Crea un nuevo archivo de texto o sobrescribe el existente y escribe el contenido de la cadena especificada en él usando la codificación especificada. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valor predeterminado del número de bytes almacenados en búfer durante la lectura y escritura de un archivo. |
## Ver también

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
