---
title: "page_merge_layers"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يدمج جميع الطبقات على الصفحة في طبقة واحدة مع اسم الطبقة الجديدة المحدد."
type: docs
url: /ar/rust-cpp/organize/page_merge_layers/
---

_يدمج جميع الطبقات على الصفحة في طبقة واحدة مع اسم الطبقة الجديدة المحدد._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // دمج جميع الطبقات على الصفحة في طبقة واحدة مع اسم الطبقة الجديدة المحدد
    pdf.page_merge_layers(1, "New Layer Name")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```