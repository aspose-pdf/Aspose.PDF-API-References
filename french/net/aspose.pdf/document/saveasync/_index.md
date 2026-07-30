---
title: "Document.SaveAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Document. Enregistre le document dans un flux avec des options d'enregistrement"
type: docs
weight: 860
url: /fr/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Enregistre le document dans un flux avec des options d'enregistrement.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| options | SaveOptions | Options d'enregistrement. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Enregistrer un document dans le flux html n'est pas pris en charge. Veuillez utiliser la méthode d'enregistrement vers le fichier. |

### Voir aussi

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Stocke le document dans un flux.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| output | Stream | Flux où le document sera stocké. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Enregistre le document dans le fichier spécifié.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Enregistrer le document de façon incrémentielle (c.-à-d. en utilisant la technique de mise à jour incrémentielle).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

## Remarques

Pour enregistrer le document de manière incrémentielle, nous devons ouvrir le fichier du document en écriture. Par conséquent, Document doit être initialisé avec un flux accessible en écriture comme dans l'extrait de code suivant : Document doc = new Document(new FileStream(\"document.pdf\", FileMode.Open, FileAccess.ReadWrite)); // apportez quelques modifications et enregistrez le document de manière incrémentielle doc.Save();

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Enregistre le document avec des options d'enregistrement.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Options d'enregistrement. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |
| format | SaveFormat | Options de format. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| format | SaveFormat | Options de format. |
| cancellationToken | CancellationToken | Jeton d'annulation |

### Valeur de retour

Tâche asynchrone.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Enregistrer un document dans le flux html n'est pas pris en charge. Veuillez utiliser la méthode d'enregistrement vers le fichier. |

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |
| options | SaveOptions | Options d'enregistrement. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


