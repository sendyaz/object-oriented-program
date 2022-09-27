# Object-Oriented-Program

<div style="background-color: whitesmoke; padding: 10px ">
    <p><strong>Tujuan:</strong></p>
    <ul>
        <li>Memperkenalkan Sistem Object dan Class pada bahasa pemrograman python</li>
    </ul>
    <p><strong>Keluaran:</strong></p>
    <ul>
        <li>Praktikan dapat memahami cara kerja object dan class</li>
    </ul>
    

#### TUGAS OOP 1: Buat Kelas dengan atribut instance

Tulis program Python untuk membuat kelas apapun dengan atribut instance-nya. 


#### TUGAS OOP 2: Parent and Child

Buatlah sebuah kelas yang akan menjadi *Parrent class* yang akan menurunkan variable ke *Child class*nya 


#### TUGAS OOP 3: Class Inheritance

Diberikan:
Buat kelas Bus yang mewarisi dari kelas Kendaraan. Berikan argumen kapasitas Bus.seating_capacity() nilai default 50.

Gunakan kode berikut untuk kelas Kendaraan induk Anda:

```python3
class Vehicle:
    def __init__(self, name, max_speed, mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage

    def seating_capacity(self, capacity):
        return f"The seating capacity of a {self.name} is {capacity} passengers"

```

Output yang harusnya keluar:

The seating capacity of a bus is 50 passengers
