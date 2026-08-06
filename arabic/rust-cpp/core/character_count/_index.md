---
title: "character_count"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد عدد الأحرف في PDF-document."
type: docs
url: /ar/rust-cpp/core/character_count/
---

_يعيد عدد الأحرف في PDF-document._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
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

    // إرجاع عدد الأحرف في PDF-document
    let count = pdf.character_count()?;

    // اطبع عدد الأحرف
    println!("Character count: {}", count);

    Ok(())
}

```