---
title: "get_meta_info"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحصل على قيمة معلومات التعريف لمستند PDF."
type: docs
url: /ar/rust-cpp/core/get_meta_info/
---

_يحصل على قيمة معلومات التعريف لمستند PDF._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // احصل على قيمة معلومات التعريف لمستند PDF
    let author = pdf.get_meta_info("Author")?;

    // اطبع النتيجة
    println!("Author: {}", author);

    Ok(())
}

```