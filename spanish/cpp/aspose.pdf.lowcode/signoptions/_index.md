---
title: "Aspose::Pdf::LowCode::SignOptions clase"
linktitle: "SignOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::SignOptions clase. Representa opciones de firma para el plugin Signature en C++."
type: docs
weight: 7400
url: /es/cpp/aspose.pdf.lowcode/signoptions/
---
## SignOptions class


Representa opciones de firma para el plugin [Signature](../signature/).

```cpp
class SignOptions : public Aspose::Pdf::LowCode::OrganizerBaseOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Contact](./get_contact/)() const | El contacto de la firma. |
| [get_Location](./get_location/)() const | La ubicación de la firma. |
| [get_Name](./get_name/)() const | El nombre del campo de firma existente. Nulo para crear un nuevo campo. |
| [get_PageNumber](./get_pagenumber/)() const | El número de página en el que se realiza la firma. |
| [get_Reason](./get_reason/)() const | La razón de la firma. |
| [get_Rectangle](./get_rectangle/)() const | El rectángulo de la firma. |
| [get_Visible](./get_visible/)() const | La visibilidad de la firma. |
| [set_Contact](./set_contact/)(const System::String\&) | El contacto de la firma. |
| [set_Location](./set_location/)(const System::String\&) | La ubicación de la firma. |
| [set_Name](./set_name/)(const System::String\&) | El nombre del campo de firma existente. Nulo para crear un nuevo campo. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | El número de página en el que se realiza la firma. |
| [set_Reason](./set_reason/)(const System::String\&) | La razón de la firma. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | El rectángulo de la firma. |
| [set_Visible](./set_visible/)(bool) | La visibilidad de la firma. |
| [SignOptions](./signoptions/)(const System::String\&, const System::String\&) | Inicializa una nueva instancia del objeto [SignOptions](./) con opciones predeterminadas. |
| [SignOptions](./signoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Inicializa una nueva instancia del objeto [SignOptions](./) con opciones predeterminadas. |
## Ver también

* Class [OrganizerBaseOptions](../organizerbaseoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
