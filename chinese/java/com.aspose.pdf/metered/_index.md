---
title: "Metered"
linktitle: "Metered"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 提供设置计量密钥的方法。 </p> <hr> 在此示例中，将尝试设置计量的公钥和私钥 <pre> 组件 jar 文件：Metered matered =."
type: docs
weight: 3060
url: /zh/java/com.aspose.pdf/metered/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metered

```
public class Metered extends Object
```

<p> 提供设置计量密钥的方法。 </p> <hr> 在此示例中，将尝试设置计量的公钥和私钥 <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered](#Metered--) | 初始化此类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getConsumptionCredit](#getConsumptionCredit--) | 获取消耗额度 |
| [getConsumptionQuantity](#getConsumptionQuantity--) | 获取消耗文件大小 |
| [setMeteredKey](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量的公钥和私钥 |

### Metered {#Metered--}
```
public Metered()
```

初始化此类的新实例。

### getConsumptionCredit {#getConsumptionCredit--}
```
public static com.aspose.ms.System.Decimal getConsumptionCredit() throws Exception
```

获取消耗额度

**Returns:**
消耗数量 @throws Exception 如果 Metered API 出现问题。

### getConsumptionQuantity {#getConsumptionQuantity--}
```
public static com.aspose.ms.System.Decimal getConsumptionQuantity() throws Exception
```

获取消耗文件大小

**Returns:**
消耗数量 @throws Exception 如果 Metered API 出现问题。

### setMeteredKey {#setMeteredKey-java.lang.String-java.lang.String-}
设置计量的公钥和私钥
