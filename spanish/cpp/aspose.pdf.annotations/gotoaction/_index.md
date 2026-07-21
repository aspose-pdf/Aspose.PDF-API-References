---
title: "Aspose::Pdf::Annotations::GoToAction class"
linktitle: "GoToAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::GoToAction class. Representa una acción de ir a que cambia la vista a un destino especificado (página, ubicación y factor de ampliación) en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.pdf.annotations/gotoaction/
---
## GoToAction class


Representa una acción ir a que cambia la vista a un destino especificado (página, ubicación y factor de magnificación).

```cpp
class GoToAction : public Aspose::Pdf::Annotations::PdfAction
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_Destination](./get_destination/)() | Obtiene el destino al que saltar. |
| [GoToAction](./gotoaction/)(int32_t) | Constructor de la clase [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Page\>\&) | Constructor de la clase [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Page\>\&, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Constructor de la clase [GoToAction](./). |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<ExplicitDestination\>\&) | Constructor. |
| [GoToAction](./gotoaction/)() | Constructor. |
| [GoToAction](./gotoaction/)(const System::SharedPtr\<Document\>\&, const System::String\&) | Acción vinculada con Destino nombrado. |
| virtual [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) | Establece el destino al que saltar. |
## Ver también

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
