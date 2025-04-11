---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Forms.PKCS1. Representa el objeto de firma según el estándar PKCS1. Se utilizan el algoritmo de cifrado RSA y el método de resumen SHA1 para firmar.
type: docs
weight: 5170
url: /es/net/aspose.pdf.forms/pkcs1/
---
## Clase PKCS1

Representa el objeto de firma según el estándar PKCS#1. Se utilizan el algoritmo de cifrado RSA y el método de resumen SHA-1 para firmar.

```csharp
public sealed class PKCS1 : Signature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | Inicializa una nueva instancia de la clase `PKCS1`. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | Inicializa una nueva instancia de la clase `PKCS1`. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | Inicializa una nueva instancia de la clase `PKCS1`. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | Inicializa una nueva instancia de la clase `PKCS1`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | El nombre de la persona o autoridad que firma el documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un array de pares de enteros (desplazamiento de byte inicial, longitud en bytes) que describen el rango exacto de bytes para el cálculo del resumen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Información proporcionada por el firmante para permitir que un destinatario se comunique con el firmante para verificar la firma, por ejemplo, un número de teléfono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtiene/establece la apariencia personalizada. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | El delegado para firmar de manera personalizada el hash del documento. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | La hora de la firma. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | El nombre del host de la CPU o la ubicación física de la firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtiene/establece la configuración de ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La razón de la firma, como (Estoy de acuerdo, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Fuerza a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {sujeto del certificado} Fecha: {signature.Date} Razón: {signature.Reason} Ubicación: {signature.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor X. También la firma puede tener una imagen, en este caso las cadenas enumeradas se colocan sobre la imagen. ShowProperties es verdadero por defecto. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Obtiene/establece la configuración de la marca de tiempo. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Obtiene/establece la bandera de validación ltv. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera información sobre el algoritmo de firma utilizado en la firma. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifica el documento respecto a esta firma y devuelve verdadero si el documento es válido o falso en caso contrario. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifica el documento respecto a esta firma y devuelve verdadero si el documento es válido o falso en caso contrario. |

### Ver También

* clase [Signature](../signature/)
* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* ensamblaje [Aspose.PDF](../../)