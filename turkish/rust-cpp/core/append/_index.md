---
title: "append"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Başka bir PDF-document'ten sayfaları ekler."
type: docs
url: /tr/rust-cpp/core/append/
---

_Başka bir PDF-document'ten sayfaları ekler._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ana PDF-document'i aç
    let pdf = Document::open("sample.pdf")?;

    // Başka bir PDF belgesini eklemek için aç
    let another_pdf = Document::open("sample1page.pdf")?;

    // Başka bir PDF belgesinden sayfaları ekle
    pdf.append(&another_pdf)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```