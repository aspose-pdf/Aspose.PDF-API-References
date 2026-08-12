---
title: "Clase Aspose::Pdf::FileSpecification"
linktitle: "FileSpecification"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::FileSpecification. Clase que representa un archivo incrustado en C++."
type: docs
weight: 5500
url: /es/cpp/aspose.pdf/filespecification/
---
## FileSpecification class


Clase que representa un archivo incrustado.

```cpp
class FileSpecification : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Elimina los contenidos. |
| [FileSpecification](./filespecification/)(const System::String\&) | Constructor para [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Constructor para la especificación de archivo. |
| [FileSpecification](./filespecification/)(const System::String\&, const System::String\&) | Constructor para [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Constructor para [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::String\&, const System::SharedPtr\<Annotations::Annotation\>\&) | Constructor para [FileSpecification](./). |
| [FileSpecification](./filespecification/)() | Crea una nueva especificación de archivo vacía. |
| [get_AFRelationship](./get_afrelationship/)() | Relación de archivo asociado. |
| [get_CollectionItem](./get_collectionitem/)() | Obtiene un elemento de colección de la especificación de archivo. |
| [get_Contents](./get_contents/)() | Obtiene el archivo de contenidos. Esta propiedad devuelve los datos cargados en memoria, lo que puede causar una excepción de falta de memoria para datos grandes. Para reducir el uso de memoria, por favor use StreamContents. |
| [get_Description](./get_description/)() | Obtiene el texto asociado con la especificación del archivo. |
| [get_Encoding](./get_encoding/)() const | Obtiene el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [get_EncryptedPayload](./get_encryptedpayload/)() | Obtiene la carga útil encriptada. |
| [get_FileSystem](./get_filesystem/)() | Obtiene el nombre del sistema de archivos. |
| [get_IncludeContents](./get_includecontents/)() const | Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo. |
| [get_MIMEType](./get_mimetype/)() | Obtiene el subtipo del archivo incrustado. |
| [get_Name](./get_name/)() | Obtiene el nombre de la especificación del archivo. |
| [get_Params](./get_params/)() | Obtiene los parámetros del archivo. |
| [get_StreamContents](./get_streamcontents/)() | Obtiene el contenido del archivo como flujo. El contenido no se carga en memoria, lo que permite reducir el uso de memoria. Pero este flujo no admite posicionamiento ni la propiedad Length. Si necesita estas funcionalidades, utilice la propiedad Contents en su lugar. |
| [get_UnicodeName](./get_unicodename/)() | Obtiene el nombre Unicode de la especificación del archivo. |
| [GetValue](./getvalue/)(const System::String\&) | Obtiene el parámetro específico de la aplicación. |
| [set_AFRelationship](./set_afrelationship/)(Aspose::Pdf::AFRelationship) | Relación de archivo asociado. |
| [set_Contents](./set_contents/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el archivo de contenido. Esta propiedad devuelve datos cargados en memoria, lo que puede causar una excepción de falta de memoria para datos grandes. Para reducir el uso de memoria, utilice StreamContents. |
| [set_Description](./set_description/)(const System::String\&) | Establece el texto asociado con la especificación del archivo. |
| [set_Encoding](./set_encoding/)(FileEncoding) | Establece el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [set_FileSystem](./set_filesystem/)(const System::String\&) | Establece el nombre del sistema de archivos. |
| [set_IncludeContents](./set_includecontents/)(bool) | Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo. |
| [set_MIMEType](./set_mimetype/)(const System::String\&) | Obtiene el subtipo del archivo incrustado. |
| [set_Name](./set_name/)(const System::String\&) | Establece el nombre de la especificación del archivo. |
| [set_Params](./set_params/)(const System::SharedPtr\<FileParams\>\&) | Obtiene los parámetros del archivo. |
| [set_UnicodeName](./set_unicodename/)(const System::String\&) | Establece el nombre Unicode de la especificación del archivo. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Establece el parámetro específico de la aplicación. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
