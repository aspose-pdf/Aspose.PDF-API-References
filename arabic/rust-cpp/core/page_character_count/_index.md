---
title: "page_character_count"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد عدد الأحرف في الصفحة المحددة في PDF-document."
type: docs
url: /ar/rust-cpp/core/page_character_count/
---

_يعيد عدد الأحرف في الصفحة المحددة في PDF-document._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
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
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // حدد رقم الصفحة (فهرس يبدأ من 1)
    let page_number = 1;

    // إرجاع عدد الأحرف في الصفحة المحددة
    let count = pdf.page_character_count(page_number)?;

    // اطبع عدد الأحرف
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```