```markdown
# Luxury Car Price List 2025 🚗💨

Daftar harga mobil mewah terkini tahun 2025 dengan tampilan modern dan responsif

![Preview](preview.jpg) <!-- Tambahkan screenshot proyek Anda -->

## Fitur Utama ✨
- Tampilan tabel modern dengan dark theme
- Responsive design untuk semua perangkat
- Gradient effect dan glow animation
- Warna berbeda untuk setiap merek mobil
- Hover effect pada baris tabel
- Format harga USD dan IDR
- Copyright notice developer

## Teknologi Yang Digunakan 🛠️
- HTML5
- Tailwind CSS
- Google Fonts (Roboto Condensed)
- CSS3 Modern (Gradient, Shadow, Animation)

## Cara Menggunakan 🚀
1. Clone repositori ini
```bash
git clone https://github.com/username/repo-name.git
```
2. Buka file `index.html` di browser
3. Untuk development, gunakan Live Server

## Struktur Data 🗃️
Format data mobil dalam tabel:
```html
<tr class="hover:bg-gray-800/30 transition-colors group">
    <td class="py-4 px-6 font-mono text-[color]-400">[nomor]</td>
    <td class="py-4 px-6 flex items-center">
        <div class="w-2 h-2 bg-[color]-500 rounded-full mr-3"></div>
        [Merek]
    </td>
    <td class="py-4 px-6">[Model]</td>
    <td class="py-4 px-6 text-center font-bold text-green-400">[Harga USD]</td>
    <td class="py-4 px-6 text-center font-bold text-purple-400">[Harga IDR]</td>
</tr>
```

## Customization 🎨
Untuk memodifikasi tampilan:
1. Ubah warna tema di `style` tag:
```css
.price-table {
    background: linear-gradient(145deg, #0a0a0a 0%, #1a1a1a 100%);
    box-shadow: 0 0 40px rgba(99, 102, 241, 0.1);
}
```
2. Tambahkan merek baru dengan warna berbeda:
```html
<div class="w-2 h-2 bg-[warna]-500 rounded-full mr-3"></div>
```
3. Update data harga di tabel sesuai kebutuhan

## Berkontribusi 🤝
1. Fork repositori
2. Buat branch fitur baru
```bash
git checkout -b fitur-baru
```
3. Commit perubahan
```bash
git commit -m 'Tambahkan fitur baru'
```
4. Push ke branch
```bash
git push origin fitur-baru
```
5. Buat Pull Request

## Lisensi 📄
MIT License

Copyright © 2024 [ijajkeyboard](https://github.com/ijajkeyboard)

---

**Developed with ❤️ by ijajkeyboard**  
📧 Contact: [your-email@example.com](mailto:ijajkeyboard001@gmail.com)
```

Tips penggunaan:
1. Ganti `[username/repo-name]` dengan detail repositori Anda
2. Tambahkan screenshot aktual (ubah `preview.jpg`)
3. Sesuaikan informasi kontak dan lisensi sesuai kebutuhan
4. Update bagian fitur jika menambahkan fungsi baru
