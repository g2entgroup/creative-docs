---
description: >-
  When creating a new smart contract project, use the guidelines below to ensure
  your project meets our basic standards of quality.
---

# 📐 Smart Contract Guidelines

## Security <a id="security"></a>

### Re-entrancy

Any external or public functions need to be analyzed to determine whether the contract can be attacked if a user re-enters that function or another.

### Safe ERC20 Usage

ERC20 token interactions should always use SafeERC20 safeApprove and safeTransferFrom in the OpenZeppelin library.

### Math Overflow and Underflow <a id="math-overflow-and-underflow"></a>

Any math operations need to be checked for overflow and underflow conditions, using SafeMath or similar.

### Trusted External Calls <a id="trusted-external-calls"></a>

The contract should minimize trust in external calls.

## Conventions <a id="conventions"></a>

### Typed Arguments

All arguments, whether to an event or function, must be typed when possible. `address` types should be avoided in favor of contract or interface types

### Logs Emitted <a id="logs-emitted"></a>

Events must be emitted for any significant state change or event.

### Grammar <a id="grammar"></a>

Names and documentation must be spelled correctly with no grammatical errors.

## Documentation <a id="documentation"></a>

### ReadMe

A complete readme must be included with the project. It needs:

* a complete description
* usage
* setup instructions
* all test commands
* deployment instructions and information
* information on any additional scripts

### Natspec <a id="natspec"></a>

Contracts must have \(at minimum\):

* `@title`: short title. shouldn't repeat the description
* `@notice`: descriptive enough so that the reader understands the intent of the contract.

Functions must have \(at minimum\):

* `@notice`: explain what the function does
* `@param`: explain each parameter
* `@return`: explain the return param\(s\)

Events must have \(at minimum\):

* `@notice`: describe when the event is emitted
* `@param`: describe each of the args

## Testing <a id="testing"></a>

### Code Coverage

* Coverage must exceed 95%
* A coverage tag must be included in the README

### Unit Tests <a id="unit-tests"></a>

* There must be a test suite for each contract
* Functions should be tested in isolation as much as possible
* Unit tests must run **locally; i.e. they do not connect to a remote node.**

### Fork Test <a id="fork-test"></a>

* A fork test script tests the contracts in the real world

## Optimizations <a id="optimizations"></a>

* All external / public functions should return a value when possible \(to save gas\)
* Structs must be tightly packed
* Values that don't change should be constants

