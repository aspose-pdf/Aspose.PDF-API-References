---
title: "word_count"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد عدد الكلمات في مستند PDF-document."
type: docs
url: /ar/rust-cpp/core/word_count/
---

_يعيد عدد الكلمات في مستند PDF-document._

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
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إرجاع عدد الكلمات في مستند PDF-document
    let count = pdf.word_count()?;

    // اطبع عدد الكلمات
    println!("Word count: {}", count);

    Ok(())
}

```