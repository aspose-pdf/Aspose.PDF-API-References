---
title: "flatten"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Meratakan dokumen PDF."
type: docs
url: /id/rust-cpp/organize/flatten/
---

_Meratakan dokumen PDF._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Kembalikan isi dokumen PDF sebagai teks biasa
    let txt = pdf.extract_text()?;

    // Cetak teks yang diekstrak
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```