---
title: "Aspose::Pdf::Annotations::FitBHExplicitDestination clase"
linktitle: "FitBHExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FitBHExplicitDestination clase. Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que todo el ancho de su cuadro delimitador quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro se mantendrá sin cambios en C++."
type: docs
weight: 3300
url: /es/cpp/aspose.pdf.annotations/fitbhexplicitdestination/
---
## FitBHExplicitDestination class


Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho total de su caja delimitadora quepa dentro de la ventana. Un valor nulo para top indica que se debe conservar sin cambios el valor actual de ese parámetro.

```cpp
class FitBHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Crea un destino explícito local. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Crea un destino explícito remoto. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(int32_t, double) | Crea un destino explícito remoto. |
| [get_Top](./get_top/)() | Obtiene la coordenada vertical superior posicionada en el borde superior de la ventana. |
| [ToString](./tostring/)() const override | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitBH 100". |
## Ver también

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
