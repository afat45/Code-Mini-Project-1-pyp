print("\nSelamat Datang di calculator tarif kerja")
perintah_1=""
while True:
  data = int(input("""
\n-----------------lobby 1-----------------
1.Sign Up
2.udahan         
silahkan pilih: """))
  if data == 1:
      print("\nSign Up")
      nama = input("Name: ")
      nim = input("NIM: ")
      print("\nData Telah DIkonfirmasi Silahkan Login")
      nama2 = input("Name: ")
      nim2 = input("NIM: ")
      if nama == nama2 and nim == nim2:
      
        perintah = ""
        while True:
            pilihan= int(input("""
\n-----------------lobby 2-----------------                        
1.calculator  
2.udahan
Pilihan: """))
            if pilihan == 1:
              print("\n---------------Calculator--------------- ")
              Waktu = int(input("Berapa Waktu kerja (Jam):  "))
              Tarif = int(input("Tarif Kerja (K) / Jam: "))

              if Waktu < 0:
                  print("tidak bisa angka minus")
              elif Waktu <= 160:
                    A= Waktu*Tarif
                    if A < 1000:
                     print(f"Rp.{A}k")
                    elif A >= 1000:
                     Gaji= A/1000
                     print(f"Rp.{Gaji}jt")
              elif Waktu > 160:
                    B = Waktu*Tarif*1.1
                    C = Waktu*Tarif*0.1
                    if B < 1000:
                      print(f"Rp.{B}k dengan Bonus Rp.{C}K ")
                    elif B >= 1000 and C < 1000:
                      Gaji_Bonus= B/1000
                      print(f"Rp.{Gaji_Bonus}jt dengan Bonus Rp.{C}K ")
                    elif B >= 1000 and C >= 1000:
                      Gaji_Bonus= B/1000
                      Bonusan = C/1000
                      print(f"Rp.{Gaji_Bonus}jt dengan Bonus Rp.{Bonusan}jt ")

            elif pilihan == 2:
                break 
            else:
                print("apa maksud mu? ")
      else:
        print("Data Tidak Sama silahkan ulang")
  elif data == 2:
    print("Sampai Jumpa,Terima Kasih")
    break
  else:
    print("Apa maksud mu? ")
