---
title: "OperatorCollection.Add"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OperatorCollection 메서드. 새 연산자를 컬렉션에 추가합니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

새 연산자를 컬렉션에 추가합니다.

```csharp
public override void Add(Operator op)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| op | 연산자 | 추가해야 하는 연산자 |

## 예제

예제는 page.contents의 끝에 연산자를 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

내용 연산자의 끝에 연산자를 추가합니다.

```csharp
public void Add(Operator[] ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ops | Operator[] | 추가될 연산자 배열입니다. 각 연산자는 (기본값 -1) 어떤 인덱스라도 가질 수 있으며, 내용 연산자의 끝에 배치되므로 인덱스가 자동으로 할당됩니다. |

## 예제

예제는 페이지 내용의 끝에 연산자를 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

다른 컬렉션의 모든 연산자를 컬렉션에 추가합니다.

```csharp
public void Add(ICollection<Operator> ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ops | ICollection`1 | 추가될 연산자를 포함하는 컬렉션. |

## 예제

예제는 연산자 컬렉션을 페이지 내용에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


