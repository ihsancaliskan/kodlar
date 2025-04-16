#include <stdio.h>

int uslu(int x,int y){
    
    int result = 1;
    
    for(int i=0;i<y;i++){
        result = result * x;
    }
    return result;
    
}

int main (){

    int x,y;
    
    printf("x = ");
    scanf("%d",&x);
    printf("y = ");
    scanf("%d",&y);
    
    printf("Sonuç = %d",uslu(x,y));
    
    return 0;
}
