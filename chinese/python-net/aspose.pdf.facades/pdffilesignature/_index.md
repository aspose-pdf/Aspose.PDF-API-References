---
title: "PdfFileSignature"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示用于使用证书对 pdf 文件进行签名的类。"
type: docs
weight: 310
url: /zh/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

表示用于使用证书对 pdf 文件进行签名的类。

PdfFileSignature 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileSignature() | PdfFileSignature 类的构造函数。 |
| PdfFileSignature(input_file) | 初始化 PdfFileSignature 类的新实例 |
| PdfFileSignature(input_file, output_file) | 初始化 PdfFileSignature 类的新实例 |
| PdfFileSignature(document) | 初始化 PdfFileSignature 类的新实例 |
| PdfFileSignature(document, output_file) | 初始化 PdfFileSignature 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| signature_appearance | 设置或获取签名的图形外观。属性值表示图像文件名。 |
| is_ltv_enabled | 获取 LTV 启用标志。 |
| is_certified | 获取确定文档是否已认证的标志。 |
| signature_appearance_stream | 设置或获取签名的图形外观。属性值表示图像流。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(input_file) | 绑定 Pdf 文件以进行编辑。 |
| bind_pdf(input_stream) | 绑定 Pdf 流以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(output_file) | 将结果 PDF 保存到文件。 |
| save(output_stream) | 将结果 PDF 保存到流。 |
| save() | 将结果 PDF 保存到文件。 |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | 在 pdf 文档上进行签名。 |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 使用给定类型的签名对文档进行签名。 |
| sign(page, visible, annot_rect, sig) | 使用给定类型的签名对文档进行签名。 |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | 使用给定类型的签名对文档进行签名。 |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 使用给定类型的签名对文档进行签名。 |
| sign(sig_name, sig) | 使用给定类型的签名对文档进行签名。 |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | 使用 MDP 签名对文档进行认证。<br/>            必须通过 Signature 对象 sig 的相应属性提供签名原因、联系信息和位置等数据。 |
| certify(sig_name, doc_mdp_signature) | 使用 MDP 签名对文档进行认证。<br/>            必须通过 Signature 对象 sig 的相应属性提供签名原因、联系信息和位置等数据。 |
| remove_signature(sign_name) | 根据签名名称移除签名。 |
| remove_signature(sign_name, remove_field) | 根据签名名称移除签名。 |
| close() | 关闭外观。 |
| get_access_permissions() | 返回通过 MDP 签名类型对已认证文档的访问权限值。 |
| get_sign_names(only_active) | 获取所有非空签名的名称。 |
| get_blank_sign_names() | 获取所有空签名字段的名称。 |
| is_contain_signature() | 检查 PDF 是否具有数字签名。 |
| contains_signature() | 检查 PDF 是否具有数字签名。 |
| contains_usage_rights() | 检查 PDF 是否具有使用权限。 |
| is_covers_whole_document(sign_name) | 检查签名是否覆盖整个文档。 |
| covers_whole_document(sign_name) | 检查签名是否覆盖整个文档。 |
| get_revision(sign_name) | 获取签名的修订版本。 |
| get_total_revision() | 获取总体修订。 |
| remove_usage_rights() | 删除使用权条目。 |
| verify_signed(sign_name) | 检查签名的有效性。 |
| get_signer_name(sign_name) | 获取签署 PDF 文档的个人或组织的名称。 |
| get_date_time(sign_name) | 获取签名的日期时间。 |
| get_reason(sign_name) | 获取签名的原因。 |
| get_location(sign_name) | 获取签名的位置。 |
| get_contact_info(sign_name) | 获取签名的联系信息。 |
| verify_signature(sign_name) | 检查签名的有效性。 |
| extract_image(sign_name) | 提取签名的图像。 |
| extract_certificate(sign_name) | 将签名的单个 X.509 证书提取为流。 |
| set_certificate(pfx, pass) | 设置签名过程的证书文件和密码。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

