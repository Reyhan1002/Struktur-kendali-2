ulang = 'y'

while ulang.lower() == 'y':
    print("MENENTUKAN JUMLAH HARI DALAM SUATU BULAN")
    bulan = int(input("Masukkan bulan (1-12): "))
    tahun = int(input("Masukkan tahun: "))
    
    # Cek jumlah hari berdasarkan bulan
    if bulan == 1 or bulan == 3 or bulan == 5 or bulan == 7 or bulan == 8 or bulan == 10 or bulan == 12:
        hari = 31
        print(f"Jumlah hari di bulan {bulan} tahun {tahun} ada {hari} hari.")
    elif bulan == 4 or bulan == 6 or bulan == 9 or bulan == 11:
        hari = 30
        print(f"Jumlah hari di bulan {bulan} tahun {tahun} ada {hari} hari.")
    elif bulan == 2:
        # Cek tahun kabisat
        if (tahun % 4 == 0 and tahun % 100 != 0) or (tahun % 400 == 0):
            hari = 29
        else:
            hari = 28
        print(f"Jumlah hari di bulan {bulan} tahun {tahun} ada {hari} hari.")
    else:
        print("Bulan yang kamu masukin salah! (Harus 1-12)")
    
    print()
    ulang = input("Mau ulang lagi? (y/n): ")

print("Terima Kasih!")
