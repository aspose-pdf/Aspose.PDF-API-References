---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Stocke le document dans un flux
type: docs
weight: 830
url: /fr/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Stocke le document dans un flux.

```csharp
public void Save(Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| output | Stream | Flux où le document sera stocké. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Sauvegarde le document dans le fichier spécifié.

```csharp
public void Save(string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Sauvegarde le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle).

```csharp
public void Save()
```

## Remarques

Pour sauvegarder le document de manière incrémentielle, nous devons ouvrir le fichier du document en écriture. Par conséquent, le Document doit être initialisé avec un flux écrivable comme dans l'extrait de code suivant : Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apporter des modifications et sauvegarder le document de manière incrémentielle doc.Save();

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Sauvegarde le document avec des options de sauvegarde.

```csharp
public void Save(SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Options de sauvegarde. |

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |
| format | SaveFormat | Options de format. |

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| format | SaveFormat | Options de format. |

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

## Save(string, SaveOptions) {#save_7}

Sauvegarde le document avec un nouveau nom en définissant ses options de sauvegarde.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin vers le fichier où le document sera stocké. |
| options | SaveOptions | Options de sauvegarde. |

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Sauvegarde le document dans un flux avec des options de sauvegarde.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| options | SaveOptions | Options de sauvegarde. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Sauvegarder un document dans le flux html n'est pas supporté. Veuillez utiliser la méthode de sauvegarde dans le fichier. |

### Voir aussi

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)