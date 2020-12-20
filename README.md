// Decimal-to-Hexadecimal-Conventer-C-
//Decimal to Hexadecimal conventer, C programming.
#include <stdio.h>
int main(int argc, char * argv[]){
    int answer, j=0, i=1;
    char ref;
    printf("|Decimal to Hexadecimal converter|");
        while(i>0?1:0){
            for(j=0; j<=0; ++j){
            printf("\nEnter Decimal number: ");
            scanf("%d", &answer);
            printf("\tDecimal entered: %d\n\tConverted into Hexadecimal: %x\n",answer,answer);}
            printf("Refresh? Y/n: ");
            scanf("%s", &ref);
                if(ref == 'Y'){
                    continue;
                }
                else if(ref == 'n'){
                    printf("Exitted.\n");
                    break;
                }
            }   
    return 0;
}
