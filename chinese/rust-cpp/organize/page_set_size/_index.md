---
title: "page_set_size"
second_title: "Aspose.PDF for Rust via C++"
description: "设置 PDF 文档中页面的大小。"
type: docs
url: /zh/rust-cpp/organize/page_set_size/
---

_设置 PDF 文档中页面的大小。_

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 设置 PDF 文档中页面的大小
    pdf.page_set_size(1, PageSize::A1)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```