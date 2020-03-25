# corona-programming-language
A hypothetical programming language (just for fun). Due to lack of time, I haven't wrote any interpreter or compile.

## Hello world

````corona
@import system;

@func main({args: String}) : Void {
  print("Hello world");
}
````

## Classes

````corona
  @import system;
  @class Hello :extends Object {
    @constructor({str: String}) {
      this.str = str;
    }
    world() : Void {
    
    }
  }
  
  @func main({args: String}) {
    @let hello = new Hello(str);
    hello.world();
  }
````
