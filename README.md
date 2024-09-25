# Meminta input dari pengguna
jawaban = input("Apakah kamu menyukai ku? (iya/tidak): ")

# Memeriksa jawaban dan memberikan respons sesuai
if jawaban.lower() == "tidak":
    print("Maaf, coba lagi.")
elif jawaban.lower() == "iya":
    print("Aku sudah menduganya.")
else:
    print("Jawaban tidak valid. Silakan jawab 'iya' atau 'tidak'.")
