# praktikum6
NAMA : Angga Muhamad Gojali  
NIM : 312210056  
Kelas : TI.22.C1  

# Langkah-langkah :
+ Buat programnya dengan source code seperti ini:
print("======> Angga Muhamad Gojali <======")  
print("======> Program Input Data <======")  
print("======> TI.22.C1 <======")  
data = {}  
while True:  
print("") m = input(" (L)ihat, (T)ambah, (U)bah, (H)apus, (C)ari, (K)eluar : ")  
print("================================================================") 
print("| NO | Nama | Nim | Tugas | UTS | UAS | Akir |") 
print("================================================================")  
print(">>>>>>>>>>>>>>>>>>>>>>>> TIDAK ADA DATA <<<<<<<<<<<<<<<<<<<<<<<<")  
if m.lower() == 'k':  
break

            print("|  1 |{0:9}   |{1:9}     |{2:9} |{3:9}  |{4:9}   |{5:9}  |".format(x[0], x[1][0],
                                                                                      x[1][1], x[1][2], x[1][3],
                                                                                      x[1][4], i))

        else:
            print("====================>>>>>>>>>>>>> Tidak Ada Data <<<<<<<<<<<<<====================")

    elif m.lower() == 't':
        print("--------------- Tambah Data ---------------")
        nama=input("Nama                  : ")
        nim=input("Nim                   : ")
        tugas=float(input("Masukan Nilai Tugas   : "))
        uts=float(input("Masukan Nilai UTS     : "))
        uas=float(input("Masukan Nilai UAS     : "))
        akhir=(int(tugas) * .30) + (int(uts) * .35) + (int(uas) * .35)
        data[nama]=nim, tugas, uts, uas, akhir

    elif m.lower() == 'u':
        print("----- Ubah Data Mahasiswa -----")
        nama=input("Nama  : ")
        if nama in data.keys():
            nim=input("Nim : ")
            tugas=float(input("masukan nilai tugas : "))
            uts=float(input("masukan nilai Uts : "))
            uas=float(input("masukan nilai uas : "))
            akhir=(int(tugas) * .30) + (int(uts) * .35) + (int(uas) * .35)
            data[nama]=nim, tugas, uts, uas, akhir

        else:
            print("Tidak Ada data")

    elif m.lower() == 'h':
        print("Hapus Data Mahasiswa")
        nama=input("nama : ")
        if nama in data.keys():
            print("Datanya", nama, "adalah {0}".format(data[nama]))
        else:
            print("Tidaak Ada Data")

    elif m.lower() == 'c':
        print("Cari Data")
        nama=input("Masukkan Nama : ")
        if nama in data.keys():
            print("Data Telah Di Temukan")
            print("=" * 73)
            print("|                             Daftar Mahasiswa                          |")
            print("=" * 73)
            print("| Nama            |       NIM       |  UTS  |  UAS  |  Tugas  |  Akhir  |")
            print("=" * 73)
            print("| {0:9} | {1:9} | {2:9} | {3:9} | {4:9} | {5:9} |"
                  .format(nama, nim, uts, uas, tugas, akhir))

            print("=" * 73)
        else:
            print("Nama {0} Tidak Ditemukan".format(nama))

    else:
        print("Pilih menu yang tersedia")

+ Screenshot codingannya


![Screenshot1](https://user-images.githubusercontent.com/116193257/204694152-7d7ec2b0-fc1c-4ddd-af25-3763509e0a1d.png)

![Screenshot2](https://user-images.githubusercontent.com/116193257/204694193-a621165b-28e3-4830-b91b-5e47ebe7f15b.png)

+ Screenshot hasil codingannya

![Screenshot3](https://user-images.githubusercontent.com/116193257/204694337-91ac40d9-e0cd-49d0-a604-366d4511d88a.png)

+ Flowchartnya

![screenshot4](https://user-images.githubusercontent.com/116193257/204694454-02e7241c-a8ce-4514-b3fb-71db31b4893f.jpg)

+ SELESAI,TERIMAKASIH
