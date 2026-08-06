---
title: "set_background"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının arka plan rengini RGB değerleriyle ayarlar."
type: docs
url: /tr/rust-cpp/organize/set_background/
---

_PDF-dökümanının arka plan rengini RGB değerleriyle ayarlar._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanının arka plan rengini RGB değerleriyle ayarla
    pdf.set_background(200, 100, 101)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```