---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Adiciona campo no formulário
type: docs
weight: 190
url: /pt/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Adiciona campo no formulário.

```csharp
public void Add(Field field, int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| field | Field | Campo que deve ser adicionado. |
| pageNumber | Int32 | Índice da página onde o campo adicionado será colocado. |

### Veja Também

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Adiciona campo no formulário.

```csharp
public void Add(Field field)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| field | Field | Campo que deve ser adicionado. |

### Veja Também

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Adiciona novo campo ao formulário; Se este campo já estiver colocado em outro ou neste formulário, uma cópia do campo é criada.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| field | Field | Nome do campo. |
| partialName | String | Nome do campo no formulário. |
| pageNumber | Int32 | Número da página onde o campo será adicionado. |

### Valor de Retorno

Campo adicionado retornado. Se uma cópia do campo foi criada, ela será retornada.

### Veja Também

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)