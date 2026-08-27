---
title: "page_word_count"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF-document 中指定页面的字数。"
type: docs
url: /zh/rust-cpp/core/page_word_count/
---

_返回 PDF-document 中指定页面的字数._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 指定页码（基于 1 的索引）
    let page_number = 1;

    // 返回指定页面的字数
    let count = pdf.page_word_count(page_number)?;

    // 打印字数
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```