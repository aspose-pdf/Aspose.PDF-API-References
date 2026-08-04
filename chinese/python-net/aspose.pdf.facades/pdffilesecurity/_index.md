---
title: "PdfFileSecurity"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示使用所有者或用户密码对 Pdf 文件进行加密或解密，修改安全设置和密码。"
type: docs
weight: 300
url: /zh/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

表示使用所有者或用户密码对 Pdf 文件进行加密或解密，修改安全设置和密码。

PdfFileSecurity 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | 初始化 PdfFileSecurity 类的新实例 |
| PdfFileSecurity(input_file, output_file) | 初始化 PdfFileSecurity 类的新实例 |
| PdfFileSecurity() | 初始化 PdfFileSecurity 对象。 |
| PdfFileSecurity(document) | 初始化 PdfFileSecurity 类的新实例 |
| PdfFileSecurity(document, output_file) | 初始化 PdfFileSecurity 类的新实例 |
| PdfFileSecurity(document, output_stream) | 初始化 PdfFileSecurity 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| allow_exceptions | 如果此值设为 true，则在操作失败时会抛出异常。否则，方法在失败时返回 false，且可以通过 LastException 属性检查最后的异常。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 初始化外观。 |
| bind_pdf(src_stream) | 初始化外观。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| encrypt_file(user_password, owner_password, privilege, key_size) | 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。<br/>            用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，所有者密码将被替换为随机字符串。<br/>            处理失败时抛出异常。 |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。<br/>            用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，所有者密码将被替换为随机字符串。<br/>            KeySize 和 Algorithm 值共有 6 种可能的组合。<br/>            但是 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合，将抛出相应的异常。<br/>            处理失败时抛出异常。 |
| set_privilege(privilege) | 使用空的用户/所有者密码设置 Pdf 文件安全。<br/>            所有者密码将由随机字符串生成。<br/>            处理失败时抛出异常。 |
| set_privilege(user_password, owner_password, privilege) | 使用原始密码设置 Pdf 文件安全。<br/>            处理失败时抛出异常。 |
| change_password(owner_password, new_user_password, new_owner_password) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被替换为随机字符串。<br/>            处理失败时抛出异常。 |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被替换为随机字符串。<br/>            处理失败时抛出异常。 |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被替换为随机字符串。<br/>            KeySize 和 Algorithm 值共有 6 种可能的组合。<br/>            但是 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合，将抛出相应的异常。<br/>            处理失败时抛出异常。 |
| try_change_password(owner_password, new_user_password, new_owner_password) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被随机字符串替换。<br/>            处理失败时不抛出异常。 |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被随机字符串替换。<br/>            处理失败时不抛出异常。 |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全。<br/>            新的用户密码和新的所有者密码可以为 null 或空。如果新的所有者密码为 null 或空，所有者密码将被随机字符串替换。<br/>            KeySize 和 Algorithm 值共有 6 种可能的组合。<br/>            但是 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合，将抛出相应的异常。<br/>            处理失败时不抛出异常。 |
| close() | 关闭外观。 |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | 使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。<br/>            用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被替换为随机字符串。<br/>            处理失败时不抛出异常。 |
| decrypt_file(owner_password) | 使用所有者密码解密加密的 Pdf 文档。<br/>            如果文档没有所有者密码，则允许使用用户密码。<br/>            处理失败时抛出异常。 |
| try_decrypt_file(owner_password) | 使用所有者密码解密加密的 Pdf 文档。<br/>            如果文档没有所有者密码，则允许使用用户密码。<br/>            处理失败时不抛出异常。 |
| try_set_privilege(user_password, owner_password, privilege) | 使用原始密码设置 Pdf 文件的安全性。<br/>            处理失败时不抛出异常。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

