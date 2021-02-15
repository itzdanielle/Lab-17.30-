# Lab-17.30-
#include <iostream>
#include <cmath>
using namespace std;


void square (float num) {
  double result;
  result = (num * num);
  cout << "The square is: " << result << endl;
  return;
}

int main() {
  double num;
  cout << "Enter a number to square:" << endl;
  cin >> num;
  square (num);
}
