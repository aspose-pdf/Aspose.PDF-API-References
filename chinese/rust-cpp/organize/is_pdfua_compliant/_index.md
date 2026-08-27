---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF 文档是否符合 PDF/UA 标准。"
type: docs
url: /zh/rust-cpp/organize/is_pdfua_compliant/
---

_获取 PDF 文档是否符合 PDF/UA 标准。_

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // 获取 PDF 文档的 PDF/UA 合规状态
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```