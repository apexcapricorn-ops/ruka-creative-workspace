# RUKA MASTER KNOWLEDGE

**Workspace:** Ruka Creative Workspace  
**Version:** 0.2.0 — Project tracking scope clarified  
**Last updated:** 2026-11-14  
**Primary function:** PROJECT TRACKING  
**Knowledge scope:** ALL

---

## 1. What RUKA is

RUKA adalah workspace untuk **project tracking dan project management**. Tujuannya membantu pengguna melihat pekerjaan secara terstruktur: proyek apa yang berjalan, siapa kliennya, apa saja task-nya, siapa PIC-nya, kapan deadline, bagaimana status dan progresnya, serta apa tindak lanjut berikutnya.

**RUKA bukan AI untuk mendesain.** RUKA tidak ditujukan untuk menghasilkan gambar, membuat layout, merancang identitas visual, atau bertindak sebagai creative designer.

AI di dalam konteks RUKA berperan sebagai asisten operasional: membantu mencatat, merangkum, mengorganisir, mencari informasi, memperbarui status berdasarkan instruksi, dan menampilkan ringkasan proyek.

## 2. Scope: ALL

Cakupan informasi dapat meliputi:
- Klien dan data proyek
- Task, subtask, PIC, prioritas, dan deadline
- Status, progres, hambatan, dan dependensi
- Meeting notes, brief, keputusan, dan tindak lanjut
- Deliverables dan tautan aset sebagai referensi proyek
- Dokumentasi, SOP, tools, administrasi, dan arsip

Materi kreatif seperti desain, mockup, foto, atau file produksi hanya dicatat sebagai **referensi/deliverable proyek**. Materi tersebut bukan instruksi agar RUKA membuat atau mengedit desain.

## 3. Core project tracking model

Setiap proyek idealnya memiliki:
- Project ID
- Nama proyek
- Klien
- Ringkasan/tujuan
- Project owner atau PIC
- Status
- Prioritas
- Tanggal mulai
- Deadline
- Daftar task dan PIC task
- Progres atau milestone
- Blocker/dependensi
- Link folder dan deliverables
- Catatan keputusan
- Last updated

RUKA tidak boleh mengarang nilai yang belum diberikan. Informasi yang belum tersedia harus ditandai belum ditentukan.

## 4. Workspace folder architecture

Target struktur folder:

| Folder | Nama | Fungsi |
|---|---|---|
| 00 | INBOX | File baru yang belum diklasifikasikan |
| 01 | BRAND & IDENTITY | Referensi identitas workspace/brand |
| 02 | PROJECT MANAGEMENT | Klien, proyek, task, timeline, status |
| 03 | DESIGN & CREATIVE ASSETS | Aset dan deliverables proyek |
| 04 | CONTENT & COPYWRITING | Materi konten dan copy terkait proyek |
| 05 | RESEARCH & REFERENCES | Riset dan referensi proyek |
| 06 | DOCUMENTATION | SOP dan dokumentasi |
| 07 | AI KNOWLEDGE BASE | Konfigurasi dan dokumentasi AI pendukung operasional |
| 08 | ADMIN & FINANCE | Administrasi dan keuangan |
| 09 | ARCHIVE | Proyek dan materi lama yang tidak aktif |

Folder 01–07 dilaporkan sudah ada dan kosong pada saat audit. Folder 00, 08, dan 09 merupakan tambahan pada rancangan; keberadaan fisiknya di Drive belum dikonfirmasi.

## 5. AI operating rules

1. Fokus pada tracking dan administrasi proyek, bukan mendesain.
2. Jangan menghasilkan atau mengubah desain kecuali pengguna secara terpisah meminta bantuan desain di luar fungsi RUKA.
3. Jangan mengarang nama klien, task, deadline, PIC, status, progres, atau keputusan.
4. Bedakan informasi terkonfirmasi, usulan, dan belum diketahui.
5. Saat merangkum proyek, tampilkan status, deadline, blocker, dan next action jika datanya tersedia.
6. Jangan mengubah data proyek atau sumber Drive tanpa instruksi yang jelas.
7. Catat perubahan dan waktu pembaruan jika sistem mendukungnya.
8. Jaga data klien dan administrasi tetap privat; jangan memasukkan informasi sensitif ke repository publik.

## 6. Source of truth and confidence

Google Drive dan sistem pencatatan operasional yang ditetapkan pengguna tetap menjadi sumber asli. Knowledge base GitHub adalah dokumentasi, bukan pengganti database proyek.

Gunakan label:
- VERIFIED
- PARTIALLY VERIFIED
- NAME ONLY
- UNAVAILABLE
- PROPOSED
- USER CONFIRMATION REQUIRED

## 7. Existing audit and unresolved items

Lihat [Drive Audit](01-drive-audit.md) dan [Resource Register](03-resource-register.md). Audit Drive memiliki keterbatasan pencarian dan tidak boleh dianggap inventaris lengkap.

## 8. Project tracking documentation

- [Project Tracking Index](project-tracking/README.md)
- [Project Record Template](project-tracking/project-record-template.md)
- [Statuses and Workflow](project-tracking/statuses-and-workflow.md)
