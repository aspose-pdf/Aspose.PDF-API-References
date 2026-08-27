---
title: "Document.Document"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur Document. Initialise une nouvelle instance de Document à partir du flux d'entrée"
type: docs
weight: 10
url: /fr/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Objet flux d'entrée, le PDF correspondant est protégé par mot de passe. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Objet flux d'entrée, le PDF correspondant est protégé par mot de passe. |
| certOptions | CertificateEncryptionOptions | Les options de chiffrement du certificat. |

### Voir aussi

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| certOptions | CertificateEncryptionOptions | Les options de chiffrement du certificat. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| certOptions | CertificateEncryptionOptions | Les options de chiffrement du certificat. |

### Voir aussi

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| certOptions | CertificateEncryptionOptions | Les options de chiffrement du certificat. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Objet flux d'entrée, le PDF correspondant est protégé par mot de passe. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| customSecurityHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

### Voir aussi

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

Initialise une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |
| customSecurityHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

### Voir aussi

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

Il suffit d'initialiser Document en utilisant *filename*. Identique à `Document`.

```csharp
public Document(string filename)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Le nom du fichier du document PDF. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

Il suffit d'initialiser Document en utilisant *filename*. Identique à `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Le nom du fichier du document PDF. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| customSecurityHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

### Voir aussi

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document chiffré.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Nom du fichier Document. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |
| customSecurityHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

### Voir aussi

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Initialise un document vide.

```csharp
public Document()
```

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Initialise un document vide par version.

```csharp
public Document(PdfVersion version)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| version | PdfVersion | La version PDF. |

### Voir aussi

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

Ouvre un document existant depuis un fichier en fournissant les options de conversion nécessaires pour obtenir un document pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Fichier d'entrée à convertir en document PDF. |
| options | LoadOptions | Représente les propriétés pour convertir *filename* en document pdf. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Ouvre un document existant depuis un flux en fournissant la conversion nécessaire pour obtenir un document pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux d'entrée à convertir en document PDF. |
| options | LoadOptions | Représente les propriétés pour convertir *input* en document PDF. |

### Voir aussi

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


