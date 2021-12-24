#include<bits/stdc++.h>
using namespace std ; 
int main()
{
	int n ; 
	cout<<" n ="; 
	cin>> n ; 
	int *A = new int[n]; 
	for(int i = 0 ; i< n ; i++)
	{
		cout<<"Nhap phan tu thu "<<i+1<<":" ; 
		cin>>A[i]; 
	}
	int p1 , p2 ; 
	cout<<"p1="; 
	cin>>p1 ; 
	cout<<"p2="; 
	cin>>p2 ; 
	int dem = 0 ; 
	cout<<"Nhung phan tu nam trong doan p1 va p2 :" ; 
	for(int i = 0 ; i< n ; i++)
	{
		if(A[i] >= p1 && A[i] <=p2)
		{
			cout<<A[i]<<" " ; 
			dem ++ ; 
		}
	}
	cout<<"\nso luong phan tu nam trong p1 va p2 la :"<<dem; 
	

