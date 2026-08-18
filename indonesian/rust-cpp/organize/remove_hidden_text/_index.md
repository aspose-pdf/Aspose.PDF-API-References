---
title: "remove_hidden_text"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus teks tersembunyi dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_hidden_text/
---

_Menghapus teks tersembunyi dari dokumen PDF._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Hapus teks tersembunyi dari PDF-document
    pdf.remove_hidden_text()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```