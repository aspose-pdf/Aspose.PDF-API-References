---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс параметров для извлечения векторной графики со страницы PDF‑документа."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Представляет класс параметров для извлечения векторной графики со страницы PDF‑документа.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Создает экземпляр класса SvgExtractionOptions. |

## Методы

| Метод | Описание |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Получает и задает параметр, автоматически группирующий подпути в изображения. Этот параметр исключает параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Получает и задает параметр, извлекающий каждый подпуть из PDF‑документа в отдельные SVG‑изображения. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG. |
| [getGroupStrength](#getGroupStrength--) | Получает и задает параметр, определяющий силу группировки подпутей в изображения. Позволяет настроить степень группировки подпутей. Значение находится в диапазоне от 0 до 1. Значение 0 соответствует включенному параметру {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Значение 1 создаст единое изображение для всех векторных путей на странице. Параметр влияет, когда параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) установлен в false. Значение по умолчанию — {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Получает или задает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. Значение выражается в преобразованных единицах пользовательского пространства конвертированной страницы PDF. По умолчанию 1 единица пользовательского пространства равна 1/72 дюйма (0,35 мм), но это может быть переопределено документом PDF. Преобразования могут влиять на фактическую минимальную ширину в генерируемом SVG. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Получает и задает параметр, строго проверяющий, находятся ли подпути внутри указанного прямоугольника в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Если параметр установлен в false, то подпути, не полностью включённые в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}), будут извлечены. Значение по умолчанию — {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные операторами Do из содержимого страницы. Вложенные XForms не распаковываются. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Получает и задает параметр, распаковывающий только XForm, соответствующий указанному предикату. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Получает и задает параметр, автоматически группирующий подпути в изображения. Этот параметр исключает параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Получает и задает параметр, извлекающий каждый подпуть из PDF‑документа в отдельные SVG‑изображения. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Получает и задает параметр, определяющий силу группировки подпутей в изображения. Позволяет настроить степень группировки подпутей. Значение находится в диапазоне от 0 до 1. Значение 0 соответствует включенному параметру {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Значение 1 создаст единое изображение для всех векторных путей на странице. Параметр влияет, когда параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) установлен в false. Значение по умолчанию — {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Получает или задает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. Значение выражается в преобразованных единицах пользовательского пространства конвертированной страницы PDF. По умолчанию 1 единица пользовательского пространства равна 1/72 дюйма (0,35 мм), но это может быть переопределено документом PDF. Преобразования могут влиять на фактическую минимальную ширину в генерируемом SVG. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Получает и задает параметр, строго проверяющий, находятся ли подпути внутри указанного прямоугольника в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Если параметр установлен в false, то подпути, не полностью включённые в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}), будут извлечены. Значение по умолчанию — {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные операторами Do из содержимого страницы. Вложенные XForms не распаковываются. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Получает и задает параметр, распаковывающий только XForm, соответствующий указанному предикату. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Создает экземпляр класса SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Получает и задает параметр, автоматически группирующий подпути в изображения. Этот параметр исключает параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
логическое значение

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Получает и задает параметр, извлекающий каждый подпуть из PDF‑документа в отдельные SVG‑изображения.

**Returns:**
логическое значение

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG.

**Returns:**
Экземпляр Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Получает и задает параметр, определяющий силу группировки подпутей в изображения. Позволяет настроить степень группировки подпутей. Значение находится в диапазоне от 0 до 1. Значение 0 соответствует включенному параметру {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Значение 1 создаст единое изображение для всех векторных путей на странице. Параметр влияет, когда параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) установлен в false. Значение по умолчанию — {@code 0.8}.

**Returns:**
double значение

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Получает или задает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. Значение выражается в преобразованных единицах пользовательского пространства конвертированной страницы PDF. По умолчанию 1 единица пользовательского пространства равна 1/72 дюйма (0,35 мм), но это может быть переопределено документом PDF. Преобразования могут влиять на фактическую минимальную ширину в генерируемом SVG.

**Returns:**
double значение

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Получает и задает параметр, строго проверяющий, находятся ли подпути внутри указанного прямоугольника в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Если параметр установлен в false, то подпути, не полностью включённые в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}), будут извлечены. Значение по умолчанию — {@code True}.

**Returns:**
логическое значение

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные операторами Do из содержимого страницы. Вложенные XForms не распаковываются.

**Returns:**
логическое значение

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Получает и задает параметр, распаковывающий только XForm, соответствующий указанному предикату.

**Returns:**
внутренний экземпляр Predicate объекта XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Получает и задает параметр, автоматически группирующий подпути в изображения. Этот параметр исключает параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Получает и задает параметр, извлекающий каждый подпуть из PDF‑документа в отдельные SVG‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Получает и задает параметр, определяющий силу группировки подпутей в изображения. Позволяет настроить степень группировки подпутей. Значение находится в диапазоне от 0 до 1. Значение 0 соответствует включенному параметру {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}). Значение 1 создаст единое изображение для всех векторных путей на странице. Параметр влияет, когда параметр {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) установлен в false. Значение по умолчанию — {@code 0.8}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Получает или задает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. Значение выражается в преобразованных единицах пользовательского пространства конвертированной страницы PDF. По умолчанию 1 единица пользовательского пространства равна 1/72 дюйма (0,35 мм), но это может быть переопределено документом PDF. Преобразования могут влиять на фактическую минимальную ширину в генерируемом SVG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Получает и задает параметр, строго проверяющий, находятся ли подпути внутри указанного прямоугольника в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Если параметр установлен в false, то подпути, не полностью включённые в {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}), будут извлечены. Значение по умолчанию — {@code True}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные операторами Do из содержимого страницы. Вложенные XForms не распаковываются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Получает и задает параметр, распаковывающий только XForm, соответствующий указанному предикату.
