Nama: Mahmud Asrul 
NPM: 2106655255
Kelas: E 

## Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.

Stateless Widget : widget mengikuti dari konfigurasi awal dan tidak akan pernah berubah sifatnya statis
Stateful Widget : widget yang dapat berubah berubah sifatnya dinamis

tergantung kebutuhan si developer untuk menentukan widget seperti apa yang ingin dipakai.

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
- Scaffold = Homepage
- AppBar() = Title
- Center() = Justifying
- Column() = Showing all widget in a vertical way
- Row() = Showing all widget in a horizontal way
- Text() = Showing teks & giving style to the text
- FloatingActionButton() = Showing floating button

## Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
setState() sebagai counter checker, apabila ada perubahan terhadap kondisi tersebut maka aplikasi akan me-refresh widget tersebut dengan value terbaru. Untuk variable di tugas 7 ini yang terpengaruh adalah counter.

## Jelaskan perbedaan antara const dengan final.
mirip seperti Java, const menginisiasi nilai ketika dikompilasi dan sifatnya direct. sedangkan final dapat dijalani tanpa memiliki vairable dan nilai secara direct namun bisa indirect.

## Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
1) if-else genap ganjil berdasarkan nilai
2) menginisiasi widget yang bergerak dari if-else tsb
3) menambahkan fungsi decrementCounter()
4) dari decrementCounter kita mengimplementasikan kepada widget FloatingActionButton
