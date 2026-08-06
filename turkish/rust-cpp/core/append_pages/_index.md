---
title: "append_pages"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Başka bir PDF belgesinden seçilen sayfaları ekler."
type: docs
url: /tr/rust-cpp/core/append_pages/
---

_Başka bir PDF belgesinden seçilen sayfaları ekler._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ana PDF-document'i aç
    let pdf = Document::open("sample1page.pdf")?;

    // Başka bir PDF belgesini eklemek için aç
    let another_pdf = Document::open("sample.pdf")?;

    // Başka bir PDF belgesinden belirli sayfaları (1 ve 3) ekle
    pdf.append_pages(&another_pdf, "1,3")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```