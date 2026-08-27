---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除 PDF/A 合规性。"
type: docs
url: /zh/rust-cpp/organize/remove_pdfa_compliance/
---

_删除 PDF/A 合规性从 PDF-document._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // 从 PDF 文档中移除 PDF/A 合规性
    pdf.remove_pdfa_compliance()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```