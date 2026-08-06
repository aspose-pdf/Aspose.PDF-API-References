---
title: "add_text_footer"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan teks di Footer PDF-document."
type: docs
url: /id/rust-cpp/organize/add_text_footer/
---

_Menambahkan teks di Footer PDF-document._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan teks di Footer PDF-document
    pdf.add_text_footer("FOOTER")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```