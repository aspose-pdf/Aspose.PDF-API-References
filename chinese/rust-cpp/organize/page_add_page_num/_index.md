---
title: "page_add_page_num"
second_title: "Aspose.PDF for Rust via C++"
description: "在页面上添加页码。"
type: docs
url: /zh/rust-cpp/organize/page_add_page_num/
---

_在页面上添加页码。_

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在页面上添加页码
    pdf.page_add_page_num(1)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```