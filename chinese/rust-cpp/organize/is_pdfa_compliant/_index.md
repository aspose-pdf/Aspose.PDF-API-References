---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF-document 是否符合 PDF/A。"
type: docs
url: /zh/rust-cpp/organize/is_pdfa_compliant/
---

_获取 PDF-document 是否符合 PDF/A._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 获取 PDF-document 的 PDF/A 合规状态
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```