---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.FitRExplicitDestination. Representa un destino explícito que muestra la página con su contenido ampliado lo suficiente para ajustar el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible.
type: docs
weight: 1780
url: /es/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## Clase FitRExplicitDestination

Representa un destino explícito que muestra la página con su contenido ampliado lo suficiente para ajustar el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Crea un destino explícito remoto. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Crea un destino explícito local. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Obtiene la coordenada vertical inferior del rectángulo visible. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Obtiene la coordenada horizontal izquierda del rectángulo visible. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtiene el objeto de la página de destino |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtiene el número de página de destino |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Obtiene la coordenada horizontal derecha del rectángulo visible. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Obtiene la coordenada vertical superior del rectángulo visible. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitR 100 200 300 400". |

### Véase también

* clase [ExplicitDestination](../explicitdestination/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../)