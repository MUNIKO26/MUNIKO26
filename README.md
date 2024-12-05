def başlangıç():
    print("Macera Başlıyor!")
    print("Ormanda uyandın ve önünde iki yol var.")
    print("1. Sağdaki patikaya git")
    print("2. Soldaki mağaraya gir")
    
    seçim = input("Hangi yolu seçmek istersin? (1 veya 2): ")
    if seçim == "1":
        patika()
    elif seçim == "2":
        mağara()
    else:
        print("Geçerli bir seçim yapmadın. Tekrar dene!")
        başlangıç()

def patika():
    print("\nPatikada yürümeye başladın. Karşına dev bir ayı çıktı!")
    print("1. Kaç")
    print("2. Ayı ile savaş")
    
    seçim = input("Ne yapacaksın? (1 veya 2): ")
    if seçim == "1":
        print("Kaçarken ayağın takıldı ve düştün. Ayı seni yakaladı. Oyun bitti!")
    elif seçim == "2":
        print("Ayıyı yendin! Kahraman oldun. Tebrikler, oyunu kazandın!")
    else:
        print("Geçerli bir seçim yapmadın. Ayı seni yakaladı. Oyun bitti!")

def mağara():
    print("\nMağaraya girdin ve karşına bir hazine sandığı çıktı.")
    print("1. Sandığı aç")
    print("2. Sandığı görmezden gel ve geri dön")
    
    seçim = input("Ne yapacaksın? (1 veya 2): ")
    if seçim == "1":
        print("Sandığın içinde altınlar buldun! Zengin oldun. Tebrikler!")
    elif seçim == "2":
        print("Geri dönerken mağaranın girişinde bir tuzağa düştün. Oyun bitti!")
    else:
        print("Geçerli bir seçim yapmadın. Mağara çöktü. Oyun bitti!")

# Oyunu başlat
başlangıç()
