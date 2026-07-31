---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo ICustomSecurityHandler. Crea un array codificato basato sulla password dell'utente. Questo valore è tipicamente usato per verificare se la password appartiene all'utente o al proprietario e per ottenere la chiave di crittografia. Chiamato durante la crittografia per prepararlo e popolare il dizionario di crittografia. La password specificata dall'utente è passata come argomento quando si chiama la crittografia del documento."
type: docs
weight: 110
url: /it/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Crea un array codificato basato sulla password dell'utente. Questo valore è tipicamente usato per verificare se la password appartiene all'utente o al proprietario, e per ottenere la chiave di crittografia. Chiamato durante la crittografia per prepararlo e popolare il dizionario di crittografia. La password specificata dall'utente viene passata come argomento quando si chiama la crittografia del document.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | La password dell'utente. |

### Valore di ritorno

L'array della chiave utente.

### Vedi anche

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


