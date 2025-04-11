---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 메서드. 컬렉션에 연산자를 삽입합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

컬렉션에 연산자를 삽입합니다.

```csharp
public override void Insert(int index, Operator op)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 새 연산자를 추가해야 하는 인덱스 |
| op | Operator | 삽입될 연산자 |

## 예제

예제는 페이지 내용에 연산자를 삽입하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

주어진 위치에 연산자를 삽입합니다.

```csharp
public void Insert(int at, Operator[] ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| at | Int32 | 연산자를 삽입하기 시작하는 인덱스. |
| ops | Operator[] | 삽입될 연산자의 배열. 각 연산자는 임의의 인덱스를 가질 수 있으며(기본값 -1) 인덱스는 *at*에서 시작하여 자동으로 조정됩니다. |

## 예제

예제는 페이지 내용에 연산자를 삽입하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

주어진 위치에 연산자를 삽입합니다.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| at | Int32 | 연산자를 삽입하기 시작하는 인덱스. |
| ops | IList`1 | 삽입될 연산자의 배열. |

## 예제

예제는 페이지 내용에 연산자를 삽입하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)