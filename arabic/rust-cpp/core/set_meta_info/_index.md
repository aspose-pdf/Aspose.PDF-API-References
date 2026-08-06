---
title: "set_meta_info"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضبط قيمة معلومات التعريف لمستند PDF."
type: docs
url: /ar/rust-cpp/core/set_meta_info/
---

_يضبط قيمة معلومات التعريف لمستند PDF._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // ضبط قيمة معلومات التعريف لمستند PDF
    pdf.set_meta_info("Author", "Aspose")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```