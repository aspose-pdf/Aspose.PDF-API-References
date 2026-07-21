---
title: "Aspose::Pdf::Annotations::FitVExplicitDestination clase"
linktitle: "FitVExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FitVExplicitDestination clase. Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo suficiente para que toda la altura de la página quepa dentro de la ventana. Un valor nulo para left especifica que el valor actual de ese parámetro debe permanecer sin cambios en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.pdf.annotations/fitvexplicitdestination/
---
## FitVExplicitDestination class


Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura total de la página quepa dentro de la ventana. Un valor nulo para left indica que se debe conservar sin cambios el valor actual de ese parámetro.

```cpp
class FitVExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FitVExplicitDestination](./fitvexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Crea un destino explícito local. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double) | Crea un destino explícito remoto. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(int32_t, double) | Crea un destino explícito remoto. |
| [get_Left](./get_left/)() | Obtiene la coordenada horizontal left posicionada en el borde izquierdo de la ventana. |
| [ToString](./tostring/)() const override | Convierte el estado del objeto a un valor de cadena. Ejemplo: "1 FitV 100". |
## Ver también

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
