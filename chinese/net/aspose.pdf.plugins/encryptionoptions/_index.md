---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.EncryptionOptions 类。表示安全插件的加密选项
type: docs
weight: 8540
url: /zh/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions 类

表示 [`Security`](../security/) 插件的加密选项。

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | 使用默认选项初始化 `EncryptionOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 操作完成后关闭输入流。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 操作完成后关闭输出流。 |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | 加密算法，详细信息请参见 [`CryptoAlgorithm`](./cryptoalgorithm/)。 |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | 文档权限，详细信息请参见 [`Permissions`](../../aspose.pdf/permissions/)。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | 返回 OrganizerOptions 插件数据集合。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 获取添加的目标集合以保存操作结果。 |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | 拥有者密码。 |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | 用户密码。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | 将新的数据源添加到 PdfOrganizer 插件数据集合。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | 将新的数据源添加到 PdfOrganizer 插件数据集合。 |

### 另请参见

* 类 [OrganizerBaseOptions](../organizerbaseoptions/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)