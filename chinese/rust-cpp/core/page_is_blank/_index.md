---
title: "page_is_blank"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF-document 中页面是否为空白。"
type: docs
url: /zh/rust-cpp/core/page_is_blank/
---

_返回 PDF 文档中的页面为空。_

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 指定页码（基于 1 的索引）
    let page_number = 1;

    // 返回 PDF 文档中的页面为空
    let is_blank = pdf.page_is_blank(page_number)?;

    // 如果指定的页面为空则打印
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```