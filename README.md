# Your-weight-on-different-planets-calculator
This is my second projects so feel free to suggest edits if anything wrong or can be optimized.

#include <iostream>
int main() {
  
  double mweight;
  double weight;
  int xy;
  
  std::cout << "Weight on earth.";
  
  std::cin >> weight;
  
  std::cout << "What planet to do you wanna see your weight on?\n";
 
  std::cout << "1=Venus 2=Mars 3=Jupiter 4=Saturn 5=Uranus 6=Neptune 7=Mercury\n";
  
  std::cin >> xy;
 
  switch(xy){
  case 1:
  mweight = weight*.91;
   std::cout << "Your weight on Venus is " << mweight <<" pounds.\n";
  break;
  case 2:
  mweight = weight*.38;
   std::cout << "Your weight on Mars is " << mweight <<" pounds.\n";
  break;
  case 3:
  mweight = weight*2.34;
   std::cout << "Your weight on Juptier is " << mweight <<" pounds.\n";
  break;
  case 4:
  mweight = weight*1.06;
  std::cout << "Your weight on Saturn is " << mweight <<" pounds.\n";
  break;
  case 5:
  mweight = weight*.92;
  std::cout << "Your weight on Uranus is " << mweight <<" pounds.\n";
  break;
  case 6:
  mweight = weight*1.19;
 std::cout << "Your weight on Neptune is " << mweight <<" pounds.\n";
  break;
  case 7:
  mweight = weight*.38;
  std::cout << "Your weight on Mercury is " << mweight <<" pounds.\n";
  break;
  default:
  std::cout << "invalid\n";
  break;
}
}
