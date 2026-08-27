---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo ICustomSecurityHandler. Chiamato per inizializzare l'istanza corrente per la crittografia. Nota che durante la crittografia verrà riempito con i dati delle proprietà trasferite ICustomSecurityHandler e quando si apre il documento dal dizionario di crittografia. Se il metodo è chiamato durante una nuova crittografia, allora UserKey e OwnerKey saranno null."
type: docs
weight: 120
url: /it/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Chiamato per inizializzare l'istanza corrente per la crittografia. Nota che durante la crittografia, verrà riempito con i dati delle proprietà trasferite [`ICustomSecurityHandler`](../), e quando si apre il documento dal dizionario di crittografia. Se il metodo è chiamato durante una nuova crittografia, allora [`UserKey`](../../encryptionparameters/userkey/) e [`OwnerKey`](../../encryptionparameters/ownerkey/) saranno null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parametri | EncryptionParameters | I parametri di crittografia. |

### Vedi anche

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


