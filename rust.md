# **Rust**


## **Rustup**

### Create new project:
```bash
cargo new {Project Name}
```

### Compile & Run in one command:
```bash
cargo run
cargo run --quiet or -q
```

### Run Test
```bash
cargo test
```

### Output STDOUT & STDERR to file
```bash
cargo run 1>out 2>err
echo $? #echo exit value
```

### println!
```rust
// {:#?} is debug 
println!("{:#?}", matches);
```