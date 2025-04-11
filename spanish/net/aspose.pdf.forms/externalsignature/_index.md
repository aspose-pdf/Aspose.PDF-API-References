---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Forms.ExternalSignature. Crea una firma PKCS7 desanexada utilizando un X509Certificate2. Soporta tokens de tarjetas inteligentes USB sin claves privadas exportables.
type: docs
weight: 5040
url: /es/net/aspose.pdf.forms/externalsignature/
---
## Clase ExternalSignature

Crea una firma PKCS#7 desanexada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```csharp
public class ExternalSignature : Signature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Crea una firma PKCS#7 `(desanexada)` utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Crea una firma PKCS#7 utilizando un X509Certificate2 como cadena base64. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Crea una firma PKCS#7 `(desanexada)` utilizando un X509Certificate2 como cadena base64. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Crea una firma PKCS#7 desanexada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Crea una firma PKCS#7 `(desanexada)` utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | El nombre de la persona o autoridad que firma el documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un array de pares de enteros (desplazamiento de byte inicial, longitud en bytes) que describen el rango exacto de bytes para el cálculo del resumen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Información proporcionada por el firmante para permitir que un destinatario se comunique con el firmante para verificar la firma, por ejemplo, un número de teléfono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtiene/establece la apariencia personalizada. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | El delegado para firmar el hash del documento de forma personalizada. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | La hora de la firma. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | El nombre del host de la CPU o la ubicación física de la firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtiene/establece la configuración de ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La razón de la firma, como (Estoy de acuerdo, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Fuerza a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {sujeto del certificado} Fecha: {firma.Date} Razón: {firma.Reason} Ubicación: {firma.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. También la firma puede tener una imagen, en este caso las cadenas listadas se colocan sobre la imagen. ShowProperties es verdadero por defecto. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtiene/establece la configuración de la marca de tiempo. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtiene/establece la bandera de validación ltv. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera información sobre el algoritmo de firma utilizado en la firma. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifica el documento respecto a esta firma y devuelve verdadero si el documento es válido o falso en caso contrario. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifica el documento respecto a esta firma y devuelve verdadero si el documento es válido o falso en caso contrario. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | El certificado con la clave privada. |

### Véase También

* clase [Signature](../signature/)
* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* ensamblaje [Aspose.PDF](../../)