---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 메서드. 컬렉션에 새로운 연산자를 추가합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

컬렉션에 새로운 연산자를 추가합니다.

```csharp
public override void Add(Operator op)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| op | Operator | 추가해야 하는 연산자 |

## 예제

예제는 페이지.contents의 끝에 연산자를 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

내용 연산자의 끝에 연산자를 추가합니다.

```csharp
public void Add(Operator[] ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ops | Operator[] | 추가할 연산자의 배열. 각 연산자는 어떤 인덱스를 가질 수 있으며(기본값 -1) 내용 연산자의 끝에 오기 때문에 인덱스는 자동으로 할당됩니다. |

## 예제

예제는 페이지 내용의 끝에 연산자를 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

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

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)