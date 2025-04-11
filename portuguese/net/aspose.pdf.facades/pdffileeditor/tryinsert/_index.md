---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Insere páginas de outro arquivo no arquivo Pdf de entrada
type: docs
weight: 420
url: /pt/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Insere páginas de outro arquivo no arquivo Pdf de entrada.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo Pdf de entrada. |
| insertLocation | Int32 | Posição de inserção no arquivo de entrada. |
| portFile | String | Páginas do arquivo Pdf. |
| pageNumber | Int32[] | O número da página do arquivo portado em portFile. |
| outputFile | String | Arquivo Pdf de saída. |

### Valor de Retorno

Verdadeiro para sucesso, ou falso.

## Observações

O método TryInsert é como o método Insert, exceto que o método TryInsert não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Insere páginas de outro arquivo no arquivo Pdf de entrada.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream do arquivo Pdf de entrada. |
| insertLocation | Int32 | Posição de inserção no arquivo de entrada. |
| portStream | Stream | Stream do arquivo Pdf para páginas. |
| pageNumber | Int32[] | O número da página do arquivo portado em portFile. |
| outputStream | Stream | Stream de saída. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryInsert é como o método Insert, exceto que o método TryInsert não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Insere o conteúdo do arquivo no arquivo de origem e armazena o resultado no objeto HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Nome do arquivo de origem. |
| insertLocation | Int32 | Número da página onde o segundo arquivo será inserido. |
| portFile | String | Caminho para o arquivo que será inserido. |
| pageNumber | Int32[] | Array de números de página no arquivo de origem que será inserido. |
| response | HttpResponse | Objeto de resposta onde o resultado será armazenado. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryInsert é como o método Insert, exceto que o método TryInsert não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Insere documento em outro documento e armazena o resultado no objeto de resposta.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Stream com o documento de origem |
| insertLocation | Int32 | Localização onde o outro documento será inserido. |
| portStream | Stream | Documento a ser inserido. |
| pageNumber | Int32[] | Array de números de página no segundo documento que será inserido. |
| response | HttpResponse | Objeto de resposta onde o resultado será armazenado. |

### Valor de Retorno

verdadeiro se a operação foi concluída com sucesso; caso contrário, falso.

## Observações

O método TryInsert é como o método Insert, exceto que o método TryInsert não lança uma exceção se a operação falhar.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)