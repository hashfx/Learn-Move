<!-- [PlayList](https://www.youtube.com/playlist?list=PL3id4Z64z2sNED_aH7UYIFFwy6MsvKCN9) -->
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
    + 16-byte address (A 256-bit (32 byte) identifier in Sui Move )
 
+ ### Vector
    + ```Vector<T>``` is the only primitive collection type provided by Move

+ ### Type Abilities (4):
    + **Copy:** value can be copied (or cloned by value)
    + **Drop** value can be dropped by the end of scope
    + **Key:** value can be used as a key for global storage operations
    + **Store:** value can be stored inside global storage

</details>

<details>
<summary><h2>Functions</summary>

Move functions have three types of visibility:
  + private(default)
  + public
  + public(friend)
  
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
