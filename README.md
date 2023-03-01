# CalculadoraBasica
Proyecto de calculadora

#include<iostream>
using namespace std;

int main{

int a,b,suma, resul,multi,opc;
float div;

cout<<"Bienvenidos a nuestra calculadora";
cout<<"selecciona opcion de operacion";
cin>>opc;

switch(opc){
    Case 1:
      cout<<"Ingresa primer numero";
      cin>>a;
      cout<<"Ingresa segundo numero";
      cin>>b;
      suma=a+b;
      cout<<"El resultado es: ";
      cout<<suma;
    Breack;
    
    Case 2:
      cout<<"Ingresa primer numero";
      cin>>c;
      cout<<"Ingresa segundo numero";
      cin>>d;
      res=c-d;
      cout<<res;
    Breack;
  
    Case 3:
      cout<<"Ingresa el primer numero";
      cin>>a;
      cout<<"Ingresa el segundo numero";
      cin>>b;
      multi=a*b;
      cout<<"El resultado es: ";
      cout<<multi;
     Breack;
     
     Case 4:
      cout<<"Ingresa el primer numero";
      cin>>a;
      cout<<"Ingresa el segundo numero";
      cin>>b;
      resul=a/b;
      cout<<"El resultado es:">>res;
     Breack;
     
     default:
     cout<<"No existe";
     Breack;
     
return 0;
}
