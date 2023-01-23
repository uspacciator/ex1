#ex1
#include <iostream>     
using namespace std;

int main()              
{

int scelta;
int somma;
int sottr;

cout<<"INSERISCI SCELTA: "<<endl;
cin>>scelta;

do{
switch(scelta)
{
case 1:
int n1;
int n2;
int somma;
cout<<"INSERISCI IL PRIMO NUMERO: "<<endl;
cin>>n1;
cout<<"INSERISCI IL SECONDO NUMERO: "<<endl;
cin>>n2;	
somma=n1+n2;
cout<<"LA SOMMA DEI NUMERI E': "<<somma<<endl;		      
break;

case 2:
int n3;
int n4;
int sottr;
cout<<"INSERISCI IL PRIMO NUMERO: "<<endl;
cin>>n3;
cout<<"INSERISCI IL SECONDO NUMERO: "<<endl;
cin>>n4;	
sottr=n3-n4;
cout<<"LA DIFFERENZA DEI NUMERI E': "<<sottr<<endl;		        
break;

case 3:
int n5;
int n6;
int molt;
cout<<"INSERISCI IL PRIMO NUMERO: "<<endl;
cin>>n5;
cout<<"INSERISCI IL SECONDO NUMERO: "<<endl;
cin>>n6;	
molt=n5*n6;
cout<<"IL PRODOTTO DEI NUMERI E': "<<molt<<endl;		        
break;

case 4:
int n7;
int n8;
int div;
cout<<"INSERISCI IL PRIMO NUMERO: "<<endl;
cin>>n7;
cout<<"INSERISCI IL SECONDO NUMERO: "<<endl;
cin>>n8;	
div=n7/n8;
cout<<"IL QUOZIENTE DEI NUMERI E': "<<div<<endl;		        
break;

default:
cout<<"ESCO DAL PROGRAMMA ";	
}
}while(scelta>=1 && scelta<=4);




return 0;
}
