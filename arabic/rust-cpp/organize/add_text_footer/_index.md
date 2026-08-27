---
title: "add_text_footer"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف نصًا في تذييل مستند PDF."
type: docs
url: /ar/rust-cpp/organize/add_text_footer/
---

_يضيف نصًا في تذييل مستند PDF._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة نص في تذييل PDF-document
    pdf.add_text_footer("FOOTER")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```