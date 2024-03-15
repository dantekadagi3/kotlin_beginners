

🔢 **Exploring Arithmetic Operators in Kotlin** 🔢

Arithmetic operators in Kotlin allow you to perform mathematical operations on variables. Here's a breakdown of the common arithmetic operators:

### 1. Addition `+`

```kotlin
var sum = x + y
```

- The `+` operator is used to add two numbers together.
- In the example, `x` and `y` are added together, and the result is stored in the variable `sum`.

### 2. Subtraction `-`

```kotlin
var difference = y - x
```

- The `-` operator subtracts the right operand from the left operand.
- Here, `x` is subtracted from `y`, and the result is stored in the variable `difference`.

### 3. Multiplication `*`

```kotlin
var product = x * y
```

- The `*` operator multiplies two numbers.
- It takes two operands (numbers) and returns their product.

### 4. Division `/`

```kotlin
var quotient = z / x
```

- The `/` operator divides the left operand by the right operand.
- In this example, `z` is divided by `x`, and the result is stored in the variable `quotient`.

### 5. Remainder (Modulus) `%`

```kotlin
var remainder = z % x
```

- The `%` operator gives the remainder of the division operation.
- It returns the remainder when the left operand is divided by the right operand.
  

code example
fun main() {
    var x = 3
    var y = 4
    var z = 5

    println("The value of x is: $x")
    println("The value of y is: $y")
    println("The value of z is: $z")

    // Addition
    var sum = x + y
    println("The sum of x and y is: $sum")

    // Subtraction
    var difference = y - x
    println("The difference of y and x is: $difference")

    // Multiplication
    var product = x * y
    println("The product of x and y is: $product")

    // Division
    var quotient = z / x
    println("The quotient of z and x is: $quotient")

    // Remainder (Modulus)
    var remainder = z % x
    println("The remainder of z divided by x is: $remainder")
}
The value of x is: 3
The value of y is: 4
The value of z is: 5
The sum of x and y is: 7
The difference of y and x is: 1
The product of x and y is: 12
The quotient of z and x is: 1
The remainder of z divided by x is: 2



### Additional Information:

- **Order of Operations**: Just like in mathematics, Kotlin follows the order of operations (PEMDAS/BODMAS) when evaluating expressions.
- **Increment and Decrement**: Kotlin also supports `++` (increment) and `--` (decrement) operators to increase or decrease the value of a variable by 1.

### Example Usage:

```kotlin
var result = (x + y) * z / 2
```

- This expression calculates a result by adding `x` and `y`, multiplying the sum by `z`, and then dividing the result by 2.

---

 Happy coding! 🌟
