---
title: "yeni"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Yeni bir PDF-döküman oluşturur."
type: docs
url: /tr/rust-cpp/core/new/
---

_Yeni bir PDF-döküman oluşturur._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Yeni bir PDF-document oluştur
    let pdf = Document::new()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```