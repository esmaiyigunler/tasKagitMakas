import random

secenekler=["taş","kağıt","makas"]
oyuncuSkoru=0
bilgisayarSkoru=0

print("Taş,kağıt,makas oyununa hoş geldiniz. En iyi 3 turu kazanan oyunu kazanır")

#3 tur için döngü

for tur in range(1,4):
    print(f"\n{tur}. Tur")

    #oyuncunun seçimi
    oyuncuSecimi=input("taş kağıt makas seçin: ").lower()

    #bilgisayarın seçimi
    bilgisayarSecimi=random.choice(secenekler)

    print("Bilgisayarın seçimi: {bilgisayarSecimi}")

    #kazananı belirleyelim
    if oyuncuSecimi==bilgisayarSecimi:
        print("Berabere!")
    elif (oyuncuSecimi=="taş" and bilgisayarSecimi=="makas")or (oyuncuSecimi=="makas" and bilgisayarSecimi=="kağıt")or (oyuncuSecimi=="kağıt" and bilgisayarSecimi=="taş"):
        print("Bu turu sen kazandın")
        oyuncuSkoru+=1
    else:
        print("Bu turu bilgisayar kazandı")
        bilgisayarSkoru+=1

#oyun sonu
print("\nOyun bitti")
print(f"Senin skorun: {oyuncuSkoru}")
print(f"Bilgisayarın skoru: {bilgisayarSkoru}")

if oyuncuSkoru>bilgisayarSkoru:
    print("Tebrikler, oyunu kazandın")
elif bilgisayarSkoru>oyuncuSkoru:
    print("Maaalesef, oyunu bilgisayar kazandı")
else:
    print("Oyun berabere bitti")
