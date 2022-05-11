# data-structure-array
#include<iostream.h>
#include<conio.h>
class arr
{
	int a[10],n,m;
	public:
	void get();
	void display();
	
};
void arr::get()
{
	cout<<"enter size of array"<<endl;
	cin>>n;
	cout<<"enter array elements "<<endl;
	for(int i=0;i<=n;i++)
	{
		cin>>a[i];
	}
	cout<<"Elements are"<<endl;
	for(int j=0;j<=n;j++)
	{
		cout<<a[j]<<"  "<<endl;
	}
	cout<<endl;
}

void arr::display()
{
	cout <<"Sorted Element List ...\n";
for(int i = 0; i<=n; i++) 
{
   cout <<a[i]<<endl;
}

}


void main()
{
	clrscr();
	arr a;
	a.get();
	a.display();
	getch();
}
Algorithm:
1.Repeat For I = LB to UB
2.Apply PROCESS to A[I]
[End of For Loop]
3.Exit
