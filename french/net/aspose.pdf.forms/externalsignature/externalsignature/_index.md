---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Constructeur ExternalSignature. Crée une signature PKCS7 détachée à l'aide d'un X509Certificate2. Il prend en charge les jetons de cartes intelligentes USB sans clés privées exportables.
type: docs
weight: 10
url: /fr/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Crée une signature PKCS#7 `(détachée)` à l'aide d'un X509Certificate2. Il prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Le certificat avec la clé privée. |

## Remarques

L'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat.

### Voir aussi

* classe [ExternalSignature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Crée une signature PKCS#7 `(détachée)` à l'aide d'un X509Certificate2. Il prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Le certificat avec la clé privée. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage pour signer un document. |

### Voir aussi

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* classe [ExternalSignature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Crée une signature PKCS#7 à l'aide d'un X509Certificate2. Il prend en charge les cartes intelligentes USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Le certificat avec la clé privée. |
| detached | Boolean | Vrai si la signature doit être détachée, sinon faux. |

## Remarques

Pour détaché défini sur faux, l'algorithme de hachage sera toujours `SHA1`. Sinon, l'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat (voir Auto).

### Voir aussi

* classe [ExternalSignature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Crée une signature PKCS#7 à l'aide d'un X509Certificate2 sous forme de chaîne base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 sous forme de chaîne base64. |
| detached | Boolean | Vrai si la signature doit être détachée, sinon faux. |

## Remarques

Pour détaché défini sur faux, l'algorithme de hachage sera toujours `SHA1`. Sinon, l'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat (voir Auto).

### Voir aussi

* classe [ExternalSignature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Crée une signature PKCS#7 `(détachée)` à l'aide d'un X509Certificate2 sous forme de chaîne base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 sous forme de chaîne base64. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage pour signer un document. |

### Voir aussi

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* classe [ExternalSignature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)