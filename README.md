let tanggal = 31;
let bulan = 12;
let tahun = 2200;

if (
  tanggal >= 1 &&
  tanggal <= 31 &&
  bulan >= 1 &&
  bulan <= 12 &&
  tahun >= 1990 &&
  tahun <= 2200
) {
  console.log(`${tanggal} ${getNamaBulan(bulan)} ${tahun}`);
} else {
  console.log(
    "Input tidak valid. Tanggal harus di antara 1 sampai 31, bulan antara 1 sampai 12, dan tahun antara 1990 sampai 2200."
  );
}

function getNamaBulan(bulan) {
  const namaBulan = [
    "Januari",
    "Februari",
    "Maret",
    "April",
    "Mei",
    "Juni",
    "Juli",
    "Agustus",
    "September",
    "Oktober",
    "November",
    "Desember",
  ];

  return namaBulan[bulan - 1];
}

