---
title: "kırp"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Bir PDF-dökümanın sayfalarını kırpar."
type: docs
url: /tr/rust-cpp/organize/crop/
---

_Bir PDF-dökümanın sayfalarını kırpar._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanın sayfalarını kırp
    pdf.crop(10.5)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```