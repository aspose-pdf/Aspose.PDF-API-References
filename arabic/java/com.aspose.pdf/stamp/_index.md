---
title: "طابع"
linktitle: "طابع"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة مجردة لأنواع مختلفة من الطوابع التي تأتي كفروع."
type: docs
weight: 4620
url: /ar/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

فئة مجردة لأنواع مختلفة من الطوابع التي تأتي كفروع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Stamp](#Stamp--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | يحصل على الهامش السفلي للطابع. |
| [getHeight](#getHeight--) | يحصل على الارتفاع المطلوب للطابع على الصفحة. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على المحاذاة الأفقية للطابع على الصفحة. |
| [getLeftMargin](#getLeftMargin--) | يحصل على الهامش الأيسر للطابع. |
| [getOpacity](#getOpacity--) | يحصل على قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | يحصل على قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | يحصل على قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0. |
| [getRightMargin](#getRightMargin--) | يحصل على الهامش الأيمن للطابع. |
| [getRotate](#getRotate--) | يحصل على دوران محتوى الطابع وفق قيم {@code Rotation}. ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية المحددة بواسطة ArbitraryAngle ليست مضاعفًا للـ 90 فإن الخاصية Rotate تُعيد Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | يحصل على زاوية دوران الطابع بالدرجات. هذه الخاصية تسمح بتعيين زاوية دوران عشوائية. |
| [getStampId](#getStampId--) | يحصل على معرف الطابع. |
| [getTopMargin](#getTopMargin--) | احصل على الهامش العلوي للطابع. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على المحاذاة العمودية للطابع على الصفحة. |
| [getWidth](#getWidth--) | يحصل على العرض المطلوب للطابع على الصفحة. |
| [getXIndent](#getXIndent--) | احصل على إحداثي الطابع الأفقي، بدءًا من اليسار. |
| [getYIndent](#getYIndent--) | احصل على إحداثي الطابع العمودي، بدءًا من الأسفل. |
| [getZoom](#getZoom--) | يحصل على معامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX وZoomY يسمح بتعيين معامل التكبير لكل محور على حدة. تعديل هذه الخاصية يغيّر كل من خصائص ZoomX وZoomY. إذا كانت قيمتا ZoomX وZoomY مختلفة فإن الخاصية Zoom تُعيد قيمة ZoomX. |
| [getZoomX](#getZoomX--) | يحصل على معامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقيًا. |
| [getZoomY](#getZoomY--) | يحصل على معامل التكبير العمودي للطابع. يسمح بتكبير الطابع عموديًا. |
| [isBackground](#isBackground--) | يحصل على قيمة منطقية تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، القيمة false، يتم وضع محتوى الطابع في الأعلى. |
| [put](#put-com.aspose.pdf.Page-) | يضيف طابعًا إلى الصفحة. |
| [setBackground](#setBackground-boolean-) | يضبط قيمة منطقية تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، القيمة false، يتم وضع محتوى الطابع في الأعلى. |
| [setBottomMargin](#setBottomMargin-double-) | يضبط الهامش السفلي للطابع. |
| [setHeight](#setHeight-double-) | يضبط الارتفاع المطلوب للطابع على الصفحة. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة الطابع أفقياً على الصفحة. |
| [setLeftMargin](#setLeftMargin-double-) | يضبط الهامش الأيسر للطابع. |
| [setOpacity](#setOpacity-double-) | يضبط قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 و 1.0. بشكل افتراضي القيمة هي 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | يضبط قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 و 1.0. بشكل افتراضي القيمة هي 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | يضبط قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0. |
| [setRightMargin](#setRightMargin-double-) | يضبط الهامش الأيمن للطابع. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | يضبط دوران محتوى الطابع وفق قيم {@code Rotation}. ملاحظة. هذه الخاصية مخصصة للزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفاً للـ 90 فإن خاصية Rotate تُعيد Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | يضبط زاوية دوران الطابع بالدرجات. هذه الخاصية تسمح بتعيين زاوية دوران عشوائية. |
| [setStampId](#setStampId-int-) | يضبط معرف الطابع. |
| [setTopMargin](#setTopMargin-double-) | يضبط الهامش العلوي للطابع. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط محاذاة الطابع رأسياً على الصفحة. |
| [setWidth](#setWidth-double-) | يضبط العرض المطلوب للطابع على الصفحة. |
| [setXIndent](#setXIndent-double-) | حدد إحداثي الطابع الأفقي، بدءاً من اليسار. |
| [setYIndent](#setYIndent-double-) | حدد إحداثي الطابع الرأسي، بدءاً من الأسفل. |
| [setZoom](#setZoom-double-) | يحصل على معامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX وZoomY يسمح بتعيين معامل التكبير لكل محور على حدة. تعديل هذه الخاصية يغيّر كل من خصائص ZoomX وZoomY. إذا كانت قيمتا ZoomX وZoomY مختلفة فإن الخاصية Zoom تُعيد قيمة ZoomX. |
| [setZoomX](#setZoomX-double-) | يضبط عامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقياً. |
| [setZoomY](#setZoomY-double-) | يضبط عامل التكبير الرأسي للطابع. يسمح بتكبير الطابع رأسياً. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

يحصل على الهامش السفلي للطابع.

**Returns:**
قيمة double

### getHeight {#getHeight--}
```
public double getHeight()
```

يحصل على الارتفاع المطلوب للطابع على الصفحة.

**Returns:**
قيمة double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على المحاذاة الأفقية للطابع على الصفحة.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

يحصل على الهامش الأيسر للطابع.

**Returns:**
قيمة double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

يحصل على قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0.

**Returns:**
قيمة double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

يحصل على قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0.

**Returns:**
قيمة double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

يحصل على قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0.

**Returns:**
قيمة double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

يحصل على الهامش الأيمن للطابع.

**Returns:**
قيمة double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

يحصل على دوران محتوى الطابع وفق قيم {@code Rotation}. ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية المحددة بواسطة ArbitraryAngle ليست مضاعفًا للـ 90 فإن الخاصية Rotate تُعيد Rotation.None.

**Returns:**
قيمة الدوران @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

يحصل على زاوية دوران الطابع بالدرجات. هذه الخاصية تسمح بتعيين زاوية دوران عشوائية.

**Returns:**
قيمة double

### getStampId {#getStampId--}
```
public int getStampId()
```

يحصل على معرف الطابع.

**Returns:**
معرف الطابع.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

احصل على الهامش العلوي للطابع.

**Returns:**
قيمة double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل على المحاذاة العمودية للطابع على الصفحة.

**Returns:**
قيمة VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

يحصل على العرض المطلوب للطابع على الصفحة.

**Returns:**
قيمة double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

احصل على إحداثي الطابع الأفقي، بدءًا من اليسار.

**Returns:**
قيمة double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

احصل على إحداثي الطابع العمودي، بدءًا من الأسفل.

**Returns:**
قيمة double

### getZoom {#getZoom--}
```
public double getZoom()
```

يحصل على معامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX وZoomY يسمح بتعيين معامل التكبير لكل محور على حدة. تعديل هذه الخاصية يغيّر كل من خصائص ZoomX وZoomY. إذا كانت قيمتا ZoomX وZoomY مختلفة فإن الخاصية Zoom تُعيد قيمة ZoomX.

**Returns:**
قيمة double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

يحصل على معامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقيًا.

**Returns:**
قيمة double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

يحصل على معامل التكبير العمودي للطابع. يسمح بتكبير الطابع عموديًا.

**Returns:**
قيمة double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

يحصل على قيمة منطقية تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، القيمة false، يتم وضع محتوى الطابع في الأعلى.

**Returns:**
قيمة منطقية

### put {#put-com.aspose.pdf.Page-}
يضيف طابعًا إلى الصفحة.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

يضبط قيمة منطقية تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، القيمة false، يتم وضع محتوى الطابع في الأعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

يضبط الهامش السفلي للطابع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

يضبط الارتفاع المطلوب للطابع على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة الطابع أفقياً على الصفحة.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

يضبط الهامش الأيسر للطابع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

يضبط قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 و 1.0. بشكل افتراضي القيمة هي 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

يضبط قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 و 1.0. بشكل افتراضي القيمة هي 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

يضبط قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

يضبط الهامش الأيمن للطابع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
يضبط دوران محتوى الطابع وفق قيم {@code Rotation}. ملاحظة. هذه الخاصية مخصصة للزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفاً للـ 90 فإن خاصية Rotate تُعيد Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

يضبط زاوية دوران الطابع بالدرجات. هذه الخاصية تسمح بتعيين زاوية دوران عشوائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | زاوية الدوران |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

يضبط معرف الطابع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القيمة الجديدة لمعرّف الطابع. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

يضبط الهامش العلوي للطابع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط محاذاة الطابع رأسياً على الصفحة.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

يضبط العرض المطلوب للطابع على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

حدد إحداثي الطابع الأفقي، بدءاً من اليسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

حدد إحداثي الطابع الرأسي، بدءاً من الأسفل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

يحصل على معامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX وZoomY يسمح بتعيين معامل التكبير لكل محور على حدة. تعديل هذه الخاصية يغيّر كل من خصائص ZoomX وZoomY. إذا كانت قيمتا ZoomX وZoomY مختلفة فإن الخاصية Zoom تُعيد قيمة ZoomX.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

يضبط عامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقياً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

يضبط عامل التكبير الرأسي للطابع. يسمح بتكبير الطابع رأسياً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
