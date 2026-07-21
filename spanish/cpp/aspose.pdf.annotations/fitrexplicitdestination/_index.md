---
title: "Aspose::Pdf::Annotations::FitRExplicitDestination clase"
linktitle: "FitRExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FitRExplicitDestination clase. Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior quede completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, se utiliza el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible en C++."
type: docs
weight: 3700
url: /es/cpp/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class


Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede producir un comportamiento impredecible.

```cpp
class FitRExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, double) | Crea un destino explícito local. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double, double) | Crea un destino explícito remoto. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(int32_t, double, double, double, double) | Crea un destino explícito remoto. |
| [get_Bottom](./get_bottom/)() | Obtiene la coordenada vertical inferior del rectángulo visible. |
| [get_Left](./get_left/)() | Obtiene la coordenada horizontal izquierda del rectángulo visible. |
| [get_Right](./get_right/)() | Obtiene la coordenada horizontal derecha del rectángulo visible. |
| [get_Top](./get_top/)() | Obtiene la coordenada vertical superior del rectángulo visible. |
| [ToString](./tostring/)() const override | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitR 100 200 300 400". |
## Ver también

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
