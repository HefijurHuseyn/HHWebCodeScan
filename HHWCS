import requests
Bir = input("Bu Tool HefijurHuseyn Tarafından kodlanmıştır. Lütfen Devam yazın:")
if Bir=="Devam":
	kod = input("Kodunu Alacağınız sitenin linkini girin:")
else:
	print("İşlem iptal edildi")
kodualma = requests.get(kod)
print("Site kodu:",kodualma.text)
