---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "LoadOptions 类型保存对各个加载选项的抽象层级。"
type: docs
weight: 2790
url: /zh/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

LoadOptions 类型保存对各个加载选项的抽象层级。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | 表示 {@code LoadOptions} 描述的文件格式。 |
| [getWarningHandler](#getWarningHandler--) | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | 获取或设置标志，以在加载文件时禁用所有字体的任何许可证限制。当 {@code } 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也允许将字体嵌入 PDF 文档。默认情况下 {@code }。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担可能的许可证/法律违规责任。因此风险由其自行承担。强烈建议仅在完全确信不会侵犯版权法时使用此标志。 |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | 获取或设置标志，以在加载文件时禁用所有字体的任何许可证限制。当 {@code } 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也允许将字体嵌入 PDF 文档。默认情况下 {@code }。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担可能的许可证/法律违规责任。因此风险由其自行承担。强烈建议仅在完全确信不会侵犯版权法时使用此标志。 |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

表示 {@code LoadOptions} 描述的文件格式。

**Returns:**
LoadFormat 元素 @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。

**Returns:**
IWarningCallback 值

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

获取或设置标志，以在加载文件时禁用所有字体的任何许可证限制。当 {@code } 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也允许将字体嵌入 PDF 文档。默认情况下 {@code }。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担可能的许可证/法律违规责任。因此风险由其自行承担。强烈建议仅在完全确信不会侵犯版权法时使用此标志。

**Returns:**
布尔值

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

获取或设置标志，以在加载文件时禁用所有字体的任何许可证限制。当 {@code } 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也允许将字体嵌入 PDF 文档。默认情况下 {@code }。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担可能的许可证/法律违规责任。因此风险由其自行承担。强烈建议仅在完全确信不会侵犯版权法时使用此标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。
