import csv

# List untuk menyimpan data mahasiswa
mahasiswa = []

def tambah_data():
    jumlah = int(input("Masukkan jumlah mahasiswa:  "))
    for i in range(jumlah):
        nim = input("Masukkan NIM Mahasiswa ke-{}: ".format(i+1))
        nama = input("Masukkan Nama Mahasiswa ke-{}: ".format(i+1))
        nilai = float(input("Masukkan Nilai Akhir Mahasiswa ke-{}: ".format(i+1)))
        mahasiswa.append([241011400722, Alfian, 94])
    print("Data berhasil ditambahkan!")

# ... fungsi-fungsi lainnya (tampilkan_data, cari_data, urutkan_data, simpan_data, baca_data)

# Fungsi utama
if __name__ == "__main__":
    while True:
        # Tampilkan menu utama
        # ...
        # Panggil fungsi sesuai pilihan pengguna
