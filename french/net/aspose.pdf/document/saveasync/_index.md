---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Stocke le document dans un flux
type: docs
weight: 840
url: /fr/net/aspose.pdf/document/saveasync/
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

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Sauvegarde le document dans le fichier spécifié.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Sauvegarde le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

## Remarques

Pour sauvegarder le document de manière incrémentielle, nous devons ouvrir le fichier du document en écriture. Par conséquent, le Document doit être initialisé avec un flux écrivable comme dans l'extrait de code suivant : Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apporter des modifications et sauvegarder le document de manière incrémentielle doc.Save();

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Sauvegarde le document avec des options de sauvegarde.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Options de sauvegarde. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |
| format | SaveFormat | Options de format. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| format | SaveFormat | Options de format. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Sauvegarder un document dans le flux html n'est pas supporté. Veuillez utiliser la méthode de sauvegarde dans le fichier. |

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Sauvegarde le document avec un nouveau nom en définissant ses options de sauvegarde.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |
| options | SaveOptions | Options de sauvegarde. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Sauvegarde le document dans un flux avec des options de sauvegarde.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| options | SaveOptions | Options de sauvegarde. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Tâche asynchrone.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Sauvegarder un document dans le flux html n'est pas supporté. Veuillez utiliser la méthode de sauvegarde dans le fichier. |

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)