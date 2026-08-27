---
title: "word_count"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF-document 中的字数。"
type: docs
url: /zh/rust-cpp/core/word_count/
---

_返回 PDF-document 中的字数._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 返回 PDF-document 中的字数
    let count = pdf.word_count()?;

    // 打印字数
    println!("Word count: {}", count);

    Ok(())
}

```