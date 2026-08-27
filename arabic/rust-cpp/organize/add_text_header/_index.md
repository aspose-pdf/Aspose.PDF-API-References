---
title: "add_text_header"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف نصًا في رأس مستند PDF."
type: docs
url: /ar/rust-cpp/organize/add_text_header/
---

_يضيف نصًا في رأس مستند PDF._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة نص في رأس PDF-document
    pdf.add_text_header("HEADER")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```