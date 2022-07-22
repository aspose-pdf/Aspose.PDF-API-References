---
title: Save
second_title: Référence de l'API Aspose.PDF pour .NET
description: Enregistrer le document de manière incrémentielle cest-à-dire en utilisant la technique de mise à jour incrémentielle.
type: docs
weight: 720
url: /fr/net/aspose.pdf/document/save/
---
## Save() {#save}

Enregistrer le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle).

```csharp
public void Save()
```

### Remarques

Afin d'enregistrer le document de manière incrémentielle, nous devons ouvrir le fichier du document pour l'écriture. Par conséquent, le document doit être initialisé avec un flux inscriptible comme dans l'extrait de code suivant : Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // apportez quelques modifications et enregistrez le document par incrémentation doc.Save();

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Enregistre le document avec les options d'enregistrement.

```csharp
public void Save(SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | SaveOptions | Enregistrer les options. |

### Voir également

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Enregistre le document sous un nouveau nom avec un format de fichier.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFileName | String | Chemin d'accès au fichier où le document sera stocké. |
| format | SaveFormat | Options de mise en forme. |

### Voir également

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Enregistre le document sous un nouveau nom avec un format de fichier.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| format | SaveFormat | Options de mise en forme. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque[`HtmlSaveOptions`](../../htmlsaveoptions) est passé à une méthode. L'enregistrement d'un document dans le flux html n'est pas pris en charge. Veuillez utiliser la méthode d'enregistrement dans le fichier. |

### Voir également

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Enregistre le document avec un nouveau nom en définissant ses options d'enregistrement.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFileName | String | Chemin d'accès au fichier où le document sera stocké. |
| options | SaveOptions | Enregistrer les options. |

### Voir également

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Enregistre le document dans un flux avec des options d'enregistrement.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document sera stocké. |
| options | SaveOptions | Enregistrer les options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | ArgumentException lorsque[`HtmlSaveOptions`](../../htmlsaveoptions) est passé à une méthode. L'enregistrement d'un document dans le flux html n'est pas pris en charge. Veuillez utiliser la méthode d'enregistrement dans le fichier. |

### Voir également

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Enregistre le document dans un flux de réponse avec des options d'enregistrement.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| response | HttpResponse | Encapsule les informations de réponse HTTP. |
| outputFileName | String | Nom de fichier simple, c'est-à-dire sans chemin. |
| disposition | ContentDisposition | Représente un en-tête Content-Disposition du protocole MIME. |
| options | SaveOptions | Enregistrer les options. |

### Voir également

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Stocke le document dans le flux.

```csharp
public void Save(Stream output)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| output | Stream | Flux où le shell du document doit être stocké. |

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Enregistre le document dans le fichier spécifié.

```csharp
public void Save(string outputFileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFileName | String | Chemin d'accès au fichier où le document sera stocké. |

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Pdf](../../document)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
