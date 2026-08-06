---
title: "save_epub"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ مستند PDF المفتوح مسبقًا كمستند EPUB."
type: docs
url: /ar/rust-cpp/convert/save_epub/
---

_يقوم بتحويل وحفظ مستند PDF-document المفتوح مسبقًا كملف EPUB-document._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // تحويل وحفظ المستند PDF-document المفتوح مسبقًا كملف Epub-document
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```