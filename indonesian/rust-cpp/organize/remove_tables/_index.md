---
title: "remove_tables"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus tabel dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_tables/
---

_Menghapus tabel dari dokumen PDF._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // Hapus tabel dari dokumen PDF
    pdf.remove_tables()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```