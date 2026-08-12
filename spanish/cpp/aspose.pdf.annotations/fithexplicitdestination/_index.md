---
title: "Aspose::Pdf::Annotations::FitHExplicitDestination clase"
linktitle: "FitHExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FitHExplicitDestination clase. Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo suficiente para que todo el ancho de la página quepa dentro de la ventana. Un valor nulo para top especifica que el valor actual de ese parámetro debe permanecer sin cambios en C++."
type: docs
weight: 3600
url: /es/cpp/aspose.pdf.annotations/fithexplicitdestination/
---
## FitHExplicitDestination class


Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho total de la página quepa dentro de la ventana. Un valor nulo para top indica que se debe conservar sin cambios el valor actual de ese parámetro.

```cpp
class FitHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FitHExplicitDestination](./fithexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Crea un destino explícito local. |
| [FitHExplicitDestination](./fithexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Crea un destino explícito remoto. |
| [FitHExplicitDestination](./fithexplicitdestination/)(int32_t, double) | Crea un destino explícito remoto. |
| [get_Top](./get_top/)() | Obtiene la coordenada vertical superior posicionada en el borde superior de la ventana. |
| [ToString](./tostring/)() const override | Convierte el estado del objeto a un valor de cadena. Ejemplo: "1 FitH 100". |
## Ver también

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
