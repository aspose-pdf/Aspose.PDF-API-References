---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Insere operador na coleção
type: docs
weight: 140
url: /pt/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Insere operador na coleção.

```csharp
public override void Insert(int index, Operator op)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Índice onde o novo operador deve ser adicionado |
| op | Operator | Operador que será inserido |

## Exemplos

O exemplo demonstra como inserir um operador no conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Insere operadores na posição dada.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| at | Int32 | Índice a partir do qual os operadores começam a ser inseridos. |
| ops | Operator[] | Array de operadores a serem inseridos. Cada operador pode ter qualquer índice (por padrão -1) porque seus índices são ajustados automaticamente a partir de *at*. |

## Exemplos

O exemplo demonstra como inserir um operador no conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Insere operadores na posição dada.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| at | Int32 | Índice a partir do qual os operadores começam a ser inseridos. |
| ops | IList`1 | Array de operadores a serem inseridos. |

## Exemplos

O exemplo demonstra como inserir operadores no conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)