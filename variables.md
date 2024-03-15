

---

🌟 **Learning Variable Declaration in Kotlin** 🌟

Welcome to the world of Kotlin! Let's dive into the basics of variable declaration in Kotlin. In Kotlin, declaring variables is easy and flexible. Here's a breakdown using some simple examples:

### 1. Declaring Variables

```kotlin
var age: Int = 20
```

- In Kotlin, you can declare a variable using the `var` keyword followed by the variable name.
- You can optionally specify the variable's data type after a colon (`:`). If you don't specify the type, Kotlin will infer it from the value assigned.
- Here, we're declaring a variable named `age` of type `Int` and initializing it with the value `20`.

### 2. Using `val` for Immutable Variables

```kotlin
val favouriteNumber = "seven"
```

- In Kotlin, if you want a variable whose value cannot be changed (immutable), you use the `val` keyword instead of `var`.
- Here, `favouriteNumber` is declared as a `val`, meaning its value cannot be reassigned once it's initialized.
- Kotlin will still infer the type if you don't specify it explicitly.

### 3. Printing Variable Values

```kotlin
println("My name age is: $age and my favourite number is: $favouriteNumber")
```

- You can print variable values using `println`.
- To include variables within a string, you can use string templates. Place the variable name within `${}` to include its value in the string.

### Additional Information:

- **Type Inference**: Kotlin supports type inference, meaning you often don't need to explicitly specify the data type of a variable as the compiler can figure it out from the context.
- **Mutable vs. Immutable**: Use `var` for mutable variables (whose values can change) and `val` for immutable variables (whose values remain constant).

---

