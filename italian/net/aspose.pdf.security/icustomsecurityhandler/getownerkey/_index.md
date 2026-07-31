---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo ICustomSecurityHandler. Crea un array codificato basato sulle password che verrà scritto nel campo O del dizionario di crittografia. Deve basarsi solo sugli argomenti passati. La password dell'utente può essere calcolata da questo campo usando la password del proprietario. Viene chiamato durante la crittografia per prepararla e popolare il dizionario di crittografia. Il valore sarà disponibile in CalculateEncryptionKey per ottenere la chiave dal UserKey. Le password specificate dall'utente al momento della crittografia del documento saranno passate. Le password potrebbero non essere specificate o potrebbe essere specificata solo una."
type: docs
weight: 100
url: /it/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Crea un array codificato basato sulle password che verrà scritto nel campo O del dizionario di crittografia. Deve basarsi solo sugli argomenti passati. La password dell'utente può essere calcolata da questo campo usando la password del proprietario. Viene chiamato durante la crittografia per prepararla e popolare il dizionario di crittografia. Il valore sarà disponibile in [`CalculateEncryptionKey`](../calculateencryptionkey/) per ottenere la chiave dal UserKey. Le password specificate dall'utente al momento della crittografia del documento saranno passate. Le password potrebbero non essere specificate o potrebbe essere specificata solo una.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | La password dell'utente. |
| ownerPassword | String | La password del proprietario. |

### Valore di ritorno

L'array della chiave del proprietario.

### Vedi anche

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


