---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Interfaz Aspose.Pdf.Plugins.IOperationResult. Interfaz general de resultado de operación que define métodos comunes que el resultado de operación de plugin concreto debe implementar
type: docs
weight: 8850
url: /es/net/aspose.pdf.plugins/ioperationresult/
---
## Interfaz IOperationResult

Interfaz general de resultado de operación que define métodos comunes que el resultado de operación de plugin concreto debe implementar.

```csharp
public interface IOperationResult
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Obtiene datos en bruto. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indica si el resultado es una ruta a un archivo de salida. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indica si el resultado es un flujo de salida. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indica si el resultado es una cadena de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Intenta convertir el resultado al archivo. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Intenta convertir el resultado al objeto de flujo. |

### Ver También

* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)