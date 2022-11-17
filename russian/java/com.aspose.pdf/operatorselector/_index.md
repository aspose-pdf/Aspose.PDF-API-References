---
title: OperatorSelector
second_title: Aspose.PDF для справки по Java API
description: Этот класс используется для выбора операторов с использованием идеи шаблона посетителя.
type: docs
weight: 234
url: /ru/java/com.aspose.pdf/operatorselector/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.pdf.IOperatorSelector](../../com.aspose.pdf/ioperatorselector)
```
public final class OperatorSelector implements IOperatorSelector
```

Этот класс используется для выбора операторов с использованием идеи шаблона посетителя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OperatorSelector()](#OperatorSelector--) | Инициализирует новый экземпляр класса Selector. |
| [OperatorSelector(Operator op)](#OperatorSelector-com.aspose.pdf.Operator-) | Инициализирует новый OperatorSelector . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSelected()](#getSelected--) | Список выбранных объектов. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(BDC BDC)](#visit-com.aspose.pdf.operators.BDC-) | Посетите/выберите оператора BDC. |
| [visit(BI BI)](#visit-com.aspose.pdf.operators.BI-) | Посетите/выберите оператора BI. |
| [visit(BMC BMC)](#visit-com.aspose.pdf.operators.BMC-) | Посетите/выберите оператора BMC. |
| [visit(BT BT)](#visit-com.aspose.pdf.operators.BT-) | Посетите/выберите оператора BT. |
| [visit(BX BX)](#visit-com.aspose.pdf.operators.BX-) | Посетите/выберите оператора BX. |
| [visit(Clip W)](#visit-com.aspose.pdf.operators.Clip-) | Посетите/выберите оператора W. |
| [visit(ClosePath h)](#visit-com.aspose.pdf.operators.ClosePath-) | Посетите/выберите оператора h. |
| [visit(ClosePathEOFillStroke b_)](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | Посетите/выберите б\* оператор. |
| [visit(ClosePathFillStroke b)](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | Посетите/выберите оператора b. |
| [visit(ClosePathStroke s)](#visit-com.aspose.pdf.operators.ClosePathStroke-) | Посетите/выберите оператора. |
| [visit(ConcatenateMatrix cm)](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | Посетите/выберите оператора cm. |
| [visit(CurveTo c)](#visit-com.aspose.pdf.operators.CurveTo-) | Посетите/выберите c оператора. |
| [visit(CurveTo1 v)](#visit-com.aspose.pdf.operators.CurveTo1-) | Посетите/выберите v оператора. |
| [visit(CurveTo2 y)](#visit-com.aspose.pdf.operators.CurveTo2-) | Посетите/выберите оператора y. |
| [visit(DP DP)](#visit-com.aspose.pdf.operators.DP-) | Посетите/выберите оператора DP. |
| [visit(Do Do)](#visit-com.aspose.pdf.operators.Do-) | Посетите/выберите оператора Do. |
| [visit(EI EI)](#visit-com.aspose.pdf.operators.EI-) | Посетите/выберите оператора EI. |
| [visit(EMC EMC)](#visit-com.aspose.pdf.operators.EMC-) | Посетите/выберите оператора EMC. |
| [visit(EOClip W_)](#visit-com.aspose.pdf.operators.EOClip-) | Посетите/выберите W\* оператор. |
| [visit(EOFill f_)](#visit-com.aspose.pdf.operators.EOFill-) | Посетите/выберите оператора f\*. |
| [visit(EOFillStroke B_)](#visit-com.aspose.pdf.operators.EOFillStroke-) | Посетите/выберите B\* оператор. |
| [visit(ET ET)](#visit-com.aspose.pdf.operators.ET-) | Посетите/выберите оператора ET. |
| [visit(EX EX)](#visit-com.aspose.pdf.operators.EX-) | Посетите/выберите оператора EX. |
| [visit(EndPath n)](#visit-com.aspose.pdf.operators.EndPath-) | Посетите/выберите оператора. |
| [visit(Fill f)](#visit-com.aspose.pdf.operators.Fill-) | Посетите/выберите f оператора. |
| [visit(FillStroke B)](#visit-com.aspose.pdf.operators.FillStroke-) | Посетите/выберите оператора B. |
| [visit(GRestore Q)](#visit-com.aspose.pdf.operators.GRestore-) | Посетите/выберите оператора Q. |
| [visit(GS gs)](#visit-com.aspose.pdf.operators.GS-) | Посетите/выберите оператора gs. |
| [visit(GSave q)](#visit-com.aspose.pdf.operators.GSave-) | Посетите/выберите оператора q. |
| [visit(ID ID)](#visit-com.aspose.pdf.operators.ID-) | Посетите/выберите ID оператора. |
| [visit(LineTo l)](#visit-com.aspose.pdf.operators.LineTo-) | Посетите/выберите l оператора. |
| [visit(MP MP)](#visit-com.aspose.pdf.operators.MP-) | Посетите/выберите оператора MP. |
| [visit(MoveTextPosition Td)](#visit-com.aspose.pdf.operators.MoveTextPosition-) | Посетите/выберите оператора Td. |
| [visit(MoveTextPositionSetLeading TD)](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | Посетите/выберите оператора ТД. |
| [visit(MoveTo m)](#visit-com.aspose.pdf.operators.MoveTo-) | Посетите/выберите m оператора. |
| [visit(MoveToNextLine T_)](#visit-com.aspose.pdf.operators.MoveToNextLine-) | Посетите/выберите T\* оператор. |
| [visit(MoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | Посетите/выберите ' оператора. |
| [visit(ObsoleteFill F)](#visit-com.aspose.pdf.operators.ObsoleteFill-) | Посетите/выберите оператора F. |
| [visit(Re re)](#visit-com.aspose.pdf.operators.Re-) | Посетите/выберите оператора re. |
| [visit(SelectFont Tf)](#visit-com.aspose.pdf.operators.SelectFont-) | Посетите/выберите оператора Tf. |
| [visit(SetAdvancedColor scn)](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | Посетите/выберите оператора scn. |
| [visit(SetAdvancedColorStroke SCN)](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | Посетите/выберите оператора SCN. |
| [visit(SetCMYKColor k)](#visit-com.aspose.pdf.operators.SetCMYKColor-) | Посетите/выберите оператора k. |
| [visit(SetCMYKColorStroke K)](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | Посетите/выберите оператора K. |
| [visit(SetCharWidth d0)](#visit-com.aspose.pdf.operators.SetCharWidth-) | Посетите/выберите оператора d0. |
| [visit(SetCharWidthBoundingBox d1)](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | Посетите/выберите оператора d1. |
| [visit(SetCharacterSpacing Tc)](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | Посетите/выберите оператора Tc. |
| [visit(SetColor sc)](#visit-com.aspose.pdf.operators.SetColor-) | Посетите/выберите оператора sc. |
| [visit(SetColorRenderingIntent ri)](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | Посетите/выберите оператора ri. |
| [visit(SetColorSpace cs)](#visit-com.aspose.pdf.operators.SetColorSpace-) | Посетите/выберите оператора cs. |
| [visit(SetColorSpaceStroke CS)](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | Посетите/выберите оператора CS. |
| [visit(SetColorStroke SC)](#visit-com.aspose.pdf.operators.SetColorStroke-) | Посетите/выберите оператора СЦ. |
| [visit(SetDash d)](#visit-com.aspose.pdf.operators.SetDash-) | Посетите/выберите оператора d. |
| [visit(SetFlat i)](#visit-com.aspose.pdf.operators.SetFlat-) | Посетите/выберите i оператора. |
| [visit(SetGlyphsPositionShowText TJ)](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | Посетите/выберите оператора TJ. |
| [visit(SetGray g)](#visit-com.aspose.pdf.operators.SetGray-) | Посетите/выберите оператора g. |
| [visit(SetGrayStroke G)](#visit-com.aspose.pdf.operators.SetGrayStroke-) | Посетите/выберите оператора G. |
| [visit(SetHorizontalTextScaling Tz)](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | Посетите/выберите оператора Tz. |
| [visit(SetLineCap J)](#visit-com.aspose.pdf.operators.SetLineCap-) | Посетите/выберите оператора J. |
| [visit(SetLineJoin j)](#visit-com.aspose.pdf.operators.SetLineJoin-) | Посетите/выберите оператора j. |
| [visit(SetLineWidth w)](#visit-com.aspose.pdf.operators.SetLineWidth-) | Посетите/выберите w оператора. |
| [visit(SetMiterLimit M)](#visit-com.aspose.pdf.operators.SetMiterLimit-) | Посетите/выберите оператора М. |
| [visit(SetRGBColor rg)](#visit-com.aspose.pdf.operators.SetRGBColor-) | Посетите/выберите оператора rg. |
| [visit(SetRGBColorStroke RG)](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | Посетите/выберите оператора RG. |
| [visit(SetSpacingMoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | Посетите/выберите '' оператора. |
| [visit(SetTextLeading TL)](#visit-com.aspose.pdf.operators.SetTextLeading-) | Посетите/выберите оператора TL. |
| [visit(SetTextMatrix Tm)](#visit-com.aspose.pdf.operators.SetTextMatrix-) | Посетите/выберите оператора Tm. |
| [visit(SetTextRenderingMode Tr)](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | Посетите/выберите оператора Tr. |
| [visit(SetTextRise Ts)](#visit-com.aspose.pdf.operators.SetTextRise-) | Посетите/выберите оператора Ts. |
| [visit(SetWordSpacing Tw)](#visit-com.aspose.pdf.operators.SetWordSpacing-) | Посетите/выберите оператора Tw. |
| [visit(ShFill sh)](#visit-com.aspose.pdf.operators.ShFill-) | Посетите/выберите оператора sh. |
| [visit(ShowText Tj)](#visit-com.aspose.pdf.operators.ShowText-) | Посетите/выберите оператора Tj. |
| [visit(Stroke S)](#visit-com.aspose.pdf.operators.Stroke-) | Посетите/выберите оператора S. |
| [visit(TextOperator textOperator)](#visit-com.aspose.pdf.operators.TextOperator-) | Посетите/выберите любой текстовый оператор оператора. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OperatorSelector() {#OperatorSelector--}
```
public OperatorSelector()
```


Инициализирует новый экземпляр класса Selector.

### OperatorSelector(Operator op) {#OperatorSelector-com.aspose.pdf.Operator-}
```
public OperatorSelector(Operator op)
```


Инициализирует новый OperatorSelector .

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор для посещения/выбора. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getSelected() {#getSelected--}
```
public List<Operator> getSelected()
```


Список выбранных объектов.

**Возвращает:**
java.util.List<com.aspose.pdf.Operator> — Список экземпляров оператора
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visit(BDC BDC) {#visit-com.aspose.pdf.operators.BDC-}
```
public void visit(BDC BDC)
```


Посетите/выберите оператора BDC.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| BDC | [BDC](../../com.aspose.pdf.operators/bdc) | Начать оператор последовательности помеченного содержимого (со списком свойств). |

### visit(BI BI) {#visit-com.aspose.pdf.operators.BI-}
```
public void visit(BI BI)
```


Посетите/выберите оператора BI.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| BI | [BI](../../com.aspose.pdf.operators/bi) | Начать встроенный оператор объекта изображения. |

### visit(BMC BMC) {#visit-com.aspose.pdf.operators.BMC-}
```
public void visit(BMC BMC)
```


Посетите/выберите оператора BMC.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| BMC | [BMC](../../com.aspose.pdf.operators/bmc) | Оператор последовательности начала помеченного содержимого. |

### visit(BT BT) {#visit-com.aspose.pdf.operators.BT-}
```
public void visit(BT BT)
```


Посетите/выберите оператора BT.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| BT | [BT](../../com.aspose.pdf.operators/bt) | Оператор начала текстового объекта. |

### visit(BX BX) {#visit-com.aspose.pdf.operators.BX-}
```
public void visit(BX BX)
```


Посетите/выберите оператора BX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| BX | [BX](../../com.aspose.pdf.operators/bx) | Начать оператор раздела совместимости. |

### visit(Clip W) {#visit-com.aspose.pdf.operators.Clip-}
```
public void visit(Clip W)
```


Посетите/выберите оператора W.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| W | [Clip](../../com.aspose.pdf.operators/clip) | Установить оператор пути отсечения (правило ненулевого числа витков). |

### visit(ClosePath h) {#visit-com.aspose.pdf.operators.ClosePath-}
```
public void visit(ClosePath h)
```


Посетите/выберите оператора h.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| h | [ClosePath](../../com.aspose.pdf.operators/closepath) | Оператор закрытия подпути. |

### visit(ClosePathEOFillStroke b_) {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
```
public void visit(ClosePathEOFillStroke b_)
```


Посетите/выберите б\* оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| b_ | [ClosePathEOFillStroke](../../com.aspose.pdf.operators/closepatheofillstroke) | Оператор закрытия, заполнения и обводки контура (четное-нечетное правило). |

### visit(ClosePathFillStroke b) {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
```
public void visit(ClosePathFillStroke b)
```


Посетите/выберите оператора b.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| b | [ClosePathFillStroke](../../com.aspose.pdf.operators/closepathfillstroke) | Оператор закрытия, заполнения и обводки пути (правило ненулевого числа витков). |

### visit(ClosePathStroke s) {#visit-com.aspose.pdf.operators.ClosePathStroke-}
```
public void visit(ClosePathStroke s)
```


Посетите/выберите оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | [ClosePathStroke](../../com.aspose.pdf.operators/closepathstroke) | Закрыть и обвести оператор пути. |

### visit(ConcatenateMatrix cm) {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
```
public void visit(ConcatenateMatrix cm)
```


Посетите/выберите оператора cm.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cm | [ConcatenateMatrix](../../com.aspose.pdf.operators/concatenatematrix) | Объединить матрицу с текущим оператором матрицы преобразования. |

### visit(CurveTo c) {#visit-com.aspose.pdf.operators.CurveTo-}
```
public void visit(CurveTo c)
```


Посетите/выберите c оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [CurveTo](../../com.aspose.pdf.operators/curveto) | Добавить криволинейный сегмент к оператору пути (три контрольные точки). |

### visit(CurveTo1 v) {#visit-com.aspose.pdf.operators.CurveTo1-}
```
public void visit(CurveTo1 v)
```


Посетите/выберите v оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [CurveTo1](../../com.aspose.pdf.operators/curveto1) | Добавить криволинейный сегмент к оператору пути (исходная точка повторяется). |

### visit(CurveTo2 y) {#visit-com.aspose.pdf.operators.CurveTo2-}
```
public void visit(CurveTo2 y)
```


Посетите/выберите оператора y.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| y | [CurveTo2](../../com.aspose.pdf.operators/curveto2) | Добавить криволинейный сегмент к оператору пути (повторяется конечная точка). |

### visit(DP DP) {#visit-com.aspose.pdf.operators.DP-}
```
public void visit(DP DP)
```


Посетите/выберите оператора DP.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| DP | [DP](../../com.aspose.pdf.operators/dp) | Определить оператор точки отмеченного содержимого (со списком свойств). |

### visit(Do Do) {#visit-com.aspose.pdf.operators.Do-}
```
public void visit(Do Do)
```


Посетите/выберите оператора Do.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Do | [Do](../../com.aspose.pdf.operators/do) | Вызвать именованный оператор XObject. |

### visit(EI EI) {#visit-com.aspose.pdf.operators.EI-}
```
public void visit(EI EI)
```


Посетите/выберите оператора EI.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| EI | [EI](../../com.aspose.pdf.operators/ei) | Завершить встроенный оператор объекта изображения. |

### visit(EMC EMC) {#visit-com.aspose.pdf.operators.EMC-}
```
public void visit(EMC EMC)
```


Посетите/выберите оператора EMC.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| EMC | [EMC](../../com.aspose.pdf.operators/emc) | Конец оператора последовательности помеченного содержимого. |

### visit(EOClip W_) {#visit-com.aspose.pdf.operators.EOClip-}
```
public void visit(EOClip W_)
```


Посетите/выберите W\* оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| W_ | [EOClip](../../com.aspose.pdf.operators/eoclip) | Установить оператор пути отсечения (четное-нечетное правило). |

### visit(EOFill f_) {#visit-com.aspose.pdf.operators.EOFill-}
```
public void visit(EOFill f_)
```


Посетите/выберите оператора f\*.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| f_ | [EOFill](../../com.aspose.pdf.operators/eofill) | Оператор заполнения пути (четное-нечетное правило). |

### visit(EOFillStroke B_) {#visit-com.aspose.pdf.operators.EOFillStroke-}
```
public void visit(EOFillStroke B_)
```


Посетите/выберите B\* оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| B_ | [EOFillStroke](../../com.aspose.pdf.operators/eofillstroke) | Оператор заполнения и обводки пути (четное-нечетное правило). |

### visit(ET ET) {#visit-com.aspose.pdf.operators.ET-}
```
public void visit(ET ET)
```


Посетите/выберите оператора ET.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ET | [ET](../../com.aspose.pdf.operators/et) | Оператор завершения текстового объекта. |

### visit(EX EX) {#visit-com.aspose.pdf.operators.EX-}
```
public void visit(EX EX)
```


Посетите/выберите оператора EX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| EX | [EX](../../com.aspose.pdf.operators/ex) | Конец оператора раздела совместимости. |

### visit(EndPath n) {#visit-com.aspose.pdf.operators.EndPath-}
```
public void visit(EndPath n)
```


Посетите/выберите оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | [EndPath](../../com.aspose.pdf.operators/endpath) | Оператор конечного пути (без заполнения или обводки). |

### visit(Fill f) {#visit-com.aspose.pdf.operators.Fill-}
```
public void visit(Fill f)
```


Посетите/выберите f оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | [Fill](../../com.aspose.pdf.operators/fill) | Оператор заполнения пути (правило ненулевого числа циклов). |

### visit(FillStroke B) {#visit-com.aspose.pdf.operators.FillStroke-}
```
public void visit(FillStroke B)
```


Посетите/выберите оператора B.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| B | [FillStroke](../../com.aspose.pdf.operators/fillstroke) | Оператор заполнения и обводки пути (правило ненулевого числа витков). |

### visit(GRestore Q) {#visit-com.aspose.pdf.operators.GRestore-}
```
public void visit(GRestore Q)
```


Посетите/выберите оператора Q.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Q | [GRestore](../../com.aspose.pdf.operators/grestore) | Оператор восстановления состояния графики. |

### visit(GS gs) {#visit-com.aspose.pdf.operators.GS-}
```
public void visit(GS gs)
```


Посетите/выберите оператора gs.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| gs | [GS](../../com.aspose.pdf.operators/gs) | Установите оператор состояния графики. |

### visit(GSave q) {#visit-com.aspose.pdf.operators.GSave-}
```
public void visit(GSave q)
```


Посетите/выберите оператора q.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| q | [GSave](../../com.aspose.pdf.operators/gsave) | Оператор сохранения графического состояния. |

### visit(ID ID) {#visit-com.aspose.pdf.operators.ID-}
```
public void visit(ID ID)
```


Посетите/выберите ID оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ID | [ID](../../com.aspose.pdf.operators/id) | Начать встроенный оператор данных изображения. |

### visit(LineTo l) {#visit-com.aspose.pdf.operators.LineTo-}
```
public void visit(LineTo l)
```


Посетите/выберите l оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| l | [LineTo](../../com.aspose.pdf.operators/lineto) | Добавить сегмент прямой линии к оператору пути. |

### visit(MP MP) {#visit-com.aspose.pdf.operators.MP-}
```
public void visit(MP MP)
```


Посетите/выберите оператора MP.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| MP | [MP](../../com.aspose.pdf.operators/mp) | Определить оператор точки отмеченного содержимого. |

### visit(MoveTextPosition Td) {#visit-com.aspose.pdf.operators.MoveTextPosition-}
```
public void visit(MoveTextPosition Td)
```


Посетите/выберите оператора Td.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Td | [MoveTextPosition](../../com.aspose.pdf.operators/movetextposition) | Оператор перемещения текста. |

### visit(MoveTextPositionSetLeading TD) {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
```
public void visit(MoveTextPositionSetLeading TD)
```


Посетите/выберите оператора ТД.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| TD | [MoveTextPositionSetLeading](../../com.aspose.pdf.operators/movetextpositionsetleading) | Переместить позицию текста и установить ведущий оператор. |

### visit(MoveTo m) {#visit-com.aspose.pdf.operators.MoveTo-}
```
public void visit(MoveTo m)
```


Посетите/выберите m оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| m | [MoveTo](../../com.aspose.pdf.operators/moveto) | Начать новый оператор подпути. |

### visit(MoveToNextLine T_) {#visit-com.aspose.pdf.operators.MoveToNextLine-}
```
public void visit(MoveToNextLine T_)
```


Посетите/выберите T\* оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| T_ | [MoveToNextLine](../../com.aspose.pdf.operators/movetonextline) | Оператор перехода к началу следующей текстовой строки. |

### visit(MoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
```
public void visit(MoveToNextLineShowText value)
```


Посетите/выберите ' оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MoveToNextLineShowText](../../com.aspose.pdf.operators/movetonextlineshowtext) | Перейти к следующей строке и показать текстовый оператор. |

### visit(ObsoleteFill F) {#visit-com.aspose.pdf.operators.ObsoleteFill-}
```
public void visit(ObsoleteFill F)
```


Посетите/выберите оператора F.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| F | [ObsoleteFill](../../com.aspose.pdf.operators/obsoletefill) | Оператор заполнения пути (правило ненулевого числа циклов). |

### visit(Re re) {#visit-com.aspose.pdf.operators.Re-}
```
public void visit(Re re)
```


Посетите/выберите оператора re.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| re | [Re](../../com.aspose.pdf.operators/re) | Добавить прямоугольник к оператору пути. |

### visit(SelectFont Tf) {#visit-com.aspose.pdf.operators.SelectFont-}
```
public void visit(SelectFont Tf)
```


Посетите/выберите оператора Tf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tf | [SelectFont](../../com.aspose.pdf.operators/selectfont) | Оператор установки шрифта и размера текста. |

### visit(SetAdvancedColor scn) {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
```
public void visit(SetAdvancedColor scn)
```


Посетите/выберите оператора scn.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| scn | [SetAdvancedColor](../../com.aspose.pdf.operators/setadvancedcolor) | Оператор установки цвета (для операций без штриховки, ICCBased и специальных цветовых пространств). |

### visit(SetAdvancedColorStroke SCN) {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
```
public void visit(SetAdvancedColorStroke SCN)
```


Посетите/выберите оператора SCN.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| SCN | [SetAdvancedColorStroke](../../com.aspose.pdf.operators/setadvancedcolorstroke) | Оператор установки цвета (для операций штриховки, ICCBased и специальных цветовых пространств). |

### visit(SetCMYKColor k) {#visit-com.aspose.pdf.operators.SetCMYKColor-}
```
public void visit(SetCMYKColor k)
```


Посетите/выберите оператора k.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| k | [SetCMYKColor](../../com.aspose.pdf.operators/setcmykcolor) | Установите цветовой оператор CMYK (для операций без обводки). |

### visit(SetCMYKColorStroke K) {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
```
public void visit(SetCMYKColorStroke K)
```


Посетите/выберите оператора K.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| K | [SetCMYKColorStroke](../../com.aspose.pdf.operators/setcmykcolorstroke) | Установите цветовой оператор CMYK (для штриховых операций). |

### visit(SetCharWidth d0) {#visit-com.aspose.pdf.operators.SetCharWidth-}
```
public void visit(SetCharWidth d0)
```


Посетите/выберите оператора d0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| d0 | [SetCharWidth](../../com.aspose.pdf.operators/setcharwidth) | Установите ширину глифа в операторе шрифта Type 3. |

### visit(SetCharWidthBoundingBox d1) {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
```
public void visit(SetCharWidthBoundingBox d1)
```


Посетите/выберите оператора d1.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| d1 | [SetCharWidthBoundingBox](../../com.aspose.pdf.operators/setcharwidthboundingbox) | Установите ширину глифа и ограничивающую рамку в операторе шрифта Type 3. |

### visit(SetCharacterSpacing Tc) {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
```
public void visit(SetCharacterSpacing Tc)
```


Посетите/выберите оператора Tc.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tc | [SetCharacterSpacing](../../com.aspose.pdf.operators/setcharacterspacing) | Установить оператор межсимвольного интервала. |

### visit(SetColor sc) {#visit-com.aspose.pdf.operators.SetColor-}
```
public void visit(SetColor sc)
```


Посетите/выберите оператора sc.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| sc | [SetColor](../../com.aspose.pdf.operators/setcolor) | Оператор Set color (для операций без обводки). |

### visit(SetColorRenderingIntent ri) {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
```
public void visit(SetColorRenderingIntent ri)
```


Посетите/выберите оператора ri.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ri | [SetColorRenderingIntent](../../com.aspose.pdf.operators/setcolorrenderingintent) | Установите оператор намерения цветопередачи. |

### visit(SetColorSpace cs) {#visit-com.aspose.pdf.operators.SetColorSpace-}
```
public void visit(SetColorSpace cs)
```


Посетите/выберите оператора cs.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cs | [SetColorSpace](../../com.aspose.pdf.operators/setcolorspace) | Оператор установки цветового пространства (для операций без штриха). |

### visit(SetColorSpaceStroke CS) {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
```
public void visit(SetColorSpaceStroke CS)
```


Посетите/выберите оператора CS.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| CS | [SetColorSpaceStroke](../../com.aspose.pdf.operators/setcolorspacestroke) | Оператор установки цветового пространства (для операций штриховки). |

### visit(SetColorStroke SC) {#visit-com.aspose.pdf.operators.SetColorStroke-}
```
public void visit(SetColorStroke SC)
```


Посетите/выберите оператора СЦ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| SC | [SetColorStroke](../../com.aspose.pdf.operators/setcolorstroke) | Оператор Set color (для операций обводки). |

### visit(SetDash d) {#visit-com.aspose.pdf.operators.SetDash-}
```
public void visit(SetDash d)
```


Посетите/выберите оператора d.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| d | [SetDash](../../com.aspose.pdf.operators/setdash) | Установить оператор шаблона пунктирной линии. |

### visit(SetFlat i) {#visit-com.aspose.pdf.operators.SetFlat-}
```
public void visit(SetFlat i)
```


Посетите/выберите i оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | [SetFlat](../../com.aspose.pdf.operators/setflat) | Установите оператор допуска плоскостности. |

### visit(SetGlyphsPositionShowText TJ) {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
```
public void visit(SetGlyphsPositionShowText TJ)
```


Посетите/выберите оператора TJ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| TJ | [SetGlyphsPositionShowText](../../com.aspose.pdf.operators/setglyphspositionshowtext) | Показать текстовый оператор (позволяет позиционировать отдельные глифы). |

### visit(SetGray g) {#visit-com.aspose.pdf.operators.SetGray-}
```
public void visit(SetGray g)
```


Посетите/выберите оператора g.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [SetGray](../../com.aspose.pdf.operators/setgray) | Установить оператор уровня серого (для операций без штриха). |

### visit(SetGrayStroke G) {#visit-com.aspose.pdf.operators.SetGrayStroke-}
```
public void visit(SetGrayStroke G)
```


Посетите/выберите оператора G.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| G | [SetGrayStroke](../../com.aspose.pdf.operators/setgraystroke) | Установить оператор уровня серого (для операций штриховки). |

### visit(SetHorizontalTextScaling Tz) {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
```
public void visit(SetHorizontalTextScaling Tz)
```


Посетите/выберите оператора Tz.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tz | [SetHorizontalTextScaling](../../com.aspose.pdf.operators/sethorizontaltextscaling) | Установите оператор горизонтального масштабирования текста. |

### visit(SetLineCap J) {#visit-com.aspose.pdf.operators.SetLineCap-}
```
public void visit(SetLineCap J)
```


Посетите/выберите оператора J.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| J | [SetLineCap](../../com.aspose.pdf.operators/setlinecap) | Установить оператор стиля окончания строки. |

### visit(SetLineJoin j) {#visit-com.aspose.pdf.operators.SetLineJoin-}
```
public void visit(SetLineJoin j)
```


Посетите/выберите оператора j.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| j | [SetLineJoin](../../com.aspose.pdf.operators/setlinejoin) | Установить оператор стиля соединения строк. |

### visit(SetLineWidth w) {#visit-com.aspose.pdf.operators.SetLineWidth-}
```
public void visit(SetLineWidth w)
```


Посетите/выберите w оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| w | [SetLineWidth](../../com.aspose.pdf.operators/setlinewidth) | Оператор установки ширины линии. |

### visit(SetMiterLimit M) {#visit-com.aspose.pdf.operators.SetMiterLimit-}
```
public void visit(SetMiterLimit M)
```


Посетите/выберите оператора М.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| M | [SetMiterLimit](../../com.aspose.pdf.operators/setmiterlimit) | Установите оператор предела митры. |

### visit(SetRGBColor rg) {#visit-com.aspose.pdf.operators.SetRGBColor-}
```
public void visit(SetRGBColor rg)
```


Посетите/выберите оператора rg.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rg | [SetRGBColor](../../com.aspose.pdf.operators/setrgbcolor) | Установить оператор цвета RGB (для операций без штриха). |

### visit(SetRGBColorStroke RG) {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
```
public void visit(SetRGBColorStroke RG)
```


Посетите/выберите оператора RG.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| RG | [SetRGBColorStroke](../../com.aspose.pdf.operators/setrgbcolorstroke) | Установить оператор цвета RGB (для операций штриховки). |

### visit(SetSpacingMoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
```
public void visit(SetSpacingMoveToNextLineShowText value)
```


Посетите/выберите '' оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SetSpacingMoveToNextLineShowText](../../com.aspose.pdf.operators/setspacingmovetonextlineshowtext) | Установка интервала между словами и символами, переход к следующей строке и отображение текстового оператора. |

### visit(SetTextLeading TL) {#visit-com.aspose.pdf.operators.SetTextLeading-}
```
public void visit(SetTextLeading TL)
```


Посетите/выберите оператора TL.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| TL | [SetTextLeading](../../com.aspose.pdf.operators/settextleading) | Установить ведущий текстовый оператор. |

### visit(SetTextMatrix Tm) {#visit-com.aspose.pdf.operators.SetTextMatrix-}
```
public void visit(SetTextMatrix Tm)
```


Посетите/выберите оператора Tm.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tm | [SetTextMatrix](../../com.aspose.pdf.operators/settextmatrix) | Установите текстовую матрицу и текстовую линейную матрицу оператора. |

### visit(SetTextRenderingMode Tr) {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
```
public void visit(SetTextRenderingMode Tr)
```


Посетите/выберите оператора Tr.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tr | [SetTextRenderingMode](../../com.aspose.pdf.operators/settextrenderingmode) | Установить оператор режима рендеринга текста. |

### visit(SetTextRise Ts) {#visit-com.aspose.pdf.operators.SetTextRise-}
```
public void visit(SetTextRise Ts)
```


Посетите/выберите оператора Ts.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Ts | [SetTextRise](../../com.aspose.pdf.operators/settextrise) | Установите оператор подъема текста. |

### visit(SetWordSpacing Tw) {#visit-com.aspose.pdf.operators.SetWordSpacing-}
```
public void visit(SetWordSpacing Tw)
```


Посетите/выберите оператора Tw.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tw | [SetWordSpacing](../../com.aspose.pdf.operators/setwordspacing) | Установите оператор интервала между словами. |

### visit(ShFill sh) {#visit-com.aspose.pdf.operators.ShFill-}
```
public void visit(ShFill sh)
```


Посетите/выберите оператора sh.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| sh | [ShFill](../../com.aspose.pdf.operators/shfill) | Область рисования определяется оператором шаблона затенения. |

### visit(ShowText Tj) {#visit-com.aspose.pdf.operators.ShowText-}
```
public void visit(ShowText Tj)
```


Посетите/выберите оператора Tj.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| Tj | [ShowText](../../com.aspose.pdf.operators/showtext) | Показать текстовый оператор. |

### visit(Stroke S) {#visit-com.aspose.pdf.operators.Stroke-}
```
public void visit(Stroke S)
```


Посетите/выберите оператора S.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| S | [Stroke](../../com.aspose.pdf.operators/stroke) | Оператор пути штриха. |

### visit(TextOperator textOperator) {#visit-com.aspose.pdf.operators.TextOperator-}
```
public void visit(TextOperator textOperator)
```


Посетите/выберите любой текстовый оператор оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textOperator | [TextOperator](../../com.aspose.pdf.operators/textoperator) | Общий текстовый оператор, который используется для выбора набора соответствующих операторов PDF. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
