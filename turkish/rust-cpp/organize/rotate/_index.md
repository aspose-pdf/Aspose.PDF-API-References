---
title: "rotate"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dosyayı döndürür."
type: docs
url: /tr/rust-cpp/organize/rotate/
---

_PDF-dosyayı döndürür._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dosyayı Döndür
    pdf.rotate(Rotation::On270)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```