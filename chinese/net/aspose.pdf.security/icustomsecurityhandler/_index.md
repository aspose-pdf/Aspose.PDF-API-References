---
title: "接口 ICustomSecurityHandler"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Security.ICustomSecurityHandler 接口。自定义安全处理程序接口。"
type: docs
weight: 10150
url: /zh/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

自定义安全处理程序接口。

```csharp
public interface ICustomSecurityHandler
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | 获取过滤器名称。 |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | 获取密钥长度。 |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | 获取处理程序或加密算法的修订版本。 |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | 获取子过滤器名称。 |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | 获取处理程序或加密算法的版本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | 计算 EncryptionKey。通常密钥是基于 UserKey 计算的。您可以使用 EncryptionParams 中的值，该对象包含调用时的当前参数。此值作为 key 参数传递给 [`Encrypt`](./encrypt/) 和 [`Decrypt`](./decrypt/)。 |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | 解密数据数组。 |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | 加密数据数组。 |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | 加密文档的 permissions 字段。结果将写入 Perms 加密字典字段。打开文档时，可通过 [`EncryptionParameters`](../encryptionparameters/) 的 Perms 字段获取该值。此操作允许您检查文档权限是否已更改。 |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | 基于密码创建一个编码数组，该数组将写入加密字典的 O 字段。应仅依赖传入的参数。可以使用所有者密码从该字段计算出用户密码。加密过程中调用此方法以准备并填充加密字典。该值将在 [`CalculateEncryptionKey`](./calculateencryptionkey/) 中可用，以从 UserKey 获取密钥。调用文档加密时用户指定的密码将被传递。密码可能未指定，或仅指定一个。 |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | 基于用户密码创建一个编码数组。此值通常用于检查密码是属于用户还是所有者，并获取加密密钥。加密过程中调用此方法以准备并填充加密字典。调用文档加密时，用户指定的密码作为参数传递。 |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | 用于初始化当前实例以进行加密的调用。请注意，在加密时，它将填充来自转移属性 `ICustomSecurityHandler` 的数据，并在从加密字典打开文档时填充。如果在新加密过程中调用此方法，则 [`UserKey`](../encryptionparameters/userkey/) 和 [`OwnerKey`](../encryptionparameters/ownerkey/) 将为 null。 |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | 检查密码是否为文档所有者的密码。该方法在 Initialize 之后调用。此方法调用在 PDF API 中使用。 |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | 检查密码是否属于用户（用于打开文档的密码）。该方法在 Initialize 之后调用。此方法调用在 PDF API 中使用。 |

### 另请参见

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


