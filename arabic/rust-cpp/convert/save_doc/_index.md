---
title: "save_doc"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كملف DOC-document."
type: docs
url: /ar/rust-cpp/convert/save_doc/
---

_يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كملف DOC-document._

```rust
pub fn save_doc(&self, filename: &str) -> Result<(), PdfError>
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

    // تحويل وحفظ المستند PDF-document المفتوح مسبقًا كملف Doc-document
    pdf.save_doc("sample.doc")?;

    Ok(())
}

```