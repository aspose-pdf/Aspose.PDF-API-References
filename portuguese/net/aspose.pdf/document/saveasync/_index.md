---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Método Document. Armazena o documento em um stream
type: docs
weight: 840
url: /pt/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Armazena o documento em um stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | Stream | Stream onde o documento será armazenado. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Salva o documento no arquivo especificado.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Salva o documento de forma incremental (ou seja, usando a técnica de atualização incremental).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

## Observações

Para salvar o documento de forma incremental, devemos abrir o arquivo do documento para escrita. Portanto, o Document deve ser inicializado com um stream gravável, como no próximo trecho de código: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // faça algumas alterações e salve o documento de forma incremental doc.Save();

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Salva o documento com opções de salvamento.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | SaveOptions | Opções de salvamento. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Salva o documento com um novo nome junto com um formato de arquivo.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |
| format | SaveFormat | Opções de formato. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Veja Também

* enum [SaveFormat](../../saveformat/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Salva o documento com um novo nome junto com um formato de arquivo.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde o documento será armazenado. |
| format | SaveFormat | Opções de formato. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

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

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Salva o documento com um novo nome definindo suas opções de salvamento.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | String | Caminho para o arquivo onde o documento será armazenado. |
| options | SaveOptions | Opções de salvamento. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Salva o documento em um stream com opções de salvamento.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde o documento será armazenado. |
| options | SaveOptions | Opções de salvamento. |
| cancellationToken | CancellationToken | Token de cancelamento. |

### Valor de Retorno

Tarefa assíncrona.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | ArgumentException quando [`HtmlSaveOptions`](../../htmlsaveoptions/) é passado para um método. Salvar um documento no stream html não é suportado. Por favor, use o método salvar para o arquivo. |

### Veja Também

* classe [SaveOptions](../../saveoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)