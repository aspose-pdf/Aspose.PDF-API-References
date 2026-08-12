---
title: "aç"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Dosya adıyla bir PDF belgesi açar."
type: docs
url: /tr/rust-cpp/core/open/
---

_Dosya adıyla bir PDF belgesi açar._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf" adlı bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```