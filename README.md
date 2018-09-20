# How-long-is a-word-
#include "std_lib_facilities.h"

int main()
{
int a = 1;
int steps = 0;

while (a != 0)
	{a <<= 1;
	++steps;
	}
cout<<steps<<'\n';
}
