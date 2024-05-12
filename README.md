# CForBeginners
##All from youtube video C Programming for Beginners by Giraffe Acadamy

#include <stdio.h>
#include <stdlib.h>

###all examples from youtube video C Programming Tutorial for Beginners

//making a shape
int main()
{
    printf("   /|\n");
    printf("  / |\n");
    printf(" /  |\n");
    printf("/___|\n");
}


//changing multiple variables at once:
int main()
{
    //make variables to hold the information
    char characterName[] = "John";
    int characterAge = 35;

    //%s is for strings and %d is for integers
    printf("There was once a man named %s.\n", characterName);
    printf("He was %d years old.\n", characterAge);
    
    //you can change the variables value at any place in the code
    characterAge = 30;
    printf("He really liked the name %s.\n", characterName);
    printf("But he did not like being %d.\n", characterAge);
}

int main()
{
   //numbers are stored in data type integer or decimal
   //decimal has to have a decimal point associated with it
   int age = 40;
   double gpa = 3.7
   
   //letters are stored in data type character
   //use single quotes
   char grade = 'A';
   
   //modification of character data type (a string of characters)
   //use double quotes
   char phrase[] = "Phrase"
   //the open and closed square brackets makes the string of characters
   
}

int main()
{
    //using printf
    //printf is a function
    //can use any characters inside quotation marks
    printf("Hello World");
    // \n creates a new line
    //use a format specifier to print out data
    printf("My favorite %s is %d", "number", 500);
    //use %f for a decimal and %c for characters
} 

int main()
{
    //pow(2, 3) gives 2^3
    //sprt does squreroot
    //ceil rounds the number up
    //floor will round the number down
    printf("%f", pow(2, 3));
    
}

int main()
{
    //constants are variables that cannot be modified
    //best practice is to name constants in all cap letters
    const int num = 5;
    printf("%d" , num);
    num = 8; //will throw an error because it cannot be changed
    printf("%d", num);
    
}
