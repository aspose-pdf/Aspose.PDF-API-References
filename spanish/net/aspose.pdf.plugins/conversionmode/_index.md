---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ConversionMode de Aspose.Pdf.Plugins. Define el modo de conversión del documento de salida
type: docs
weight: 8500
url: /es/net/aspose.pdf.plugins/conversionmode/
---
## Enumeración ConversionMode

Define el modo de conversión del documento de salida.

```csharp
public enum ConversionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| TextBox | `0` | Este modo es rápido y bueno para preservar al máximo la apariencia original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada. |
| Flow | `1` | Modo de reconocimiento completo, el motor realiza agrupamiento y análisis multinivel para restaurar la intención original del autor del documento y producir un documento maximamente editable. La desventaja es que el documento de salida podría verse diferente del archivo PDF original. |
| EnhancedFlow | `2` | Un modo Flow alternativo que admite el reconocimiento de tablas. |

### Ver También

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)