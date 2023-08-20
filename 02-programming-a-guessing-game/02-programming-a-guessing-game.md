# Programming a Guessing Game

we included the input/output functionality from the standard library with use `std::io`;

To obtain user input and then print the result as output, we need to bring the `io` input/output library into scope. The `io` library comes from the standard library, known as `std`

## Storing Values with Variables

```rust
// variable to store the user input
let mut guess = String::new()
// The :: syntax in the ::new line indicates that new is an associated function of the String type

// let statement to create the variable
let apples = 5;

let orange = 5; // immutable
let mut bananas = 5; // mutable
```

## Receiving User Input

call the stdin function from the io module, which will allow us to handle user input:

```rust
io::stdin().read_line(&mut guess)
```

The `&` indicates that this argument is a **reference**, which gives you a way to let multiple parts of your code access one piece of data without needing to copy that data into memory multiple times.

## Handling Potential Failure with Result
