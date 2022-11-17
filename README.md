Nama: Mahmud Asrul 
NPM: 2106655255
Kelas: E 

# Tugas 8: Flutter Form

## Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement.
* Navigator.push() menaruh route teratas tanpa menggantikan dengan widget terbaru (stack)
* Navigator.pushReplacement() menggantikan route yang teratas dengan widget terbaru

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
1. Scaffold = main homepage
2. AppBar = title
3. Container = seperti pada container yang kita pelajari di HTML
4. Column = kolom secara vertical
5. Text = mengisi text sesuai harapan

## Sebutkan jenis-jenis event yang ada pada Flutter (contoh: onPressed).
1. onSaved
2. onChange
3. onHover
4. onTap

## Cara kerja Navigator
Navigator --> menampilkan screen paling terdepan pada stack dengan mempertimbangkan object Navigator --> diarahkan ke new layer sehingga bisa diakses pada widgetnya

## Pengimplementasian Checklist
1. New Page
2. New Custom Drawer Widget (note: add separation concern in each pages)
3. Create Navigation Page in Drawer
4. Creating Global List in the root widget sehingga bisa diakses dengan bebas
5. Implement WIdget to the form
6. Implement Save Button --> Safe the newest transaction to the global list
7. Menampilkan semua object budget dengan iterasi.