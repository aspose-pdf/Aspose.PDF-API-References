---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Exclui operador da coleção
type: docs
weight: 110
url: /pt/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Exclui operador da coleção.

```csharp
public void Delete(int index)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Índice do operador que deve ser excluído. A numeração dos operadores começa em 1. |

## Exemplos

O exemplo demonstra como excluir um operador pelo seu índice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Veja Também

* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Exclui operadores da coleção.

```csharp
public void Delete(Operator[] ops)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ops | Operator[] | Array de operadores a serem excluídos |

## Exemplos

O exemplo demonstra como remover um operador do conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Exclui operadores da coleção.

```csharp
public void Delete(IList<Operator> list)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| list | IList`1 | A lista de operadores a serem excluídos |

## Exemplos

O exemplo demonstra como remover um operador do conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)