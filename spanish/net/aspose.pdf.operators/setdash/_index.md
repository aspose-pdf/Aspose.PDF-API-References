---
title: SetDash
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa al operador d establece el patrón de trazos de línea.
type: docs
weight: 5450
url: /es/net/aspose.pdf.operators/setdash/
---
## SetDash class

Clase que representa al operador d (establece el patrón de trazos de línea).

```csharp
public class SetDash : Operator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SetDash](setdash)(int[], int) | Crea un operador de patrón de guión establecido. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Index](../../aspose.pdf/operator/index) { get; set; } | Índice de operadores en la lista de operadores de página. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern) { get; set; } | Patrón de guiones. Los elementos de la matriz deben ser números que especifiquen las longitudes de los guiones y espacios alternos. En el caso de una matriz de elementos, las longitudes de guiones y espacios son iguales. |
| [Phase](../../aspose.pdf.operators/setdash/phase) { get; set; } | Fase de carrera. Antes de comenzar a trazar un camino, se debe recorrer la matriz de guiones, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, se iniciará el trazo de la ruta, y la matriz de guiones se utilizará cíclicamente a partir de ese punto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept)(IOperatorSelector) | Acepta objeto visitante para procesar operador. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring)() | Obtiene la representación de la cadena del operador. |

### Ver también

* class [Operator](../../aspose.pdf/operator)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->