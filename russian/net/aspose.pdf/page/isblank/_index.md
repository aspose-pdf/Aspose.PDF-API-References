---
title: "Page.IsBlank"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Page. Получает флаг, указывающий, пустая ли страница"
type: docs
weight: 490
url: /ru/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Получает флаг, указывающий, пустая страница или нет.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillThresholdFactor | Double | Значение порога заполнения, которое управляет чувствительностью обнаружения. Должно находиться в диапазоне [0..1). |

### Возвращаемое значение

True — если страница пустая; иначе false.

## Примечания

Чтобы определить, пустая ли страница, вычисляется отношение заполненного пространства к общему пространству страницы. Это отношение сравнивается с параметром fillThresholdFactor, и если оно меньше, страница считается пустой.

### См. также

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


