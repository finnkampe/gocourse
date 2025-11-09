package main

import "fmt"

func main() {
	var a, b int = 10, 3
	var result int
	result = a + b
	fmt.Println("Addition:", result)
	result = a - b
	fmt.Println("Subtraction:", result)
	result = a * b
	fmt.Println("Multication:", result)
	result = a / b
	fmt.Println("Division:", result)
	result = a % b
	fmt.Println("Remainder:", result)

}
