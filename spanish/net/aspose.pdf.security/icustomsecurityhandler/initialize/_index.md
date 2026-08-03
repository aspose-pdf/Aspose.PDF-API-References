---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método ICustomSecurityHandler. Llamado para inicializar la instancia actual para el cifrado. Tenga en cuenta que al cifrar se rellenará con los datos de las propiedades transferidas ICustomSecurityHandler y al abrir el documento desde el diccionario de cifrado. Si el método se llama durante un nuevo cifrado, entonces UserKey y OwnerKey serán nulos"
type: docs
weight: 120
url: /es/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Llamado para inicializar la instancia actual para el cifrado. Tenga en cuenta que al cifrar, se rellenará con los datos de las propiedades transferidas [`ICustomSecurityHandler`](../), y al abrir el documento desde el diccionario de cifrado. Si el método se llama durante un nuevo cifrado, entonces [`UserKey`](../../encryptionparameters/userkey/) y [`OwnerKey`](../../encryptionparameters/ownerkey/) serán nulos.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parámetros | EncryptionParameters | Los parámetros de cifrado. |

### Ver también

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


