Start

    Fungsi Fibonacci(n):
        jika n <= 1:
            kembalikan n
        kembalikan Fibonacci(n - 1) + Fibonacci(n - 2)
    Selesai

    Fungsi Utama:
        n: integer
        Tampilkan "Masukkan deret fibonacci: "
        Baca n

        Tampilkan "Deret Fibonacci hingga n adalah:"
        Untuk setiap i = 0 hingga n - 1, lakukan:
            Tampilkan Fibonacci(i)
        Ulangi
    Selesai
End
