---
title: "ComHelper.OpenStream"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode ComHelper. Initialise et renvoie une nouvelle instance de Document à partir du flux d'entrée"
type: docs
weight: 30
url: /fr/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

Initialisez et renvoyez une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document OpenStream(Stream input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |

### Valeur de retour

Objet Document

### Voir aussi

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

Initialisez et renvoyez une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document OpenStream(Stream input, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Objet flux d'entrée, le PDF correspondant est protégé par mot de passe. |
| password | String | Mot de passe utilisateur ou propriétaire. |

### Valeur de retour

Objet Document

### Voir aussi

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

Initialisez et renvoyez une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Valeur de retour

Objet Document

### Voir aussi

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

Initialisez et renvoyez une nouvelle instance de Document à partir du flux *input*.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux contenant un document PDF. |
| password | String | Mot de passe utilisateur ou propriétaire. |
| isManagedStream | Boolean | si défini sur `true`, le flux interne est fermé avant la sortie ; sinon, il ne l'est pas. |

### Valeur de retour

Objet Document

### Voir aussi

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

Ouvrez et renvoyez un document existant à partir d'un flux en fournissant la conversion nécessaire pour obtenir un document PDF.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Stream | Flux d'entrée à convertir en document PDF. |
| options | LoadOptions | Représente les propriétés pour convertir *input* en document PDF. |

### Valeur de retour

Objet Document

### Voir aussi

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


