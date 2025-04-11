---
title: Class BasicSetColorAndPatternOperator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.BasicSetColorAndPatternOperator. Operador base para todos los operadores de Establecer Color
type: docs
weight: 7150
url: /es/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## Clase BasicSetColorAndPatternOperator

Operador base para todos los operadores de Establecer Color.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Obtiene el componente rojo del color |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Obtiene el componente cian del color CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtiene el arreglo de componentes de color. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Obtiene el componente verde del color |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtiene el componente negro del color gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de página. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Obtiene el componente negro del color CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Obtiene el componente magenta del color CMYK. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Obtiene el Nombre del Patrón. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Obtiene el componente rojo del color |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Obtiene el componente amarillo del color CMYK. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Acepta el visitante IOperatorSelector que proporciona el procesamiento de operadores. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Retorna el color especificado por el operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Retorna el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Ver También

* clase [BasicSetColorOperator](../basicsetcoloroperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)