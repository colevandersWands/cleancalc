# Documentation for __cleanCalc__ 

## New version: 2.0.0

* calc: object
    * properties: 1
        * lastResult: number
            * initialized: 0000
            * pupose: to allow chained operations
    * methods: 5
        * operate: function
            * args: 3
                * operation: string
                    * purpose: designates which method to call
                * arg1: number
                    * purpose: required operand
                * arg2: number
                    * purpose: optional operand
            * return: number
            * behavior: calls the right method with arg1 and arg2 OR * * * lastResult
            * purpose: allows users to access math methods from a single interface

        * add: function
            * args: 2
                * arg1, arg2: number
                    * purpose: math need numbers
            * return: number
            * behavior: adds arg1 to arg2 and returns the sum
            * purpose: so users can add

        * subtract: function
            * args: 2
                * arg1, arg2: number
                    * purpose: math need numbers
            * return: number
            * behavior: sutracts arg1 to arg2 and returns the result
            * purpose: so users can subtract

        * multiply: function
            * args: 2
                * arg1, arg2: number
                    * purpose: math need numbers
            * return: number
            * behavior: multiplies arg1 to arg2 and returns the result
            * purpose: so users can multiply

        * divide: function
            * args: 2
                * arg1, arg2: number
                    * purpose: math need numbers
            * return: number
            * behavior: divides arg1 to arg2 and returns the result
            * purpose: so users can divide
    * purpose: use to store actions you can perform with arguments for cleancalc 
