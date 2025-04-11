---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.SetAdvancedColorStroke. Clase que representa el operador SCN para establecer el color en operaciones de trazado
type: docs
weight: 7570
url: /es/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## Clase SetAdvancedColorStroke

Clase que representa el operador SCN (establecer color para operaciones de trazado).

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | Inicializa el operador. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | Constructor para el operador scn |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | Constructor para el operador scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | Constructor para el operador scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | Constructor para el operador scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | Constructor para el operador scn. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Obtiene el componente rojo del color |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Obtiene el componente cian del color CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtiene el array de componentes de color. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Obtiene el componente verde del color |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtiene el componente negro del color gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Obtiene el componente negro del color CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Obtiene el componente magenta del color CMYK. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Obtiene el nombre del patrón. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Obtiene el componente rojo del color |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Obtiene el componente amarillo del color CMYK. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | Acepta el objeto visitante para procesar el operador. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | Devuelve el color especificado por el operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Véase también

* clase [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)