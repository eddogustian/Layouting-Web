#Layouting with Table HTML 

Colspan dan rowspan adalah html attribute yang digunakan untuk memperbesar atau menggabungkan beberapa kolom atau row menjadi satu, sehingga satu unit kolom atau row ini menjadi lebih besar.

1. Colspan adalah pendekatan dari "Column span" yang berarti sebagai "berapa kotak kesamping"

2. Rowspan mengartikan "berapa kotak kebawah"

attribute colspan diletakan dalam tag <td> dan kamu bisa ngatru "value" atau nilai nya berapa kotak yang akan di span. berikut contohnya :

<table border="1">
    <tr>
        <td colspan="5"><center>Gabungan kotak 1-5</center></td>
    </tr>
    <tr>
        <td>kotak 1</td>
        <td>kotak 2</td>
        <td>kotak 3</td>
        <td>kotak 4</td>
        <td>kotak 5</td>
    </tr>
</table>

note:
Dengan mengatur colspan menjadi "5", kotak di baris pertama akan menjadi gabungan dari 5 kolom.

Bagaimana dengan rowspan?
Rowspan tugasnya untuk menyatukan kotak-kotak row kebawah sehingga menjadi satu unit yang panjang. contohnya seperti ini:

<table border="1">
    <tr>
        <td rowspan="5">Kotak 1-5</td>
        <td>Kotak 1</td>
    </tr>
    <tr>
        <td>Kotak 2</td>
    </tr>
    <tr>
        <td>Kotak 3</td>
    </tr>
    <tr>
        <td>Kotak 4</td>
    </tr>
    <tr>
        <td>Kotak 5</td>
    </tr>
</table>
