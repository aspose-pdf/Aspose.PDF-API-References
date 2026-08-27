---
title: "convert"
second_title: "Aspose.PDF for Rust via C++"
description: "将 PDF-document 转换为具有指定 PDF 格式的 PDF-document。"
type: docs
url: /zh/rust-cpp/organize/convert/
---

_将 PDF-document 转换为具有指定 PDF 格式的 PDF-document._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 将 PDF 文档转换为具有指定 PDF 格式的 PDF 文档
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // 打印转换结果和完整日志
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```