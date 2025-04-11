---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Enum ExplicitDestinationType de Aspose.Pdf.Annotations. Enumera los tipos de destinos explícitos
type: docs
weight: 1690
url: /es/net/aspose.pdf.annotations/explicitdestinationtype/
---
## Enumeración ExplicitDestinationType

Enumera los tipos de destinos explícitos.

```csharp
public enum ExplicitDestinationType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| XYZ | `0` | Muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom especifica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. |
| Fit | `1` | Muestra la página con su contenido ampliado lo suficiente para que quepa toda la página dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la página dentro de la ventana en la otra dimensión. |
| FitH | `2` | Muestra la página con la coordenada vertical arriba posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la anchura de la página dentro de la ventana. Un valor nulo para arriba especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| FitV | `3` | Muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la altura de la página dentro de la ventana. Un valor nulo para izquierda especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| FitR | `4` | Muestra la página con su contenido ampliado lo suficiente para que quepa el rectángulo especificado por las coordenadas izquierda, abajo, derecha y arriba completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible. |
| FitB | `5` | Muestra la página con su contenido ampliado lo suficiente para que quepa completamente su caja delimitadora dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la caja delimitadora dentro de la ventana en la otra dimensión. |
| FitBH | `6` | Muestra la página con la coordenada vertical arriba posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la anchura de su caja delimitadora dentro de la ventana. Un valor nulo para arriba especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |
| FitBV | `7` | Muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que quepa toda la altura de su caja delimitadora dentro de la ventana. Un valor nulo para izquierda especifica que el valor actual de ese parámetro debe mantenerse sin cambios. |

### Ver También

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)