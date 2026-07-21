---
title: "Aspose::Pdf::WarningType enumeración"
linktitle: "WarningType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::WarningType enumeración. Enumeración que representa el tipo de advertencia en C++."
type: docs
weight: 27300
url: /es/cpp/aspose.pdf/warningtype/
---
## WarningType enum


El enumerado representa el tipo de advertencia.

```cpp
enum class WarningType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SourceFileCorruption | 0 | El archivo está corrupto. |
| DataLoss | 1 | El texto, gráfico, imagen u otros datos faltan completamente, ya sea del árbol del documento después de la carga o del documento creado después de guardar. |
| MajorFormattingLoss | 2 | Pérdidas de formato importantes en comparación con el documento original. Esto es para casos en los que la pérdida de formato es sustancial pero los datos aún están presentes. |
| MinorFormattingLoss | 3 | Pérdidas de formato menores en comparación con el documento original. Esto es para pérdidas menores de fidelidad. |
| CompatibilityIssue | 4 | Problema conocido que impedirá que el documento sea abierto por ciertos agentes de usuario, o versiones anteriores de agentes de usuario. |
| InvalidInputStreamType | 5 | Tipo de flujo de entrada no válido. |
| UnexpectedContent | 99 | El archivo tiene contenido inesperado. |

## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
