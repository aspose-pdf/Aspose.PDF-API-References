---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination class"
linktitle: "XYZExplicitDestination"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination class. Representa un destino explícito que muestra la página con las coordenadas (left, top) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros left, top o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo en C++."
type: docs
weight: 12000
url: /es/cpp/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class


Representa un destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo.

```cpp
class XYZExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateDestination](./createdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, bool) | Cree el destino a la ubicación especificada de la página considerando la rotación de la página si es necesario. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Cree el destino a la esquina superior izquierda de la página especificada. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Cree el destino a la página especificada. |
| [get_Left](./get_left/)() | Obtiene la coordenada horizontal izquierda de la esquina superior izquierda de la ventana. |
| [get_Top](./get_top/)() | Obtiene la coordenada vertical superior de la esquina superior izquierda de la ventana. |
| [get_Zoom](./get_zoom/)() | Obtiene el factor de zoom. |
| [ToString](./tostring/)() const override | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 XYZ 100 200 3". |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double) | Crea un destino explícito local. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double) | Crea un destino explícito remoto. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(int32_t, double, double, double) | Crea un destino explícito remoto. |
## Ver también

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
