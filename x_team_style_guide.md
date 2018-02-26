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
  * if statements: Personal preference (Most in group prefer using horizontal space)
  * eg: if(args) {
  *  \*insert code here\*
  * }
  * switch statement: Personal preference (See if statements)
  * eg: switch(arg) {
  *  \*insert code here\*
  * }
  * while loops: Personal preference (See if statements)
  * eg: while(args) {
  *  \*insert code here\*
  * }
  * for loops: Personal preference (See if statements)
  * eg: for(args) {
  *  \*insert code here\*
  * }
  * enhanced for loops: Personal perference (See if statements)
  * eg: for(int i : intArray) {
  *  \*insert code here\*
  * }
