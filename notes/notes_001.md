Types - tells the compiler or the runtime a plan for your memory layout
    - built in type - e.g. double, int, string
        - lots of these
        - these may or may not have other capabilities 
            - what does it mean to have a capability / feature / functionality?
                - remember string.length() - something a type can do
    - user defined type - something like a structure (struct) or an class that you define
        - defines (NOT DECLARE) a memory layout 
        - may or may not define capabilities associated with the memory layout 
            - what does it mean to have a "capability?"
                - for user defined classes, you can also define your own capabilites 
                    - in a class, we refer to capabilites as 'methods' 
    
    * defining classes and structures are ways for the coder to create a "type" 

    - struct vs class
        - generally you can use these terms interchangably
            - example in c++ -> members are private by default in class, but not in structs
        - have subtle differences based on your language 

Operand
    - an instance of type that is 'operated on'
    - can be a built in type or a user defined type 
Operators
    - operates on the operand 
    - when you have a Type, you will need to perform operations on it
        - eg int + int - in this case the '+' symbol 
    - operators have prescidence
    - https://www.tutorialspoint.com/cprogramming/c_operators.htm

    - MEMORIZE - Arithmetic, Relational, Logical, Assignment
    - learn general prescidence 
        1 + 2 * 3 
    - may or may not be able to operate on different types of operands 

    - cast 
        - could be considered a type of operator 
        - convert or view a type as though it is a different type 

        - in ANSI C, a cast to integer looks like ...
            (int)242.32; 

            std::static_cast<int>(242.32);


