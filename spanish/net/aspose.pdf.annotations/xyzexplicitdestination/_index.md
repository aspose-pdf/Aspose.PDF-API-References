---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Annotations.XYZExplicitDestination. Representa un destino explícito que muestra la página con las coordenadas izquierda superior posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, superior o zoom especifica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo.
type: docs
weight: 2730
url: /es/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Clase XYZExplicitDestination

Representa un destino explícito que muestra la página con las coordenadas (izquierda, superior) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, superior o zoom especifica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Crea un destino explícito remoto. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Crea un destino explícito local. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Obtiene la coordenada horizontal izquierda de la esquina superior izquierda de la ventana. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtiene el objeto de la página de destino |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtiene el número de página de destino |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Obtiene la coordenada vertical superior de la esquina superior izquierda de la ventana. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Obtiene el factor de zoom. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Crea un destino a la ubicación especificada de la página considerando la rotación de la página si es necesario. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Crea un destino a la página especificada. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Crea un destino a la esquina superior izquierda de la página especificada. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 XYZ 100 200 3". |

## Ejemplos

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Ver También

* clase [ExplicitDestination](../explicitdestination/)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../)