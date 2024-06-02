<!-- Directory Structure -->
<details open>
<summary><h2>Directory Structure</summary>

<pre>
my_move_package

|____ Move.lock
|____ Move.toml
|____ sources
  |____ my_module.move

</pre>

```move
/* my_module.move */

module named_address::my_first_module {
    /* logic here */
}
```

</details>


<!-- Move Module Syntax -->
<details>
<summary><h2>Module - Syntax</summary>
  
```move
module <address>::<identifier> {
  (<use> <friend> <type> <function> <constant>) *
}
```

where <kbd>module</kbd> is a builtin keyword, <kbd>&lt;address&gt;</kbd> is a valid named or literal
address, <kbd>identifier</kbd> is the module name.
</details>


<details>
<summary><h2>Data Types</summary>

+ ### Unsigned Integer
    + **u8, u16, u32, u64, u128, u256**
    + no signed integer
    + type casting between integers
        + ```(x as u8)```
        + ```(y as u16)```
        + ```(some_numberu16 as u32)```

+ ### Address
    + Used to represent locations (sometimes called accounts) in storage.
    + A 256-bit (32 byte) identifier in Sui Move (different from Move's 16-byte addresses

</details>

<details>
<summary></summary>
</details>

<details>
<summary></summary>
</details>

<details>
<summary></summary>
</details>

<details>
<summary></summary>
</details>

<details>
<summary></summary>
</details>
