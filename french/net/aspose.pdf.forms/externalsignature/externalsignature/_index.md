---
title: "ExternalSignature.ExternalSignature"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur ExternalSignature. Crée une signature PKCS7 détachée en utilisant un X509Certificate2. Il prend en charge les jetons de cartes à puce USB sans clés privées exportables"
type: docs
weight: 10
url: /fr/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Crée une signature PKCS#7 `(detached)` détachée en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificat | X509Certificate2 | Le certificat avec la clé privée. |

## Remarques

L'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat.

### Voir aussi

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Crée une signature PKCS#7 `(detached)` détachée en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificat | X509Certificate2 | Le certificat avec la clé privée. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage pour signer un document. |

### Voir aussi

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Crée une signature PKCS#7 détachée en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| certificat | X509Certificate2 | Le certificat avec la clé privée. |
| détaché | Boolean | Vrai si la signature doit être détachée, sinon faux. |

## Remarques

Lorsque détaché est réglé sur false, l'algorithme de hachage sera toujours `SHA1`. Sinon, l'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat (voir Auto).

### Voir aussi

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Crée une signature PKCS#7 en utilisant un X509Certificate2 sous forme de chaîne base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 en tant que chaîne base64. |
| détaché | Boolean | Vrai si la signature doit être détachée, sinon faux. |

## Remarques

Lorsque détaché est réglé sur false, l'algorithme de hachage sera toujours `SHA1`. Sinon, l'algorithme de hachage sera automatiquement sélectionné en fonction des données de clé du certificat (voir Auto).

### Voir aussi

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Crée une signature PKCS#7 `(detached)` détachée en utilisant un X509Certificate2 sous forme de chaîne base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 en tant que chaîne base64. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage pour signer un document. |

### Voir aussi

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


