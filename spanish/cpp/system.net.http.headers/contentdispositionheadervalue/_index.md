---
title: "Clase System::Net::Http::Headers::ContentDispositionHeaderValue"
linktitle: "ContentDispositionHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::ContentDispositionHeaderValue. Representa un valor del encabezado ''Content-Disposition''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue class


Representa un valor del encabezado 'Content-Disposition'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Construye una nueva instancia. |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)(String) | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_CreationDate](./get_creationdate/)() | Obtiene la fecha de creación del archivo. |
| [get_DispositionType](./get_dispositiontype/)() | Información RTTI. |
| [get_FileName](./get_filename/)() | Obtiene un valor que determina cómo construir un nombre de archivo para almacenar la carga del mensaje. Se utiliza cuando la entidad está separada y se almacena en un archivo independiente. |
| [get_FileNameStar](./get_filenamestar/)() | Obtiene un valor que determina cómo construir nombres de archivo para almacenar la carga del mensaje. Se utiliza cuando las entidades están separadas y se almacenan en archivos independientes. |
| [get_ModificationDate](./get_modificationdate/)() | Obtiene la fecha de modificación del archivo. |
| [get_Name](./get_name/)() | Obtiene un nombre para una parte del cuerpo del contenido. |
| [get_Parameters](./get_parameters/)() | Devuelve una colección de parámetros del encabezado 'Content-Disposition'. |
| [get_ReadDate](./get_readdate/)() | Obtiene la fecha en que el archivo fue leído por última vez. |
| [get_Size](./get_size/)() | Obtiene un tamaño de archivo aproximado. |
| static [GetDispositionTypeLength](./getdispositiontypelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [ContentDispositionHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [ContentDispositionHeaderValue](./). |
| [set_CreationDate](./set_creationdate/)(Nullable\<DateTimeOffset\>) | Establece la fecha de creación del archivo. |
| [set_DispositionType](./set_dispositiontype/)(String) | Establece un tipo de disposición. |
| [set_FileName](./set_filename/)(String) | Establece un valor que determina cómo construir un nombre de archivo para almacenar la carga del mensaje. Se utiliza cuando la entidad está separada y se almacena en un archivo independiente. |
| [set_FileNameStar](./set_filenamestar/)(String) | Establece un valor que determina cómo construir nombres de archivo para almacenar la carga del mensaje. Se utiliza cuando las entidades están separadas y se almacenan en archivos independientes. |
| [set_ModificationDate](./set_modificationdate/)(Nullable\<DateTimeOffset\>) | Establece la fecha de modificación del archivo. |
| [set_Name](./set_name/)(String) | Establece un nombre para una parte del cuerpo del contenido. |
| [set_ReadDate](./set_readdate/)(Nullable\<DateTimeOffset\>) | Establece la fecha en que el archivo se leyó por última vez. |
| [set_Size](./set_size/)(Nullable\<int64_t\>) | Establece un tamaño de archivo aproximado. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [ContentDispositionHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
