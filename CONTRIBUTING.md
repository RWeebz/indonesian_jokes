# Cara berpartisipasi dalam repository ini
1. Fork repository ini
2. Clone repository yang telah ter-fork
3. Tambahkan file username_mu.json ke dalam direktori `indonesian_jokes/src/data/` lalu ikuti structure json seperti di bawah:
```json
{
  "data": [
    {
      "jokes": "Sejak kapan Rengoku hidup di season 2?"
    },
    {
      "jokes": "Kenapa cewek suka bingung cari tempat makan 💁‍♀️? Karena di awal kasih saran makan apa, seluruh umat manusia dilempar ke bumi 🤦‍♂️."
    }
  ],
  "author": "babaiyu"
}
```
> Anda bisa menambahkan lebih banyak jokes dalam key `data`. Pastikan value dari `author` adalah username github yang valid.

4. Setelah point 3, jalankan `npm run generate`
5. Jalankan `npm run dev` untuk melihat hasil dari jokes yang telah ditambahkan
6. Commit perubahan yang ada, push ke origin dan lakukan `pull-request`
