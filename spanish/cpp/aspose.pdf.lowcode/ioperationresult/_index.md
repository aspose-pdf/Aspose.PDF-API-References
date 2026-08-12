---
title: "Aspose::Pdf::LowCode::IOperationResult clase"
linktitle: "IOperationResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::IOperationResult clase. Interfaz de resultado de operación general que define los métodos comunes que el resultado de operación del plugin concreto debe implementar en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.pdf.lowcode/ioperationresult/
---
## IOperationResult class


Interfaz de resultado de operación general que define métodos comunes que el resultado de operación del plugin concreto debe implementar.

```cpp
class IOperationResult : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_Data](./get_data/)() | Obtiene datos sin procesar. |
| virtual [get_IsFile](./get_isfile/)() | Indica si el resultado es una ruta a un archivo de salida. |
| virtual [get_IsStream](./get_isstream/)() | Indica si el resultado es un flujo de salida. |
| virtual [get_IsString](./get_isstring/)() | Indica si el resultado es una cadena de texto. |
| virtual [ToFile](./tofile/)() | Intenta convertir el resultado al archivo. |
| virtual [ToStream](./tostream/)() | Intenta convertir el resultado al objeto de flujo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
