#include<iostream>
using namespace std;
int GCG(int,int);
int main()
{
	int a,b,c;
	cout<<"请输入两个自然数：";
	cin>>a>>b;
	c=GCG(a,b);
	cout<<"\n最大公因数是："<<c;
	return 0; 
}
int GCG(int x,int y)
{
	int z,w; 
	cout<<"x:"<<x<<"\ty:"<<y<<"\t"; 
	if(x!=y)   //如果y整除x，那么x=（x,y） 
	    while(x%y!=0)
	    {
	        w=x%y;
            cout<<"w:"<<w<<endl;
	        x=y;
	        y=w;//如果x<y，辗转相除法的第一步相当于二者互换 
	        cout<<"x:"<<x<<"\ty:"<<y<<"\t";
	    }//在x=qy+w中如果余数不为0，那么用余数w去除除数y。重复该步骤直至整除为止 
	return y; 
}

