---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Método OperatorCollection. Adiciona novo operador à coleção
type: docs
weight: 60
url: /pt/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Adiciona novo operador à coleção.

```csharp
public override void Add(Operator op)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| op | Operator | Operador que deve ser adicionado |

## Exemplos

O exemplo demonstra como adicionar operadores ao final de page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Adiciona operadores ao final dos operadores de conteúdo.

```csharp
public void Add(Operator[] ops)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ops | Operator[] | Array de operadores a serem adicionados. Cada operador pode ter qualquer índice (por padrão -1) porque eles vão para o final dos operadores de conteúdo, ou seja, os índices são atribuídos automaticamente. |

## Exemplos

O exemplo demonstra como adicionar operador ao final do conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Adiciona à coleção todos os operadores de outra coleção.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ops | ICollection`1 | coleção que contém operadores que serão adicionados. |

## Exemplos

O exemplo demonstra como adicionar coleção de operadores ao conteúdo da página.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)