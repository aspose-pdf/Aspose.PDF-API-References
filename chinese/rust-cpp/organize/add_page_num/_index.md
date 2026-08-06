---
title: "add_page_num"
second_title: "Aspose.PDF for Rust via C++"
description: "向 PDF-document 添加页码。"
type: docs
url: /zh/rust-cpp/organize/add_page_num/
---

_向 PDF-document 添加页码._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // 向 PDF-文档 添加页码
    pdf.add_page_num()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```