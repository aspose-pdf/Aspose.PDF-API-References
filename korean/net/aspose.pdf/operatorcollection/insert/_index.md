---
title: "OperatorCollection.Insert"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OperatorCollection 메서드. 연산자를 컬렉션에 삽입합니다."
type: docs
weight: 140
url: /ko/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

연산자를 컬렉션에 삽입합니다.

```csharp
public override void Insert(int index, Operator op)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 새 연산자를 추가해야 하는 인덱스 |
| op | 연산자 | 삽입될 연산자 |

## 예제

예제는 페이지 내용에 연산자를 삽입하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

주어진 위치에 연산자를 삽입합니다.

```csharp
public void Insert(int at, Operator[] ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| at | Int32 | 연산자를 삽입하기 시작하는 인덱스. |
| ops | Operator[] | 삽입될 연산자 배열입니다. 각 연산자는 (기본값 -1) 어떤 인덱스라도 가질 수 있으며, 인덱스는 *at*부터 자동으로 조정됩니다. |

## 예제

예제는 페이지 내용에 연산자를 삽입하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

주어진 위치에 연산자를 삽입합니다.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| at | Int32 | 연산자를 삽입하기 시작하는 인덱스. |
| ops | IList`1 | 삽입될 연산자 배열. |

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

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


