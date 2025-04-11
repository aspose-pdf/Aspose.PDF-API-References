---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: Método ComHelper. Apenas cria e retorna Documento usando o nome do arquivo. O mesmo que Documento
type: docs
weight: 20
url: /pt/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Apenas cria e retorna Documento usando *nome do arquivo*. O mesmo que [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | O nome do arquivo do documento pdf. |

### Valor de Retorno

Objeto Documento

### Veja Também

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Inicializa e retorna uma nova instância da classe [`Document`](../../document/) para trabalhar com documento criptografado.

```csharp
public Document OpenFile(string filename, string password)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Nome do arquivo do documento. |
| password | String | Senha do usuário ou do proprietário. |

### Valor de Retorno

Objeto Documento

### Veja Também

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Inicializa uma nova instância da classe [`Document`](../../document/) para trabalhar com documento criptografado.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Nome do arquivo do documento. |
| password | String | Senha do usuário ou do proprietário. |
| isManagedStream | Boolean | se definido como `true`, o fluxo interno é fechado antes da saída; caso contrário, não é. |

### Valor de Retorno

Objeto Documento

### Veja Também

* classe [Document](../../document/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Abre um documento existente de um arquivo fornecendo as opções de conversão necessárias para obter o documento pdf.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | String | Arquivo de entrada para converter em documento pdf. |
| options | LoadOptions | Representa propriedades para converter *nome do arquivo* em documento pdf. |

### Valor de Retorno

Objeto Documento

### Veja Também

* classe [Document](../../document/)
* classe [LoadOptions](../../loadoptions/)
* classe [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)