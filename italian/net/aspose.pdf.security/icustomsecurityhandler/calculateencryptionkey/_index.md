---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo ICustomSecurityHandler. Calcola l'EncryptionKey. Generalmente la chiave è calcolata in base al UserKey. È possibile utilizzare i valori da EncryptionParams che contengono i parametri correnti al momento della chiamata. Questo valore viene passato come argomento key in Encrypt e Decrypt"
type: docs
weight: 60
url: /it/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calcola l'EncryptionKey. Generalmente la chiave è calcolata in base al UserKey. È possibile utilizzare i valori da EncryptionParams, che contengono i parametri correnti al momento della chiamata. Questo valore viene passato come argomento key in [`Encrypt`](../encrypt/) e [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | String | Password inserita dall'utente. |

### Valore di ritorno

L'array della chiave di crittografia.

### Vedi anche

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


