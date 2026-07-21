---
title: "Clase Aspose::Pdf::FileParams"
linktitle: "FileParams"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::FileParams. Define un diccionario de parámetros de archivo incrustado que debe contener información adicional específica del archivo en C++."
type: docs
weight: 5400
url: /es/cpp/aspose.pdf/fileparams/
---
## FileParams class


Define un diccionario de parámetros de archivo incrustado que debe contener información adicional específica del archivo.

```cpp
class FileParams : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FileParams](./fileparams/)(const System::SharedPtr\<FileSpecification\>\&) | Constructor de la clase [FileParams](./). |
| [get_CheckSum](./get_checksum/)() | Una cadena de 16 bytes que es la suma de verificación de los bytes del archivo incrustado sin comprimir. La suma de verificación se calcula aplicando el algoritmo estándar de resumen de mensaje MD5 a los bytes del flujo del archivo incrustado. |
| [get_CreationDate](./get_creationdate/)() | La fecha y hora en que se creó el archivo incrustado. |
| [get_ModDate](./get_moddate/)() | La fecha y hora en que se modificó por última vez el archivo incrustado. |
| [get_Size](./get_size/)() | El tamaño del archivo incrustado sin comprimir, en bytes. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | La fecha y hora en que se creó el archivo incrustado. |
| [set_ModDate](./set_moddate/)(System::DateTime) | La fecha y hora en que se modificó por última vez el archivo incrustado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
