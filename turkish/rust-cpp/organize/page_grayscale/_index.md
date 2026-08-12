---
title: "page_grayscale"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Bir sayfayı siyah beyaza dönüştürür."
type: docs
url: /tr/rust-cpp/organize/page_grayscale/
---

_Bir sayfayı siyah beyaza dönüştürür._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfayı siyah beyaza dönüştür
    pdf.page_grayscale(1)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```