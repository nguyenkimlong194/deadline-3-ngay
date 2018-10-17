# deadline-3-ngay
#include<bits/stdc++.h>
#define h first
#define w second
#define t third
using namespace std;
vector<int>a,b,c;
int main()
{
	int hi,we,tu;
	int i=0;
	while(cin >>hi>>we>>tu)
	{
		i++;
		a.push_back(hi);
		b.push_back(we);
                c.push_back(tu);
	}
	for(int j=0;j<i;j++)
	{
	if (c[j] < 18)
	{
		cout <<c[j]<<endl;
	}
	}
	return 0;
}
