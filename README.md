# HelloWorlds
Github asked me to create a hello-world repository, but instead of just doing that I decided that I could add in the iconic time-honored tradition of printing out the words "Hello World" in the many different programming languages that are out there today.

## *Java*

public class HelloWorld {

    public static void main(String[] args) {
    
        System.out.println("Hello World");
        
    }
}


## *C*

#include<stdio.h>

main()
{

    printf("Hello World");
    
}


## *C++*

#include <iostream>
using namespace std;

int main() 
{

    cout << "Hello World!";
    return 0;
    
}

## *Python*

print("Hello World")







## *C#*

public class Hello1
{
   public static void Main()
   {
     
     System.Console.WriteLine("Hello World!");
     
   }
}

## *Visual Basic .NET*

Imports System
Public Module modmain
   
   Sub Main()
     
     Console.WriteLine ("Hello World")
   
   End Sub

End Module


## *Javascript*

<!DOCTYPE HTML>

<html>

<body>
  
  <script>
    
    alert( 'Hello World!' );
  
  </script>

</body>

</html>

## *PHP*

<html>
 
 <body>
 
 <?php echo '<p>Hello World</p>'; ?> 
 
 </body>

</html>



## *Perl*

  use strict;
  use warnings;

  print "Hello World!\n";
  
  
  
  
## *Ruby*

class HelloWorld
   
   def initialize(name)
      
      @name = name.capitalize
   
   end
   
   def sayHi
      
      puts "Hello #{@name}!"
   
   end

end

hello = HelloWorld.new("World")

hello.sayHi

## *Swift*

print("Hello World")






## *R*

 myString <- "Hello World!"
 
 print (myString)
 
 
 
 
 
 ## *Go*
 
package main

import "fmt"

func main() {
    
    fmt.Println("hello world")
}



## *Objective-C*

#import <Foundation/Foundation.h>

int main (int argc, const char * argv[])
{
        
        NSAutoreleasePool *pool = [[NSAutoreleasePool alloc] init];
        
        NSLog (@"Hello, World!");
        
        [pool drain];
        
        return 0;
}
