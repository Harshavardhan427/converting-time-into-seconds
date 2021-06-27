# converting-time-into-seconds
#include<iostream>
using namespace std;
class Time
{
	private:
		int seconds;
		int hh,mm,ss;
		
	   public:
	         gettime();
		    void conversion()
		     {
		     	seconds = hh*3600 + mm*60 + ss;
			 }
		     displaytime();
};
Time :: gettime()
{
cout<<"enter time : ";
cout << "\nhours : ";
cin>>hh;
cout << "\n minutes : ";
cin>>mm;
cout << "\n seconds : ";
cin>>ss;
};
Time :: displaytime()
{
	cout << "the total time in seconds : " <<seconds;
}

int main()
{
	Time t;
	t.gettime();
	t.conversion();
	t.displaytime();
	return 0;
}
  
  output :
  enter time :
hours : 1

 minutes : 1

 seconds : 6
the total time in seconds : 3666
  ******
