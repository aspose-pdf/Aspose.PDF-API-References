---
title: Signature
second_title: Referencia de API de Aspose.PDF para .NET
description: Una clase abstracta que representa el objeto de firma en el documento pdf. Las firmas son campos con valores de objetos de firma estos últimos contienen datos que se utilizan para verificar la validez del documento.
type: docs
weight: 3210
url: /es/net/aspose.pdf.forms/signature/
---
## Signature class

Una clase abstracta que representa el objeto de firma en el documento pdf. Las firmas son campos con valores de objetos de firma, estos últimos contienen datos que se utilizan para verificar la validez del documento.

```csharp
public abstract class Signature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Signature](signature#constructor)() | Inicializa una nueva instancia del[`Signature`](../signature) clase. |
| [Signature](signature#constructor_1)(Stream, string) | Inicializa una nueva instancia del[`Signature`](../signature) clase. |
| [Signature](signature#constructor_2)(string, string) | Inicializa una nueva instancia del[`Signature`](../signature) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | El nombre de la persona o autoridad que firma el documento. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Una matriz de pares de enteros (compensación de bytes de inicio, longitud en bytes) que describirá el rango de bytes exacto para el cálculo del resumen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo) { get; set; } | Información proporcionada por el firmante para permitir que un destinatario se comunique con el firmante para verificar la firma, por ejemplo, un número de teléfono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance) { get; set; } | Obtiene/establece la apariencia personalizada. |
| [Date](../../aspose.pdf.forms/signature/date) { get; set; } | El momento de la firma. |
| [Location](../../aspose.pdf.forms/signature/location) { get; set; } | El nombre de host de la CPU o la ubicación física de la firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings) { get; set; } | Obtiene/establece la configuración de ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason) { get; set; } | El motivo de la firma, como (Estoy de acuerdoРІР‚В¦). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties) { get; set; } | Obligar a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de la firma tiene un formato de apariencia predefinido (cadenas para representar): --------------------- ------------- Firmado digitalmente por {asunto del certificado} Fecha: {firma.Fecha} Motivo: {firma.Razón} Ubicación: { firma.Ubicación} --------------------------------------------x000d_ donde {X} es un marcador de posición para el valor X. También la firma puede tener una imagen, en este caso, las cadenas enumeradas se colocan sobre la imagen. ShowProperties es verdadero de forma predeterminada. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings) { get; set; } | Obtiene/establece la configuración de marca de tiempo. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv) { get; set; } | Obtiene/establece el indicador de validación ltv. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Verify](../../aspose.pdf.forms/signature/verify)() | Verifique el documento con respecto a esta firma y devuelva verdadero si el documento es válido o falso en caso contrario. |

### Ver también

* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
