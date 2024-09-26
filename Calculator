#include<stdio.h>
#include<math.h>

int main(){
    
    // primitive data types
    char character, operator;
    int a, b;
    float pi = 3.142;
    
    printf("##### CALCULATOR #####\n\n**** READ THE INSTRUCTIONS BELOW ***\n\n1.Press '+' for addition\n2.Press '-' for subtraction\n3. Press '*' for multiplication\n4.Press '/' for division 5.Press '%' for division\n6.Press 'r' for square root of number\n7.Press 'p' for exponent\n8.Press 's' to take sin function\n9.Press 'c' to take cos funtion\n10. Press 't' to take tan function\n");

    // s to start
    printf("Press S to Start: ");
    scanf(" %c",&character);

    if ((character == 'S')||(character == 's'))
    {        
        printf("Enter an operator");
        scanf(" %c",&operator);

// switch
        switch (operator)
        {

        case '+':
            printf("Enter 2 digits: ");
            scanf("%d %d",&a, &b);
            printf("Result = %d",a + b);
            break;

        case '-':
            printf("Enter 2 digits: ");
            scanf("%d %d",&a, &b);
            printf("Result = %d",a - b);
            break;

        case '%':
            printf("Enter 2 digits: ");
            scanf("%d %d",&a, &b);
            printf("Result = %d",a % b);
            break;

        case '*':
            printf("Enter 2 digits: ");
            scanf("%d %d",&a, &b);
            printf("Result = %d",a * b);    
            break;

        case '/':
            printf("Enter 2 digits: ");
            scanf("%d %d",&a, &b);
            printf("Result = %d",a / b);

            if (b == 0){
                printf("Division Error");
            } else if (a == 0 && b == 0){
                printf("Infinity");
            }
            break;

        case 'r':    
            printf("Enter a number: ");
            scanf("%d",&a);
            printf("Result = %f",sqrt(a));
            break;

        case 'p':  
            printf("Enter a number: ");
            scanf("%d", &a);
            printf("Enter index: ");
            scanf("%d",&b);
            printf("Result = %f",pow (a, b));
            break;

        case 's':
            printf("Enter a number: ");
            scanf("%d",&a);
            printf("Result = %f",sin(a));
            break;

        case 'c':
            printf("Enter a number: ");
            scanf("%d",&a);    
            printf("Result = %f",cos(a));
            break;

        case 't':
            printf("Enter a number: ");
            scanf("%d",&a);
            printf("Result = %f",tan(a));
            break;

        default:
        printf("Invalid operator");
            break;
        }
    } else printf("Thank You");
    
    return 0;
}
