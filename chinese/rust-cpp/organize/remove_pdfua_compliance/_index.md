---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF 文档中移除 PDF/UA 合规性。"
type: docs
url: /zh/rust-cpp/organize/remove_pdfua_compliance/
---

_从 PDF 文档中移除 PDF/UA 合规性。_

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 从 PDF 文档中移除 PDF/UA 合规性
    pdf.remove_pdfua_compliance()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```