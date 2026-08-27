---
title: "Document.Save"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Document. Enregistre le document dans un flux avec des options d'enregistrement"
type: docs
weight: 850
url: /fr/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

Enregistre le document dans un flux avec des options d'enregistrement.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| options | SaveOptions | Options d'enregistrement. |

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

## Save(Stream) {#save_2}

Stocke le document dans un flux.

```csharp
public void Save(Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| output | Stream | Flux où le document sera stocké. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Enregistre le document dans le fichier spécifié.

```csharp
public void Save(string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Enregistrer le document de façon incrémentielle (c.-à-d. en utilisant la technique de mise à jour incrémentielle).

```csharp
public void Save()
```

## Remarques

Pour enregistrer le document de manière incrémentielle, nous devons ouvrir le fichier du document en écriture. Par conséquent, Document doit être initialisé avec un flux accessible en écriture comme dans l'extrait de code suivant : Document doc = new Document(new FileStream(\"document.pdf\", FileMode.Open, FileAccess.ReadWrite)); // apportez quelques modifications et enregistrez le document de manière incrémentielle doc.Save();

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Enregistre le document avec des options d'enregistrement.

```csharp
public void Save(SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Options d'enregistrement. |

### Voir aussi

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |
| format | SaveFormat | Options de format. |

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier.

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
| ArgumentException | ArgumentException lorsque [`HtmlSaveOptions`](../../htmlsaveoptions/) est passé à une méthode. Enregistrer un document dans le flux html n'est pas pris en charge. Veuillez utiliser la méthode d'enregistrement vers le fichier. |

### Voir aussi

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | String | Chemin du fichier où le document sera stocké. |
| options | SaveOptions | Options d'enregistrement. |

### Voir aussi

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


