---
title: "Clase Aspose::Pdf::NamedDestinationCollection"
linktitle: "NamedDestinationCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::NamedDestinationCollection. La clase representa la colección de todas las destinaciones (un árbol de nombres que asigna cadenas de nombres a destinaciones (ver 12.3.2.3, \"Named Destinations\") y (ver 7.7.4, \"Name Dictionary\")) en el documento pdf en C++."
type: docs
weight: 11600
url: /es/cpp/aspose.pdf/nameddestinationcollection/
---
## NamedDestinationCollection class


Clase que representa la colección de todos los destinos (un árbol de nombres que asigna cadenas de nombres a destinos (ver 12.3.2.3, "Destinos con nombre") y (ver 7.7.4, "Diccionario de nombres")) en el documento pdf.

```cpp
class NamedDestinationCollection : public Aspose::Pdf::INamedDestinationCollection
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Agregar una nueva destinación nombrada. |
| [get_Count](./get_count/)() override | Cantidad de destinaciones nombradas. |
| [get_Names](./get_names/)() override | Lista de nombres de las destinaciones. |
| [idx_get](./idx_get/)(System::String) override | Obtiene la cita por su nombre. |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Establece la cita por su nombre. |
| [Remove](./remove/)(System::String) override | Eliminar destinación nombrada. |
## Ver también

* Class [INamedDestinationCollection](../inameddestinationcollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
