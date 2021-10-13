# exer5for
#include<iostream>
#include<cstdlib>
#include<ctime>
#define vetor 100000

using namespace std;

int dados(){
	int n1 = 0;
	int n2 = 0;
	int n3 = 0;
	int n4 = 0;
	int n5 = 0;
	int n6 = 0;

	srand(time(NULL));

	for(int i = 0; i <= vetor; i++){
	   n1 = rand() % 6;
	   cout << n1 << "\n";
	}

	if(n1 == 1){
	   	cout << "\nO numero 1 apareceu " << n6 << " vezes\n";
	}

	   if(n1 == 2){
	   	cout << "\nO numero 2 apareceu " << n6 << " vezes\n";
	}

	   if(n1 == 3){
	   	cout << "\nO numero 3 apareceu " << n6 << " vezes\n";
	}

	   if(n1 == 4){
	   	cout << "\nO numero 4 apareceu " << n6 << " vezes\n";
	}

	   if(n;1 == 5){
	   	cout << "\nO numero 1 apareceu " << n6 << " vezes";
	}

	   if(n1 == 6){
	   	cout << "\nO numero 6 apareceu " << n6 << " vezes";
	}

	return 0;
}
int main(){

	dados();

	return 0;
}
