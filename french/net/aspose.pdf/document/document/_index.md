---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Constructeur de Document. Initialiser une nouvelle instance de Document à partir du flux d'entrée
type: docs
weight: 10
url: /fr/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Initialiser une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document(Stream input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec le document pdf. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Initialiser une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec le document pdf. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Initialiser une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document(Stream input, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Objet de flux d'entrée, le pdf correspondant est protégé par mot de passe. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Initialiser une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec le document pdf. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Initialiser simplement Document en utilisant *filename*. C'est la même chose que `Document`.

```csharp
public Document(string filename)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Le nom du fichier du document pdf. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Initialiser simplement Document en utilisant *filename*. C'est la même chose que `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Le nom du fichier du document pdf. |
| isManagedStream | Boolean | Si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document crypté.

```csharp
public Document(string filename, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Nom du fichier du document. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Initialise une nouvelle instance de la classe [`Document`](../) pour travailler avec un document crypté.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Nom du fichier du document. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Initialise un document vide.

```csharp
public Document()
```

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
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
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Ouvre un document existant à partir d'un fichier en fournissant les options de conversion nécessaires pour obtenir un document pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Fichier d'entrée à convertir en document pdf. |
| options | LoadOptions | Représente les propriétés pour convertir *filename* en document pdf. |

### Voir aussi

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Ouvre un document existant à partir d'un flux en fournissant les conversions nécessaires pour obtenir un document pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux d'entrée à convertir en document pdf. |
| options | LoadOptions | Représente les propriétés pour convertir *input* en document pdf. |

### Voir aussi

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)