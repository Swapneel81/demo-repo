#include <iostream>

int getMax(int numbers[], int size){
  int max = numbers[0];
  for(int i = 1; i < size; i++){
      if(numbers[i] > max){
        max = numbers[i];
      }
  }
  return max;
}

int main(){

int numbers[5] = {5, 4, -2, 29, 8};
std::cout << "Max number is - " << getMax(numbers, 5);

return 0;
}
