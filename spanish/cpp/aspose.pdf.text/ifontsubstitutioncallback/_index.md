---
title: "Aspose::Pdf::Text::IFontSubstitutionCallback clase"
linktitle: "IFontSubstitutionCallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::IFontSubstitutionCallback clase. Esta interfaz declara un mecanismo de devolución de llamada para enviar notificaciones en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.text/ifontsubstitutioncallback/
---
## IFontSubstitutionCallback class


Esta interfaz declara un mecanismo de devolución de llamada para enviar notificaciones.

```cpp
class IFontSubstitutionCallback : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_NotifyAboutFontSubstitutions](./get_notifyaboutfontsubstitutions/)() | Devuelve true si las sustituciones de fuentes están habilitadas. |
| virtual [get_Registrar](./get_registrar/)() | IRegistrar para el documento actual. |
| virtual [NotifyAboutSubstitution](./notifyaboutsubstitution/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Envía una notificación sobre la sustitución de fuentes mediante un mecanismo de eventos. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
