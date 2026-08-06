---
title: "add_text_header"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan teks di Header dokumen PDF."
type: docs
url: /id/rust-cpp/organize/add_text_header/
---

_Menambahkan teks di Header dokumen PDF._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan teks di Header PDF-document
    pdf.add_text_header("HEADER")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```