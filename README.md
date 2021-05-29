# Function_Parameters_Triangle
C++ Program

    #include <iostream>
    using namespace std;
    void DrawBar(int);
    void Shape(int);
    int main() {
    int length = 4;
    Shape(length);
    }
    void Shape(int length){
      for(int i = 0; i <= length; i++){
      DrawBar(i);
      cout << endl; 
      }
    }
    void DrawBar(int length){
      for(int i = 0; i < length; i++){
      cout << "*"; 
      }
    }
