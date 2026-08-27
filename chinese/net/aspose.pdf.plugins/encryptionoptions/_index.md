---
title: "类 EncryptionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.EncryptionOptions 类。表示用于 Security 插件的加密选项"
type: docs
weight: 8670
url: /zh/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

表示用于 [`Security`](../security/) 插件的加密选项。

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
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 在操作完成后关闭输入流。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 在操作完成后关闭输出流。 |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | 加密算法，详情请参阅 [`CryptoAlgorithm`](./cryptoalgorithm/)。 |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | 文档权限，详情请参阅 [`Permissions`](../../aspose.pdf/permissions/)。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | 返回 OrganizerOptions 插件的数据集合。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 获取已添加目标的集合，用于保存操作结果。 |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | 所有者密码。 |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | 用户密码。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | 向 PdfOrganizer 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | 向 PdfOrganizer 插件的数据集合添加新数据源。 |

### 另请参见

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


