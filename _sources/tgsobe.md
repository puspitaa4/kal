## Penyelesaian sistem persamaan linear

### Operasi Baris Elementer

### Eliminasi Gausss
##### Soal 1
$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3-x_2&=2
\end{array}
$$

#### Penyelesaian 
###### Dari sistem persamaan di rubah ke Matriks augmented:
$$
\begin{bmatrix}
1&2&3&|6\\
2&4&6&|12\\
0&1&1&|2
\end{bmatrix}
$$

###### Eliminasi
B2 → B2 - 2B1 untuk menghilangkan elemen di bawah elemen pivot pertama (kolom pertama):

$$
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
$$

###### Matriks setelah eliminasi
$$
\begin{bmatrix}
1&2&3&|6\\
0&1&1&|2
\end{bmatrix}
$$
###### Sistem ini memiliki tak hingga banyak solusi berbentuk ;

$$
(x_1,x_2,x_3)=(2-t,2-t,t), \quad t \in \mathbb{R}
$$


#### Soal 2
$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=8\\
x_1+2x_2&=3
\end{array}
$$
###### Bentuk Matriks Augmentasi
$$
\begin{bmatrix}
1&1&1&|3\\
2&0&1&|5\\
1&2&0&|3
\end{bmatrix}
$$

###### Eliminasi Gauss-Jordan
Pertama, nolkan elemen dibawah pivot

$$
\begin{bmatrix}
1&1&1&|3\\
0&-2&-1&|-1\\
0&1&-1&|0
\end{bmatrix}
$$





#### Soal 3
$$
\begin{array}{cc}
2x_1+2x_2&=4\\
x_1+x_2&=2
\end{array}
$$


#### Soal 4
$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
$$

#### Penyelesaian

Diberikan sistem persamaan:

\begin{aligned}
    x_1 + x_2 &= 5 \quad \text{(Persamaan 1)} \\
    x_1 + 2x_3 &= 6 \quad \text{(Persamaan 2)}
\end{aligned}


###### Dari sistem persamaan di rubah ke Matriks augmented:
Kita tulis dalam bentuk matriks:

\begin{bmatrix}
    1 & 1 & 0 & | 5 \\
    1 & 0 & 2 & | 6
\end{bmatrix}


###### Eliminasi

###### **1. Hilangkan elemen di bawah elemen pivot pertama** 
###### Gunakan b2= b2-b1 untuk menghilangkan elemen pertama di baris kedua:
\begin{bmatrix}
1&1&0&|5\\
0&-1&2&|1
\end{bmatrix}
###### normalisasi Pivot Kedua
Kita buat pivot kedua menjadi positif dengan mengalikan baris kedua dengan -1:

\begin{bmatrix}
1&1&0&|5\\
0&1&-2&|-1
\end{bmatrix}

###### Hilangkan Elemen di Atas Pivot Kedua
###### Hilangkan b1= b1-b2 untuk menghilangkan elemen di kolom kedua pada baris pertama:
\begin{bmatrix}
1&0&2&|6\\
0&1&-2&|-1
\end{bmatrix}
###### Dari sini, kita dapatkan persamaan:

$$
\begin{array}{cc}
x_1=2x_3&=6\\
x_2-2x_3&=-1
\end{array}
$$
##### Penyelesaian dengan Eliminasi Gauss
