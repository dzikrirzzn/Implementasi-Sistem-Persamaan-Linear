# Implementasi-Sistem-Persamaan-Linear

1. Metode Matriks Balikan:
Metode ini melibatkan menghitung matriks balikan dari matriks koefisien sistem persamaan linear dan kemudian mengalikannya dengan vektor hasil. Jika matriks balikan dapat dihitung, solusi sistem persamaan linear dapat ditemukan dengan mudah.

2. Metode Dekomposisi LU Gauss:
Metode ini melibatkan dekomposisi matriks koefisien sistem persamaan linear menjadi dua matriks segitiga, yaitu matriks bawah (L) dan matriks atas (U), menggunakan metode eliminasi Gauss. Setelah mendapatkan dekomposisi LU, solusi sistem persamaan linear dapat ditemukan dengan mengalikan vektor hasil dengan matriks balikan dari matriks segitiga bawah dan matriks segitiga atas.

3. Metode Dekomposisi Crout:
Metode ini juga melibatkan dekomposisi matriks koefisien sistem persamaan linear menjadi dua matriks segitiga, yaitu matriks bawah (L) dan matriks atas (U), tetapi dengan pendekatan Crout. Solusi sistem persamaan linear kemudian ditemukan dengan mengalikan vektor hasil dengan matriks balikan dari matriks segitiga bawah dan matriks segitiga atas.

source code yang diberikan merupakan implementasi dari metode metode diatas dengan menggunakan library numpy
