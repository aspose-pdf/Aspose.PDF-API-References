---
title: "validate"
second_title: "Aspose.PDF for Rust via C++"
description: "验证 PDF 文档是否符合 PDF 格式规范。"
type: docs
url: /zh/rust-cpp/organize/validate/
---

_验证 PDF 文档是否符合 PDF 格式规范。_

```rust
    pub fn validate(
        &self,
        pdf_format: PdfFormat,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the validation log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 验证 PDF 文档是否符合 PDF 格式的规范
    let (ok, log) = pdf.validate(PdfFormat::PDF_A_2A)?;

    // 打印验证结果和完整日志
    println!("Validate PDF/A result: {}", ok);
    println!("Validate PDF/A log:\n{}", log);

    Ok(())
}

```