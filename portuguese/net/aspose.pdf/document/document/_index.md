---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Construtor de Document. Inicializa uma nova instância de Document a partir do fluxo de entrada
type: docs
weight: 10
url: /pt/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Inicializa uma nova instância de Document a partir do *fluxo* de entrada.

```csharp
public Document(Stream input)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | Stream | Fluxo com o documento pdf. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Inicializa uma nova instância de Document a partir do *fluxo* de entrada.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | Stream | Fluxo com o documento pdf. |
| isManagedStream | Boolean | se definido como `true`, o fluxo interno é fechado antes da saída; caso contrário, não é. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Inicializa uma nova instância de Document a partir do *fluxo* de entrada.

```csharp
public Document(Stream input, string password)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | Stream | Objeto de fluxo de entrada, o pdf correspondente está protegido por senha. |
| password | String | Senha do usuário ou do proprietário. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Inicializa uma nova instância de Document a partir do *fluxo* de entrada.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | Stream | Fluxo com o documento pdf. |
| password | String | Senha do usuário ou do proprietário. |
| isManagedStream | Boolean | Se definido como `true`, o fluxo interno é fechado antes da saída; caso contrário, não é. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Apenas inicializa Document usando *nome do arquivo*. O mesmo que `Document`.

```csharp
public Document(string filename)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | O nome do arquivo do documento pdf. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Apenas inicializa Document usando *nome do arquivo*. O mesmo que `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | O nome do arquivo do documento pdf. |
| isManagedStream | Boolean | Se definido como `true`, o fluxo interno é fechado antes da saída; caso contrário, não é. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Inicializa uma nova instância da classe [`Document`](../) para trabalhar com documento criptografado.

```csharp
public Document(string filename, string password)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Nome do arquivo do documento. |
| password | String | Senha do usuário ou do proprietário. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Inicializa uma nova instância da classe [`Document`](../) para trabalhar com documento criptografado.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Nome do arquivo do documento. |
| password | String | Senha do usuário ou do proprietário. |
| isManagedStream | Boolean | se definido como `true`, o fluxo interno é fechado antes da saída; caso contrário, não é. |

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Inicializa um documento vazio.

```csharp
public Document()
```

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Inicializa um documento vazio pela versão.

```csharp
public Document(PdfVersion version)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| version | PdfVersion | A versão do PDF. |

### Veja Também

* enum [PdfVersion](../../pdfversion/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Abre um documento existente de um arquivo fornecendo as opções de conversão necessárias para obter o documento pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Arquivo de entrada para converter em documento pdf. |
| options | LoadOptions | Representa propriedades para converter *filename* em documento pdf. |

### Veja Também

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Abre um documento existente de um fluxo fornecendo a conversão necessária para obter o documento pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | Stream | Fluxo de entrada para converter em documento pdf. |
| options | LoadOptions | Representa propriedades para converter *input* em documento pdf. |

### Veja Também

* classe [LoadOptions](../../loadoptions/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)