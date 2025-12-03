package main

import "fmt"

var srVozrast = 45 // создали переменную глобально, она видна везде

func main() {
	fmt.Println(z) // видна только в функции main
}

func main2() {
	fmt.Println(z) // не видна для этой функции 
}
