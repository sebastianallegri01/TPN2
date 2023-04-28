#include <bits/stdc++.h>

using namespace std;

float contardolares(float dolar, float resultado);

int main(){
	
		float dolar, resultado=331.37;
	
	cout<<"ingre su catidad de dolares: "<<endl;
	cin>>dolar;

    cout<<"la cantidad de pesos es de:"<<contardolares(dolar,resultado);
    
	return 0;
}

float contardolares(float dolar, float resultado){
	float peso;

	peso= resultado * dolar;

    return peso;
}
