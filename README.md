# Access-Control-Project

This folder contains source code that explains about access control in Cadence Language.
Based on the provided Solidity-like pseudo-code:

### Variables:

- **a**: 
  - Read scope: Areas 1, 2, 3, and 4.
  - Write scope: Areas 1, 2, 3, and 4.

- **b**: 
  - Read scope: Areas 1, 2, 3, and 4.
  - Write scope: Area 1 only.

- **c**: 
  - Read scope: Areas 1, 2, and 3.
  - Write scope: Area 1 only.

- **d**: 
  - Read scope: Area 1 only.
  - Write scope: Area 1 only.

### Functions:

- **publicFunc**: 
  - Can be called in Areas 1, 2, 3, and 4.

- **contractFunc**: 
  - Can be called in Areas 1, 2, and 3.
  - Access is within the contract only.

- **privateFunc**: 
  - Can be called in Area 1 only.
  - Access is within the struct only.

### Function Call Locations:

- **structFunc**: 
  - Calls within the struct. Area 1.

- **resourceFunc**: 
  - Calls within the resource. Area 2.

- **createSomeResource**: 
  - Can be called from any area.

- **questsAreFun**: 
  - Can be called from any area.

### Initialization:

- **init**: 
  - Initializes variables `a`, `b`, `c`, and `d` with values "a", "b", "c", and "d" respectively.
  - Initializes `testStruct` with a new instance of `SomeStruct`.
  - Initializes `SomeResource` with a value of 17 for `e`.


## Author
https://github.com/Naman-Solanki

## License

This project is licensed under the [MIT License](LICENSE).
