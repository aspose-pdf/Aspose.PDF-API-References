---
title: "Interfaccia ICustomSecurityHandler"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Interfaccia Aspose.Pdf.Security.ICustomSecurityHandler. L'interfaccia del gestore di sicurezza personalizzato"
type: docs
weight: 10150
url: /it/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

L'interfaccia del gestore di sicurezza personalizzato.

```csharp
public interface ICustomSecurityHandler
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Ottiene il nome del filtro. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Ottiene la lunghezza della chiave. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Ottiene la revisione del gestore o dell'algoritmo di crittografia. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Ottiene il nome del sottofiltro. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Ottiene la versione del gestore o dell'algoritmo di crittografia. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Calcola la EncryptionKey. Generalmente la chiave viene calcolata in base alla UserKey. È possibile utilizzare i valori da EncryptionParams, che contiene i parametri correnti al momento della chiamata. Questo valore viene passato come argomento key a [`Encrypt`](./encrypt/) e [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Decripta l'array di dati. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Cripta l'array di dati. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Cripta il campo dei permessi del document. Il risultato verrà scritto nel campo Perms del dizionario di crittografia. Quando si apre un document, il valore può essere ottenuto in [`EncryptionParameters`](../encryptionparameters/) tramite il campo Perms. Consente di verificare se i permessi del document sono cambiati. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Crea un array codificato basato sulle password che verrà scritto nel campo O del dizionario di crittografia. Deve basarsi solo sugli argomenti forniti. La password dell'utente può essere calcolata da questo campo usando la password del proprietario. Chiamato durante la crittografia per prepararlo e popolare il dizionario di crittografia. Il valore sarà disponibile in [`CalculateEncryptionKey`](./calculateencryptionkey/) per ottenere la chiave dalla UserKey. Le password specificate dall'utente durante la chiamata di crittografia del document saranno passate. Le password potrebbero non essere specificate o potrebbe essere specificata solo una. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Crea un array codificato basato sulla password dell'utente. Questo valore è tipicamente usato per verificare se la password appartiene all'utente o al proprietario, e per ottenere la chiave di crittografia. Chiamato durante la crittografia per prepararlo e popolare il dizionario di crittografia. La password specificata dall'utente viene passata come argomento quando si chiama la crittografia del document. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Chiamato per inizializzare l'istanza corrente per la crittografia. Nota che durante la crittografia, verrà riempita con i dati delle proprietà trasferite `ICustomSecurityHandler`, e durante l'apertura del document dal dizionario di crittografia. Se il metodo viene chiamato durante una nuova crittografia, allora [`UserKey`](../encryptionparameters/userkey/) e [`OwnerKey`](../encryptionparameters/ownerkey/) saranno null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Verifica se la password è quella del proprietario del document. Il metodo è chiamato dopo Initialize. La chiamata al metodo è utilizzata nell'API PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Verifica se la password appartiene all'utente (password per aprire il documento). Il metodo viene chiamato dopo Initialize. La chiamata al metodo è utilizzata nell'API PDF. |

### Vedi anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


