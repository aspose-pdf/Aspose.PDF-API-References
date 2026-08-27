---
title: "Aspose.Pdf.Security"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Lo spazio dei nomi Aspose.Pdf.Security contiene classi utilizzate per la crittografia e la firma digitale"
type: docs
weight: 210
url: /it/net/aspose.pdf.security/
---
Lo spazio dei nomi **Aspose.Pdf.Security** contiene classi utilizzate per la crittografia e la firma digitale.

## Classi

| Classe | Descrizione |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | Rappresenta una classe per le opzioni di crittografia di un PDF document utilizzando un metodo di crittografia basato su certificato. Utilizzata per aprire PDF documents crittografati. |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | Rappresenta una classe per le informazioni sull'algoritmo di firma DSA. |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | Rappresenta una classe per le informazioni sull'algoritmo di firma ECDSA. |
| [EncryptionParameters](./encryptionparameters/) | Rappresenta una classe di parametri di crittografia. |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | Rappresenta una classe per le informazioni su un algoritmo di firma con chiave. |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | Rappresenta una classe per le informazioni sull'algoritmo di firma RSA. |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | Rappresenta una classe per le informazioni su un algoritmo di firma, includendo il suo tipo, lo standard crittografico e l'algoritmo di hash del digest. |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | Rappresenta gli errori che si verificano durante la firma PDF. Si verifica se [`SignHash`](../aspose.pdf.forms/signhash/) viene utilizzato per firmare un document e la lunghezza effettiva della firma è maggiore di quella specificata nell'opzione [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/). |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | Rappresenta una classe per le informazioni sull'algoritmo di firma timestamp. |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | Rappresenta una classe per le informazioni sull'algoritmo di firma sconosciuto. |
| [ValidationOptions](./validationoptions/) | Rappresenta le opzioni per la convalida di una firma digitale in un PDF document. |
| [ValidationResult](./validationresult/) | Rappresenta il risultato di un processo di convalida per un certificato. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | L'interfaccia del gestore di sicurezza personalizzato. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | Rappresenta gli standard crittografici disponibili per proteggere i documenti PDF. |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | Elenca i tipi di algoritmi di firma utilizzati per le firme digitali. |
| [ValidationMethod](./validationmethod/) | Rappresenta un enum che definisce il metodo usato per la convalida del certificato. |
| [ValidationMode](./validationmode/) | Specifica la modalità di convalida per i processi di validazione delle firme PDF. |
| [ValidationStatus](./validationstatus/) | Rappresenta lo stato di convalida di una validazione del certificato. |


