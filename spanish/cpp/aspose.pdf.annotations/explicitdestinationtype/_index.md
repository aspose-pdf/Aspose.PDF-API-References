---
title: "Enumeración Aspose::Pdf::Annotations::ExplicitDestinationType"
linktitle: "ExplicitDestinationType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración Aspose::Pdf::Annotations::ExplicitDestinationType. Enumera los tipos de destinos explícitos en C++."
type: docs
weight: 13100
url: /es/cpp/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enum


Enumera los tipos de destinos explícitos.

```cpp
enum class ExplicitDestinationType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| XYZ | 0 | Muestra la página con las coordenadas (left, top) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor zoom. Un valor nulo para cualquiera de los parámetros left, top o zoom indica que el valor actual de ese parámetro debe permanecer sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. |
| Fit | 1 | Muestre la página con su contenido ampliado lo suficiente para que toda la página quepa dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la página dentro de la ventana en la otra dimensión. |
| FitH | 2 | Muestre la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que todo el ancho de la página quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro debe permanecer sin cambios. |
| FitV | 3 | Muestre la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que toda la altura de la página quepa dentro de la ventana. Un valor nulo para left indica que el valor actual de ese parámetro debe permanecer sin cambios. |
| FitR | 4 | Muestre la página con su contenido ampliado lo suficiente para que el rectángulo especificado por las coordenadas left, bottom, right y top quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede producir un comportamiento impredecible. |
| FitB | 5 | Muestre la página con su contenido ampliado lo suficiente para que su caja delimitadora quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la caja delimitadora dentro de la ventana en la otra dimensión. |
| FitBH | 6 | Muestre la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que todo el ancho de su caja delimitadora quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro debe permanecer sin cambios. |
| FitBV | 7 | Muestre la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que toda la altura de su caja delimitadora quepa dentro de la ventana. Un valor nulo para left indica que el valor actual de ese parámetro debe permanecer sin cambios. |

## Ver también

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
