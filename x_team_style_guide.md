# X-Team 04 Style Guide

Keep it clean. Keep it consise. Comment for confusion

## Naming conventions

- Keep it short
- Obvious abbriviations when possible
- static final variables all caps w/ underscores
- Cammel Casing on variables and methods
- Title Casing on classes, interfaces

### Examples
* interfaces: 
  * SearchTreeADT
* classes: 
  * Node
* exception types: 
  * DuplicateKeyException
* fields: 
  * Scanner scnr
* methods: 
  * rotateL(Node<T> n)
* parameters: 
  * (int index, Node<T> node)
* local variables
  * int i // index
* instance constants
  * public final int INDEX
* class constants
  * public static final int MAX_NUMBER_OF_NODES

## Commenting style for public and private members of a class or interface:

Documentation comments (/\*\*) for classes and methods

Inline comments are fine. (Use //)

### Examples

* classes
  * /\*\*Cool Comment about the Class here\*/
* fields
  * // Insert Comment Here
* constructors
  * Same as methods
* methods
  * Same as classes
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements: Don't care
  * switch statement: Don't care
  * while loops: Don't care
  * for loops: Don't care
  * enhanced for loops: Don't care
