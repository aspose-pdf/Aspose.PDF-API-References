---
title: "save_docx_enhanced"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة DOCX-document مع وضع التعرف المحسن (جداول وفقرات قابلة للتحرير بالكامل)."
type: docs
url: /ar/rust-cpp/convert/save_docx_enhanced/
---

_يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة DOCX-document مع وضع التعرف المحسن (جداول وفقرات قابلة للتحرير بالكامل)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // قم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كوثيقة DocX-document مع وضع التعرف المحسن (جداول وفقرات قابلة للتحرير بالكامل)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```