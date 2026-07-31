---
title: "Document.Document"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore Document. Inizializza una nuova istanza di Document dallo stream di input"
type: docs
weight: 10
url: /it/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| isManagedStream | Boolean | se impostato su `true` il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Oggetto flusso di input, il pdf corrispondente è protetto da password. |
| password | String | Password utente o proprietario. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Oggetto flusso di input, il pdf corrispondente è protetto da password. |
| certOptions | CertificateEncryptionOptions | Le opzioni di crittografia del certificato. |

### Vedi anche

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| certOptions | CertificateEncryptionOptions | Le opzioni di crittografia del certificato. |
| isManagedStream | Boolean | Se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| certOptions | CertificateEncryptionOptions | Le opzioni di crittografia del certificato. |

### Vedi anche

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| certOptions | CertificateEncryptionOptions | Le opzioni di crittografia del certificato. |
| isManagedStream | Boolean | se impostato su `true` il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Oggetto flusso di input, il pdf corrispondente è protetto da password. |
| password | String | Password utente o proprietario. |
| customSecurityHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

### Vedi anche

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | Se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

Inizializza una nuova istanza di Document dallo stream *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso con documento pdf. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | Se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |
| customSecurityHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

### Vedi anche

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

Basta inizializzare Document usando *filename*. È lo stesso di `Document`.

```csharp
public Document(string filename)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file del documento pdf. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

Basta inizializzare Document usando *filename*. È lo stesso di `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file del documento pdf. |
| isManagedStream | Boolean | Se impostato su `true` lo stream interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| password | String | Password utente o proprietario. |
| customSecurityHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

### Vedi anche

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| password | String | Password utente o proprietario. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | se impostato su `true` il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

Inizializza una nuova istanza della classe [`Document`](../) per lavorare con un documento crittografato.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Nome file Document. |
| password | String | Password utente o proprietario. |
| isManagedStream | Boolean | se impostato su `true` il flusso interno viene chiuso prima dell'uscita; altrimenti, non lo è. |
| customSecurityHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

### Vedi anche

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Inizializza un documento vuoto.

```csharp
public Document()
```

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Inizializza un documento vuoto per versione.

```csharp
public Document(PdfVersion version)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| versione | PdfVersion | La versione PDF. |

### Vedi anche

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

Apre un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | File di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire *filename* in documento pdf. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Apre un documento esistente da uno stream fornendo la conversione necessaria per ottenere un documento pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | Stream | Flusso di input da convertire in documento pdf. |
| options | LoadOptions | Rappresenta le proprietà per convertire *input* in documento pdf. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


