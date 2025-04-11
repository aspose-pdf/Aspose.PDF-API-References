---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.EncryptionOptions. Representa las opciones de cifrado para el complemento de seguridad
type: docs
weight: 8540
url: /es/net/aspose.pdf.plugins/encryptionoptions/
---
## Clase EncryptionOptions

Representa las opciones de cifrado para el complemento [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Inicializa una nueva instancia del objeto `EncryptionOptions` con opciones predeterminadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Cierra los flujos de entrada después de que se complete la operación. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Cierra los flujos de salida después de que se complete la operación. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algoritmo criptográfico, consulte [`CryptoAlgorithm`](./cryptoalgorithm/) para más detalles. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Permisos del documento, consulte [`Permissions`](../../aspose.pdf/permissions/) para más detalles. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Devuelve la colección de datos del complemento OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Contraseña del propietario. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Contraseña del usuario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del complemento PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del complemento PdfOrganizer. |

### Véase también

* clase [OrganizerBaseOptions](../organizerbaseoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)