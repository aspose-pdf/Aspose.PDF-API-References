---
title: "merge_documents"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "ينشئ مستند PDF جديد عن طريق دمج مستندات PDF المقدمة."
type: docs
url: /ar/rust-cpp/core/merge_documents/
---

_ينشئ مستند PDF جديد عن طريق دمج مستندات PDF المقدمة._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // إنشاء مستند PDF-document جديد
    let pdf1 = Document::new()?;

    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // إنشاء مستند PDF جديد عن طريق دمج مستندات PDF المقدمة
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```