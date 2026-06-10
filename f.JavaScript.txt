if(siswaLulus.includes(nama)){

    tampilkanConfetti();

    hasil.innerHTML = `
    <div class="lulus">

        <h1>🎉 SELAMAT 🎓</h1>

        <h2>${nama}</h2>

        <p>
        Dinyatakan
        <b>LULUS</b>
        dari SD Negeri Laweueng
        Tahun Pelajaran 2024/2025
        </p>

        <br>

        <button onclick="window.print()">
        🖨 Cetak Hasil
        </button>

    </div>
    `;
}