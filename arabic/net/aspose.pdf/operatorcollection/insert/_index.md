---
title: "OperatorCollection.Insert"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OperatorCollection. تُدرج عاملًا في المجموعة."
type: docs
weight: 140
url: /ar/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

يدرج المشغّل في المجموعة.

```csharp
public override void Insert(int index, Operator op)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | المؤشر حيث يجب إضافة العامل الجديد. |
| op | Operator | العامل الذي سيتم إدراجه. |

## أمثلة

مثال يوضح كيفية إدراج عامل إلى محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

إدراج المشغّلات في الموضع المحدد.

```csharp
public void Insert(int at, Operator[] ops)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| at | Int32 | المؤشر الذي تبدأ منه عملية إدراج العوامل. |
| ops | Operator[] | مصفوفة من العوامل التي سيتم إدراجها. يمكن لكل عامل أن يكون له أي فهرس (افتراضيًا -1) لأن فهارسهم تُضبط تلقائيًا بدءًا من *at*. |

## أمثلة

مثال يوضح كيفية إدراج عامل إلى محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

إدراج المشغّلات في الموضع المحدد.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| at | Int32 | المؤشر الذي تبدأ منه عملية إدراج العوامل. |
| ops | IList`1 | مصفوفة من العوامل التي سيتم إدراجها. |

## أمثلة

مثال يوضح كيفية إدراج العوامل إلى محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


