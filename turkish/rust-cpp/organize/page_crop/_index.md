---
title: "page_crop"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Bir sayfayı kırpar."
type: docs
url: /tr/rust-cpp/organize/page_crop/
---

_Bir sayfayı kırpar._

```rust
pub fn page_crop(&self, num: i32, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **margin** - page margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Bir sayfayı kırp
    pdf.page_crop(1, 1.0)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_crop.pdf")?;

    Ok(())
}

```