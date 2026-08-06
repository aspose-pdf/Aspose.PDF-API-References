---
title: "clear_meta_info"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يمسح جميع قيم معلومات التعريف لمستند PDF."
type: docs
url: /ar/rust-cpp/core/clear_meta_info/
---

_يمسح جميع قيم معلومات التعريف لمستند PDF._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // مسح جميع قيم معلومات التعريف لمستند PDF
    pdf.clear_meta_info()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```