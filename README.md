# Java Essential

Java merupakan bahasa pemrograman yang menggunakan paradigma Object Oriented Programming atau yang sering disebut OOP.

## Java Basic
- [Name Convention]()
- [Hello World!]()
- [Variable & Data Type (variabel & tipe data)]()
- [Operation (operator)]()
- [Conditional (pengkodisian)]()
- [Looping (perulangan)]()
- [Keyword this, super, final]()
- [Method (fungsi)]()

## Java Object Oriented Programming

- [Class & Object]()
- [Inheritance]()
- [Polymorphism]()
- [Encapsulation]()

## Statement

## Name Convention


Method main

```java
public static void main(){}
```

Contoh

```java
class TestingHello{
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

Output :

```bash
Hello World!
```

- **``println()``** : fungsi **``println()``** merupakan fungsi bawaan dari Java yang berguna untuk mencetak karakter pada layar.
- **``main()``** : method/fungsi main() merupakan suatu fungsi untuk mengeksekusi program pertama kali yang akan diproses dan akan ditampilkan kepada user.

## Variabel

Fungsi dari variabel adalah untuk menyimpan suatu nilai pada memory.

### Implementasi Variabel

### Ruang Lingkup Variabel

- Local Variable
- Instance Variable
- Static Varible atau Class Variable

### Contoh Local Variable
### Contoh Instance Variable
### Contoh Static Variable

## Tipe Data

### Tipe data primitif

### Tipe data dari Java


## Operators

Tipe operator yang dapat dilakukan dibahasa pemrograman Java

- Unary Operator
- Arithmetic Operator (Operator Aritmatika)
- Shift Operator
- Relational Operator
- Bitwise Operator
- Logical Operator
- Ternary Operator
- Assigment Operator

### Unary Operator

### Increment & Decrement

**Prefix**

Nilai suatu variable bertambah dan akan digunakan sebagai nilai baru pada ekspresi. Simbol yang digunakan oleh prefix adalah ``++<nama_variabel>``.

Contoh : 

```java
int x = 20;
int y = ++x;
```

Output :

```bash
21
```

**Postfix**

Nilai varibel yang pertama kali digunakan didalam ekspresi kemudian nilai akan bertambah , namun tidak tampil pada ekspresi. Simbol yang digunakan oleh prefix adalah ``<nama_variabel>++``.

 ```java
int x = 20;
int y = x++;
```

Output :

```bash
20
```


## Reference

1. [Javatpoint.com](https://www.javatpoint.com)
2. [Sololearn Java](https://www.sololearn.com/Play/Java)