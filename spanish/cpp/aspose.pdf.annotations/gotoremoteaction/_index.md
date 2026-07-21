---
title: "Clase Aspose::Pdf::Annotations::GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::GoToRemoteAction. Representa una acción de ir a remoto que es similar a una acción de ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual en C++."
type: docs
weight: 4400
url: /es/cpp/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class


Representa una acción ir a remota que es similar a una acción ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual.

```cpp
class GoToRemoteAction : public Aspose::Pdf::Annotations::GoToAction
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Destination](./get_destination/)() override | Obtiene el destino al que saltar. |
| [get_File](./get_file/)() | Obtiene la especificación del archivo en el que se encuentra el destino. |
| [get_NewWindow](./get_newwindow/)() | Obtiene una bandera que especifica si se debe abrir el documento de destino en una nueva ventana. |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, int32_t) | Inicializa el objeto [GoToRemoteAction](./). |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, const System::SharedPtr\<ExplicitDestination\>\&) | Inicializa el objeto [GoToRemoteAction](./). |
| [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) override | Establece el destino al que saltar. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Establece la especificación del archivo en el que se encuentra el destino. |
| [set_NewWindow](./set_newwindow/)(ExtendedBoolean) | Establece una bandera que indica si se debe abrir el documento de destino en una nueva ventana. |
## Ver también

* Class [GoToAction](../gotoaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
