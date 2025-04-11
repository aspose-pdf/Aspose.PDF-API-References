---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Forms.PKCS7. Representa el objeto PKCS7 que se ajusta a la especificación PKCS7 en el RFC de Internet 2315 PKCS 7 Sintaxis de Mensaje Criptográfico Versión 1.5. El resumen SHA1 del rango de bytes del documento está encapsulado en el campo SignedData de PKCS7.
type: docs
weight: 5180
url: /es/net/aspose.pdf.forms/pkcs7/
---
## Clase PKCS7

Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC de Internet 2315, PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5. El `SHA1 digest` del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7.

```csharp
public sealed class PKCS7 : Signature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | Inicializa una nueva instancia de la clase `PKCS7`. |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | Inicializa una nueva instancia de la clase `PKCS7`. |
| [PKCS7](pkcs7/#constructor_2)(string, string) | Inicializa una nueva instancia de la clase `PKCS7`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | El nombre de la persona o autoridad que firma el documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Obtiene y establece una opción que indica si se debe evitar estimar la longitud de una firma. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un array de pares de enteros (desplazamiento de byte inicial, longitud en bytes) que describen el rango exacto de bytes para el cálculo del resumen. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Información proporcionada por el firmante para permitir que un destinatario se comunique con el firmante para verificar la firma, por ejemplo, un número de teléfono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Obtiene/establece la apariencia personalizada. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | El delegado para firmar de manera personalizada el resumen del documento. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | La hora de la firma. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Obtiene o establece la longitud predeterminada para los datos de la firma en bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | El nombre del host de la CPU o la ubicación física de la firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Obtiene/establece la configuración de ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | La razón de la firma, como (Estoy de acuerdo, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Fuerza a mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo de firma tiene un formato de apariencia predefinido (cadenas para representar): ------------------------------------------- Firmado digitalmente por {sujeto del certificado} Fecha: {firma.Date} Razón: {firma.Reason} Ubicación: {firma.Location} ------------------------------------------- donde {X} es un marcador de posición para el valor de X. También la firma puede tener una imagen, en este caso las cadenas enumeradas se colocan sobre la imagen. ShowProperties es verdadero por defecto. |
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
* ensamblado [Aspose.PDF](../../)