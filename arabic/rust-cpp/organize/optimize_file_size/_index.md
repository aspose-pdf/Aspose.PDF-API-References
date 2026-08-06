---
title: "optimize_file_size"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحسن حجم مستند PDF باستخدام جودة ضغط الصورة."
type: docs
url: /ar/rust-cpp/organize/optimize_file_size/
---

_يحسن حجم مستند PDF باستخدام جودة ضغط الصورة._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تحسين حجم مستند PDF باستخدام جودة ضغط الصورة
    pdf.optimize_file_size(50)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```