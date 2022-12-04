#diffpermofanumber
//Find the minimum number of distribution of a number in which no two are same!
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int n;
	cin>>n;
	
	for(int i=0;i<n;i++) {
	        int a;
	        cin>>a;
	        
	        if(a<=6) {
	                cout<<"NO"<<endl;
	        }
	        else if(a>=21) {
	                cout<<"YES"<<endl;
	        }
	        else {
	                cout<<"NO"<<endl;
	        }
	}
	return 0;
}
  
  //ADD START WITH 1 TO N AND ANY NUMBER GREATER THAN THE SUM OF THEM,CAN HAVE THIS CONDITION SATISFIED. 
