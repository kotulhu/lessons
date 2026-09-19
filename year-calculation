#include <iostream>

int main(){
    int papa = 1990;
    int mama = 2000;
    int hijo = 2024;
    int curyear = 2026;
    
    int sumn;
    int targetyear;
    
    int target;
    std::cout<<"Input sumn: ";
    std::cin>>target;
    
    targetyear = curyear;
    
    do{
        sumn = (targetyear - papa) + (targetyear - mama) + (targetyear - hijo);

        if (sumn == target){
            std::cout<<targetyear;
            break;
        }
        targetyear++;
    }while (sumn < target && targetyear < curyear + 500);
    
    if (sumn != target){
        std::cout<<"Year wasn't found";
    }
    return 0;
}
