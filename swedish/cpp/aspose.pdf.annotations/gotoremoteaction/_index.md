---
title: "Aspose::Pdf::Annotations::GoToRemoteAction class"
linktitle: "GoToRemoteAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::GoToRemoteAction class. Representerar en fjärr‑gå‑till‑åtgärd som liknar en vanlig gå‑till‑åtgärd men hoppar till en destination i en annan PDF‑fil istället för den aktuella filen i C++."
type: docs
weight: 4400
url: /sv/cpp/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class


Representerar en fjärr‑gå‑till‑åtgärd som liknar en vanlig gå‑till‑åtgärd men hoppar till en destination i en annan PDF‑fil istället för den aktuella filen.

```cpp
class GoToRemoteAction : public Aspose::Pdf::Annotations::GoToAction
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Destination](./get_destination/)() override | Hämtar destinationen att hoppa till. |
| [get_File](./get_file/)() | Hämtar specifikationen för filen där destinationen finns. |
| [get_NewWindow](./get_newwindow/)() | Hämtar en flagga som specificerar om destinationsdokumentet ska öppnas i ett nytt fönster. |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, int32_t) | Initierar [GoToRemoteAction](./) objekt. |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, const System::SharedPtr\<ExplicitDestination\>\&) | Initierar [GoToRemoteAction](./) objekt. |
| [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) override | Ställer in destinationen att hoppa till. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Ställer in specifikationen för filen där destinationen finns. |
| [set_NewWindow](./set_newwindow/)(ExtendedBoolean) | Ställer in en flagga som specificerar om destinationsdokumentet ska öppnas i ett nytt fönster. |
## Se även

* Class [GoToAction](../gotoaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
