# test_leo_richardsms.aleo

## Leo Code
```
program my_program_example.aleo {
    // The main function 'calculate_sum'.
    //
    // You can try this function by running:
    // leo run calculate_sum 3u32 4u32

    transition calculate_sum(param1: u32, param2: u32) -> u32 {
        return param1 + param2;
    }
}
```

## Leo Run
```
leo run calculate_sum 3u32 4u32
```