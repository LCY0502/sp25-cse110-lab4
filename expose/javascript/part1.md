1. "values added: 20"
2. "fianl result: 20"
3. Var do not have black-scoping which means the scope of the variable declared by var is visible anywhere within the function where it is delcared . 
4. "values added: 20"
5. Error, because using variable delcared by "let" is block-scoped, and the variable "result" is not declared outside the "if" block.
6. Error, because "const" do not allow reassign value.
7. Error, because "const" variable is also block-scoped and result is not defined outside the block.  