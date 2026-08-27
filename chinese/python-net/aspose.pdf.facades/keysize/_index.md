---
title: "KeySize"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "定义可用于加密 PDF 文档的不同密钥大小。"
type: docs
weight: 590
url: /zh/python-net/aspose.pdf.facades/keysize/
---

## KeySize enumeration

定义可用于加密 PDF 文档的不同密钥大小。

## Members
| Member name | 描述 |
| :- | :- |
| X40 | 40 位密钥。此密钥长度用于 RC4 算法，提供低安全性。<br/>            然而，旧版本的 PDF 文档只能使用此类密钥进行加密（v. 1.3 及以下）； |
| X128 | 128 位密钥。RC4 和 AES 算法都可以使用此密钥大小。 |
| X256 | 256 位密钥。此密钥大小只能与 AES 一起使用，并在最新的 Adobe Reader 版本（从 v.9 开始）中被识别。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

