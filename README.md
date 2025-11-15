Expense Tracker Workflow – Webinar

Repo ini berisi workflow n8n yang kita pakai untuk sesi webinar “Expense Tracker”.
File JSON di sini bisa kamu import langsung ke n8n, baik lewat URL maupun upload manual.

Video demo : https://www.loom.com/share/ca3c491932f14555b2f17e16433c5aa5
⸻

Isi File

expense-tracker-webinar.json
Workflow ini kurang lebih berisi:
	•	Trigger manual untuk memulai workflow
	•	Function node yang bikin contoh data pengeluaran
	•	Node yang rapikan datanya (title, amount, category, date, notes)
	•	Node Notion untuk kirim data ke database kamu

Tujuannya supaya peserta bisa langsung coba tanpa perlu input apa-apa dulu.

⸻

Cara Import ke n8n

Import lewat URL
	1.	Klik file → klik tombol Raw
	2.	Copy link RAW-nya
	3.	Di n8n, pilih Import from URL, paste link, lalu import

Import lewat File
	1.	Download file JSON
	2.	Di n8n, pilih Import from File
	3.	Upload JSON-nya

⸻

Tujuan Workflow

Workflow ini dibuat untuk latihan dasar:
	•	Cara bikin data dummy untuk testing
	•	Cara format data supaya siap dipakai
	•	Cara kirim data ke Notion lewat n8n
	•	Cara membangun alur sederhana untuk pencatatan pengeluaran
