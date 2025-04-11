---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: Méthode ComHelper. Initialiser et retourner une nouvelle instance de Document à partir du flux d'entrée
type: docs
weight: 30
url: /fr/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Initialiser et retourner une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document OpenStream(Stream input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec document pdf. |

### Valeur de retour

Objet Document

### Voir aussi

* classe [Document](../../document/)
* classe [ComHelper](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Initialiser et retourner une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document OpenStream(Stream input, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Objet de flux d'entrée, le pdf correspondant est protégé par mot de passe. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Valeur de retour

Objet Document

### Voir aussi

* classe [Document](../../document/)
* classe [ComHelper](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Initialiser et retourner une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec document pdf. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Valeur de retour

Objet Document

### Voir aussi

* classe [Document](../../document/)
* classe [ComHelper](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Initialiser et retourner une nouvelle instance de Document à partir du *flux* d'entrée.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux avec document pdf. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Valeur de retour

Objet Document

### Voir aussi

* classe [Document](../../document/)
* classe [ComHelper](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Ouvrir et retourner un document existant à partir d'un flux en fournissant la conversion nécessaire pour obtenir un document pdf.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | Stream | Flux d'entrée à convertir en document pdf. |
| options | LoadOptions | Représente les propriétés pour convertir *input* en document pdf. |

### Valeur de retour

Objet Document

### Voir aussi

* classe [Document](../../document/)
* classe [LoadOptions](../../loadoptions/)
* classe [ComHelper](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)