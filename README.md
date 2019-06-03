SINGLE PAGE APPLICATIONS
1. Only one html page is served by server and then everything is managed by Javascript
2. You never have to go back to server
3. Controlled by one React component which has other components in it
4. For above, we use only one REACTDOM.render() -> root component

MULTI PAGE APPLICATIONS
1. Multiple pages are called with routes to server

REACT
1. Javascript library
2. Uses JSX (means HTML inside Javascript function)
3. Props - contained attributes to add into component
4. Angular and Vue are also best alternatives

React -  https://reactjs.org/

-------------------------------------------------------------------------------------
ES6
1. Use of let(variable values) and const(constants)
2. Arrow function
    const myName = (name) => {

    }
    if one arugment, you can remove braces around name
    const multiply = (number) =>{
        return number * 2;
    }
    if only one return, then write as const multiply = (number) => number * 2;
3. Exports and Imports(Modular code)
    const person = {
        name : 'Hari'
    }
    export default person
    The above imported as import person from './person' or import per from './person'
    export const clean = () => {}
    import as, import {clean} from ''; (Named export)
    or import { clean as cln } from '';
    or import * as cln from '';
4. Classes - variables(Properties) and functions(Methods)
    OLDER 
    Properties are added inside constructor
    class Person{
        constructor(){
            this.name = 'Hari';
        }
        printMyName(){
            console.log(this.name);
        }
    }
    const person = new Person();
    person.printMyName();
    NEWER - ES7
    No use of constructor and this keyword for Properties
5. Spread and Rest ( ... )
    i. Spread - split up array elems or object Properties
        const newArray = [...oldArray,1,2];
        const newObject = { ...oldObject, newProp:5 };
    ii. Rest - merge list of function arguments into an array
        function sortArgs(..args){
            return args.sort();
        }
6. Destructuring - extract array elements or object properties
    ARRAY
    const numbers = [1,2,3];
    [num1,num2] = numbers;
    console.log(num1,num2) // 1 2
  ------------------------------------------------------------------------  
