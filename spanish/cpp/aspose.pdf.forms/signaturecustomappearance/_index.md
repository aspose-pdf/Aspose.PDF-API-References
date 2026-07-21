---
title: "Aspose::Pdf::Forms::SignatureCustomAppearance clase"
linktitle: "SignatureCustomAppearance"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::SignatureCustomAppearance. Una clase abstracta que representa un objeto de apariencia personalizada de firma en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.forms/signaturecustomappearance/
---
## SignatureCustomAppearance class


Una clase abstracta que representa un objeto de apariencia personalizada de firma.

```cpp
class SignatureCustomAppearance : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Obtiene/establece el color de fondo. Valor predeterminado: Transparente. |
| [get_ContactInfoLabel](./get_contactinfolabel/)() const | Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contacto". |
| [get_Culture](./get_culture/)() const | Obtiene/establece el valor de información cultural. Valor predeterminado: InvariantCulture. |
| [get_DateSignedAtLabel](./get_datesignedatlabel/)() const | Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date". |
| [get_DateTimeFormat](./get_datetimeformat/)() const | Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss". |
| [get_DateTimeLocalFormat](./get_datetimelocalformat/)() const | Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz". |
| [get_DigitalSignedLabel](./get_digitalsignedlabel/)() const | Obtiene/establece la etiqueta de firma digital. Valor predeterminado: "Digitally signed by". |
| [get_DigitalSubjectFormat](./get_digitalsubjectformat/)() const | Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization. |
| [get_FontFamilyName](./get_fontfamilyname/)() const | Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial. |
| [get_FontSize](./get_fontsize/)() const | Obtiene/establece el tamaño de fuente. Valor predeterminado: 10. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue. |
| [get_IsForegroundImage](./get_isforegroundimage/)() const | Obtiene un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false. |
| [get_LocationLabel](./get_locationlabel/)() const | Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location". |
| [get_ReasonLabel](./get_reasonlabel/)() const | Obtiene/establece la etiqueta de motivo. Valor predeterminado: "Reason". |
| [get_Rotation](./get_rotation/)() const | Obtiene la rotación de la firma. |
| [get_ShowContactInfo](./get_showcontactinfo/)() const | Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true. |
| [get_ShowLocation](./get_showlocation/)() const | Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true. |
| [get_ShowReason](./get_showreason/)() const | Obtiene/establece la visibilidad del motivo. Valor predeterminado: true. |
| [get_UseDigitalSubjectFormat](./get_usedigitalsubjectformat/)() const | Obtiene/establece el estado de uso del [DigitalSubjectFormat](../). |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Obtiene/establece el color de fondo. Valor predeterminado: Transparente. |
| [set_ContactInfoLabel](./set_contactinfolabel/)(const System::String\&) | Obtiene/establece la etiqueta de información de contacto. Valor predeterminado: "Contacto". |
| [set_Culture](./set_culture/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&) | Obtiene/establece el valor de información cultural. Valor predeterminado: InvariantCulture. |
| [set_DateSignedAtLabel](./set_datesignedatlabel/)(const System::String\&) | Obtiene/establece la etiqueta de fecha de firma. Valor predeterminado: "Date". |
| [set_DateTimeFormat](./set_datetimeformat/)(const System::String\&) | Obtiene/establece el formato de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss". |
| [set_DateTimeLocalFormat](./set_datetimelocalformat/)(const System::String\&) | Obtiene/establece el formato local de fecha y hora. Valor predeterminado: "yyyy.MM.dd HH:mm:ss zzz". |
| [set_DigitalSignedLabel](./set_digitalsignedlabel/)(const System::String\&) | Obtiene/establece la etiqueta de firma digital. Valor predeterminado: "Digitally signed by". |
| [set_DigitalSubjectFormat](./set_digitalsubjectformat/)(const System::ArrayPtr\<SubjectNameElements\>\&) | Obtiene/establece el formato para el orden de los elementos en la cadena Subject. Ejemplos de resultados: C=UK, CN=Org, O=Organization o CN=Org, C=UK, O=Organization o O=Organization. |
| [set_FontFamilyName](./set_fontfamilyname/)(const System::String\&) | Obtiene/establece el nombre de la familia tipográfica. Debe existir en el documento. Valor predeterminado: Arial. |
| [set_FontSize](./set_fontsize/)(double) | Obtiene/establece el tamaño de fuente. Valor predeterminado: 10. |
| [set_ForegroundColor](./set_foregroundcolor/)(const System::SharedPtr\<Color\>\&) | Obtiene/establece el color de primer plano (color del texto). Valor predeterminado: Blue. |
| [set_IsForegroundImage](./set_isforegroundimage/)(bool) | Establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen de primer plano. Valor predeterminado: false. |
| [set_LocationLabel](./set_locationlabel/)(const System::String\&) | Obtiene/establece la etiqueta de ubicación. Valor predeterminado: "Location". |
| [set_ReasonLabel](./set_reasonlabel/)(const System::String\&) | Obtiene/establece la etiqueta de motivo. Valor predeterminado: "Reason". |
| [set_Rotation](./set_rotation/)(Aspose::Pdf::Rotation) | Establece la rotación de la firma. |
| [set_ShowContactInfo](./set_showcontactinfo/)(bool) | Obtiene/establece la visibilidad de la información de contacto. Valor predeterminado: true. |
| [set_ShowLocation](./set_showlocation/)(bool) | Obtiene/establece la visibilidad de la ubicación. Valor predeterminado: true. |
| [set_ShowReason](./set_showreason/)(bool) | Obtiene/establece la visibilidad del motivo. Valor predeterminado: true. |
| [set_UseDigitalSubjectFormat](./set_usedigitalsubjectformat/)(bool) | Obtiene/establece el estado de uso del [DigitalSubjectFormat](../). |
| [SignatureCustomAppearance](./signaturecustomappearance/)() | Inicializa una nueva instancia de la clase [SignatureCustomAppearance](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
