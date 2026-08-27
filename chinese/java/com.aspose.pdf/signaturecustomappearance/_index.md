---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Aspose.PDF for Java API 参考"
description: "抽象类，表示签名自定义外观对象。"
type: docs
weight: 4500
url: /zh/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

抽象类，表示签名自定义外观对象。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | 初始化 {@link SignatureCustomAppearance} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | 获取/设置背景颜色。默认值：Transparent。 |
| [getContactInfoLabel](#getContactInfoLabel--) | 获取/设置联系信息标签。默认值："Contact"。 |
| [getCulture](#getCulture--) | 获取/设置区域信息值。默认值：InvariantCulture。 |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | 获取/设置签署日期标签。默认值："Date"。 |
| [getDateTimeFormat](#getDateTimeFormat--) | 获取/设置日期时间格式。默认值："yyyy.MM.dd HH:mm:ss"。 |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | 获取/设置本地日期时间格式。默认值："yyyy.MM.dd HH:mm:ss zzz"。 |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | 获取/设置数字签名标签。默认值："Digitally signed by"。 |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | 获取/设置 Subject 字符串中元素顺序的格式。结果示例：C=UK, CN=Org, O=Organization 或 CN=Org, C=UK, O=Organization 或 O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | 获取/设置字体族名称。它应当已存在于文档中。默认值：Arial。 |
| [getFontSize](#getFontSize--) | 获取/设置字体大小。默认值：10。 |
| [getForegroundColor](#getForegroundColor--) | 获取/设置前景颜色（文本颜色）。默认值：Blue。 |
| [getLocationLabel](#getLocationLabel--) | 获取/设置位置标签。默认值："Location"。 |
| [getReasonLabel](#getReasonLabel--) | 获取/设置原因标签。默认值："Reason"。 |
| [getRotation](#getRotation--) | 获取或设置签名旋转。 |
| [isForegroundImage](#isForegroundImage--) | 获取或设置一个值，指示签名外观中的图像是否绘制为前景图像。默认值：false。 |
| [isShowContactInfo](#isShowContactInfo--) | 获取/设置联系信息可见性。默认值：true。 |
| [isShowLocation](#isShowLocation--) | 获取/设置位置可见性。默认值：true。 |
| [isShowReason](#isShowReason--) | 获取/设置原因可见性。默认值：true。 |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) | 获取/设置 {@code DigitalSubjectFormat}（{@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}）的使用状态。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取/设置背景颜色。默认值：Transparent。 |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | 获取/设置联系信息标签。默认值："Contact"。 |
| [setCulture](#setCulture-java.util.Locale-) | 获取/设置区域信息值。 |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | 获取/设置签署日期标签。默认值："Date"。 |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | 获取/设置日期时间格式。默认值："yyyy.MM.dd HH:mm:ss"。 |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | 获取/设置本地日期时间格式。默认值："yyyy.MM.dd HH:mm:ss zzz"。 |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | 获取/设置数字签名标签。默认值："Digitally signed by"。 |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | 获取/设置 Subject 字符串中元素顺序的格式。结果示例：C=UK, CN=Org, O=Organization 或 CN=Org, C=UK, O=Organization 或 O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | 获取/设置字体族名称。它应当已存在于文档中。默认值：Arial。 |
| [setFontSize](#setFontSize-double-) | 获取/设置字体大小。默认值：10。 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | 获取/设置前景颜色（文本颜色）。默认值：Blue。 |
| [setForegroundImage](#setForegroundImage-boolean-) | 获取或设置一个值，指示签名外观中的图像是否绘制为前景图像。默认值：false。 |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | 获取/设置位置标签。默认值："Location"。 |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | 获取/设置原因标签。默认值："Reason"。 |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | 获取或设置签名旋转。 |
| [setShowContactInfo](#setShowContactInfo-boolean-) | 获取/设置联系信息可见性。默认值：true。 |
| [setShowLocation](#setShowLocation-boolean-) | 获取/设置位置可见性。默认值：true。 |
| [setShowReason](#setShowReason-boolean-) | 获取/设置原因可见性。默认值：true。 |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) | 获取/设置 {@code DigitalSubjectFormat}（{@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}）的使用状态。 |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

初始化 {@link SignatureCustomAppearance} 类的新实例。

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取/设置背景颜色。默认值：Transparent。

**Returns:**
com.aspose.pdf.Color 实例

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

获取/设置联系信息标签。默认值："Contact"。

**Returns:**
字符串值

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

获取/设置区域信息值。默认值：InvariantCulture。

**Returns:**
Locale 值

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

获取/设置签署日期标签。默认值："Date"。

**Returns:**
字符串值

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

获取/设置日期时间格式。默认值："yyyy.MM.dd HH:mm:ss"。

**Returns:**
字符串值

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

获取/设置本地日期时间格式。默认值："yyyy.MM.dd HH:mm:ss zzz"。

**Returns:**
字符串值

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

获取/设置数字签名标签。默认值："Digitally signed by"。

**Returns:**
字符串值

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

获取/设置 Subject 字符串中元素顺序的格式。结果示例：C=UK, CN=Org, O=Organization 或 CN=Org, C=UK, O=Organization 或 O=Organization

**Returns:**
int 数组 @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

获取/设置字体族名称。它应当已存在于文档中。默认值：Arial。

**Returns:**
字符串值

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

获取/设置字体大小。默认值：10。

**Returns:**
double 值

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

获取/设置前景颜色（文本颜色）。默认值：Blue。

**Returns:**
com.aspose.pdf.Color 实例

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

获取/设置位置标签。默认值："Location"。

**Returns:**
字符串值

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

获取/设置原因标签。默认值："Reason"。

**Returns:**
字符串值

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

获取或设置签名旋转。

**Returns:**
旋转元素

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

获取或设置一个值，指示签名外观中的图像是否绘制为前景图像。默认值：false。

**Returns:**
布尔值

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

获取/设置联系信息可见性。默认值：true。

**Returns:**
布尔值

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

获取/设置位置可见性。默认值：true。

**Returns:**
布尔值

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

获取/设置原因可见性。默认值：true。

**Returns:**
布尔值

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

获取/设置 {@code DigitalSubjectFormat}（{@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}）的使用状态。

**Returns:**
布尔值

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取/设置背景颜色。默认值：Transparent。

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
获取/设置联系信息标签。默认值："Contact"。

### setCulture {#setCulture-java.util.Locale-}
获取/设置区域信息值。

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
获取/设置签署日期标签。默认值："Date"。

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
获取/设置日期时间格式。默认值："yyyy.MM.dd HH:mm:ss"。

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
获取/设置本地日期时间格式。默认值："yyyy.MM.dd HH:mm:ss zzz"。

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
获取/设置数字签名标签。默认值："Digitally signed by"。

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

获取/设置 Subject 字符串中元素顺序的格式。结果示例：C=UK, CN=Org, O=Organization 或 CN=Org, C=UK, O=Organization 或 O=Organization

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 数组 @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
获取/设置字体族名称。它应当已存在于文档中。默认值：Arial。

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

获取/设置字体大小。默认值：10。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
获取/设置前景颜色（文本颜色）。默认值：Blue。

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

获取或设置一个值，指示签名外观中的图像是否绘制为前景图像。默认值：false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLocationLabel {#setLocationLabel-java.lang.String-}
获取/设置位置标签。默认值："Location"。

### setReasonLabel {#setReasonLabel-java.lang.String-}
获取/设置原因标签。默认值："Reason"。

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
获取或设置签名旋转。

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

获取/设置联系信息可见性。默认值：true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

获取/设置位置可见性。默认值：true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

获取/设置原因可见性。默认值：true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

获取/设置 {@code DigitalSubjectFormat}（{@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])}）的使用状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
