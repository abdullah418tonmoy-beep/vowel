#include<stdio.h>
int main()
{
    char c;

    printf("Enter your character to define vowel: ");
    scanf(" %c", &c);

    if(c=='a' || c=='e' || c=='i' || c=='o' || c=='u' ||
       c=='A' || c=='E' || c=='I' || c=='O' || c=='U')
    {
        printf("The character is VOWEL: %c\n\n", c);
    }
    else
    {
        printf("The character is CONSONANT: %\n", c);
    }

    // ASCII value
    printf("The ASCII value of your character is: %d\n", c);

    return 0;
}

