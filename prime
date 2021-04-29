#include <iostream>

using namespace std;

int main()
{
	int input, jum, i, j;
	int count = 0;

	cout<<"+-------------------------+\n";
	cout<<"| >> PROGRAM BIL PRIMA << |\n";
	cout<<"+-------------------------+\n";
	cout<<"===========================\n";
	cout<<"Masukan nilai input : ";
	cin>>input;
	
	if(input > 0){
	cout<<"Bilangan Prima : \n";
	
	for(i=1;i<=5000;i++){
		jum = 0;
		for(j=1;j<=i;j++){
			if(i%j == 0){
				jum++;
			}
		}
		if (jum == 2){
			count++;
			if (count <= input){
				cout<< i <<" ";
			}
		}
	}
	
    }else{
    	cout<<"Nilai input harus lebih dari 0!";
	}
	
return 0;

}
