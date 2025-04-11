---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Verifique se o formulário já possui o campo especificado
type: docs
weight: 280
url: /pt/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Verifique se o formulário já possui o campo especificado.

```csharp
public bool HasField(Field field)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| field | Field | Campo a ser verificado. |

### Valor de Retorno

`true` se o nome do campo especificado foi adicionado ao Formulário; caso contrário, `false`.

### Veja Também

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Determina se o campo com o nome especificado já foi adicionado ao Formulário.

```csharp
public bool HasField(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) do campo. |

### Valor de Retorno

`true` se o nome do campo especificado foi adicionado ao Formulário; caso contrário, `false`.

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determina se o campo com o nome especificado já foi adicionado ao Formulário, com a capacidade de procurar na hierarquia de campos filhos.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) do campo. |
| searchChildren | Boolean | Quando definido como `true`, toda a hierarquia de campos do formulário será pesquisada pelo *fieldName* solicitado (observe que, neste caso, o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) do campo requerido deve ser passado como *fieldName*). |

### Valor de Retorno

`true` se o nome do campo especificado foi adicionado ao Formulário; caso contrário, `false`.

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)