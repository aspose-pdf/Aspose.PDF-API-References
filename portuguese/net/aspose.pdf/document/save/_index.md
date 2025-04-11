---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Método Document. Armazena o documento em um stream
type: docs
weight: 830
url: /pt/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Armazena o documento em um stream.

```csharp
public void Save(Stream output)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | Stream | Stream onde o documento será armazenado. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Salva o documento no arquivo especificado.

```csharp
public void Save(string outputFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Salva o documento de forma incremental (ou seja, usando a técnica de atualização incremental).

```csharp
public void Save()
```

## Observações

Para salvar o documento de forma incremental, devemos abrir o arquivo do documento para escrita. Portanto, o Document deve ser inicializado com um stream gravável, como no próximo trecho de código: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // faça algumas alterações e salve o documento de forma incremental doc.Save();

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Salva o documento com opções de salvamento.

```csharp
public void Save(SaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | SaveOptions | Opções de salvamento. |

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Salva o documento com um novo nome junto com um formato de arquivo.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |
| format | SaveFormat | Opções de formato. |

### Veja Também

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Salva o documento com um novo nome junto com um formato de arquivo.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde o documento será armazenado. |
| format | SaveFormat | Opções de formato. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) é passado para um método. Salvar um documento no stream html não é suportado. Por favor, use o método salvar para o arquivo. |

### Veja Também

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Salva o documento com um novo nome definindo suas opções de salvamento.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |
| options | SaveOptions | Opções de salvamento. |

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Salva o documento em um stream com opções de salvamento.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde o documento será armazenado. |
| options | SaveOptions | Opções de salvamento. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) é passado para um método. Salvar um documento no stream html não é suportado. Por favor, use o método salvar para o arquivo. |

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)