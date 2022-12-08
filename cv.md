# Niyaz Amanshaiykov 

## Contact information: 
Phone: +7 778 388 952

Mail.ru: niyaz.amanshayykov@list.ru

E-mail: niyaz.amanshaiykov@gmail.com

Telegram: @ArchmagosDown

Discord: ArchmagosKain#4370

[VK](https://vk.com/adeptusmilfus)

[GitHub](https://github.com/AdeptusMilfus)

***
## General information about me:
I study at the university under the program engineering and telecommunications. Studied at the same time at the programming school Alem 01. Where I was able to improve my skills and add a couple of projects to my portfolio. Also, during my studies, I helped professors with their projects. The choice fell on me because of my sociability and ability to quickly join in work & team. 

I believe that by learning new things and developing my skills, I can succeed and become a top-notch front-end developer.
***
## Skills:
* Golang
* HTML, CSS Basics
* Git, GitHub, Gitea
* VS Code IDE
*** 

## Code example:
**Name**: Tabmult 

**Instructions**: Write a program that displays a number's multiplication table.
The parameter will always be a strictly positive number that fits in an int. Said number multiplied by 9 will also fit in an int.

Usage

$ go run . 9 

1 x 9 = 9 

2 x 9 = 18 

...

9 x 9 = 81


===
```
package main

import (
	"os"
	"strconv"

	"github.com/01-edu/z01"
)

func main() {
	if len(os.Args) != 2 {
		return
	}
	var num int
	arg, err := strconv.Atoi(os.Args[1])
	if err != nil {
		return
	}

	for i := 1; i <= 9; i++ {
		num = i * arg
		Println(Itoa(i) + " x " + Itoa(arg) + " = " + Itoa(num))
	}
}

func Itoa(n int) string {
	var ch string
	if n < 0 { // условие для отрицательных значений
		n = -n
		ch = "-"
	}
	digits := "0123456789"
	if n < 10 {
		return ch + digits[n:n+1]
	}
	return ch + Itoa(n/10) + digits[n%10:n%10+1]
}

func Println(s string) {
	for _, w := range s {
		z01.PrintRune(w)
	}
	z01.PrintRune('\n')
}
```
***
## My courses:
Bachelor at [KazATU](https://kazatu.edu.kz/)

[Alem01](https://alem.school/)

[w3school](https://www.w3schools.com/)
## projects:
1. [Ascii-Art-Web](https://github.com/AdeptusMilfus/Ascii-Art-Web/tree/main/ascii-art-web)
2. [Sudoku](https://github.com/AdeptusMilfus/Sudoku/tree/main/sudoku)
3. [Math-skills](https://github.com/AdeptusMilfus/Math-skills/tree/main/Math-skills)
4. [Go-reloaded](https://github.com/AdeptusMilfus/Go-reloaded/tree/main/Go-reloaded)
***
## Languages:
* English - Upper-intermediate/Advanced
* Russian - Advanced
* Kazakh - Native



