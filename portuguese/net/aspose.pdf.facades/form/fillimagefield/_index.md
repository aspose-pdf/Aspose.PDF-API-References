---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Método do formulário. Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado
type: docs
weight: 150
url: /pt/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome de campo totalmente qualificado do campo de botão de imagem. |
| imageFileName | String | O caminho do arquivo de imagem, relativo e absoluto são ambos aceitáveis. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Sobrecarga da função FillImageField. A entrada é um fluxo de imagem.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome de campo totalmente qualificado. |
| imageStream | Stream | O fluxo da imagem. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)