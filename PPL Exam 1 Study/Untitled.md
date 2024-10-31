# Haskell Practice Questions

## Expressions and Types

1. What is the result of `x01 = 1+2`?

<details>
<summary>Solution</summary>

3

The expression simply adds 1 and 2.
</details>

2. What is the type of `t02 = (+)`?

<details>
<summary>Solution</summary>

`Num a => a -> a -> a`

This is the type signature of the addition function. It takes two numbers of the same type and returns a number of that type.
</details>

3. How does `x04 = flip (-) 1 2` differ from `x03 = (-) 1 2`?

<details>
<summary>Solution</summary>

`x04` evaluates to 1, while `x03` evaluates to -1.

`flip` reverses the order of arguments, so `flip (-) 1 2` is equivalent to `2 - 1`.
</details>

4. What does `x05 = 1 : []` create?

<details>
<summary>Solution</summary>

`[1]`

This expression creates a list with a single element, 1.
</details>

5. What is the type of `t08 = []`?

<details>
<summary>Solution</summary>

`[a]`

This is an empty list that can contain elements of any type.
</details>

6. Evaluate `x11 = [1, 2] ++ [3, 4]`.

<details>
<summary>Solution</summary>

`[1,2,3,4]`

The `++` operator concatenates two lists.
</details>

7. What is the result of `x14 = foldr (-) 0 [1, 2, 3]`?

<details>
<summary>Solution</summary>

2

This is equivalent to `1 - (2 - (3 - 0))`, which equals 2.
</details>

8. Compare the results of `x14` and `x16`. Why are they different?

<details>
<summary>Solution</summary>

`x14 = foldr (-) 0 [1, 2