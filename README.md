#include <iostream>

using namespace std;

int main(){
double mark;
char grade;
cout << "Enter your mark: ";
 cin >> mark;
if(mark >= 70){
cout<< "Grade is A";
 }

else if(mark >=60){
    cout<< "Grade is B";
}

else if(mark>= 50){
    cout << "Grade is C";
}
else if (mark >= 40){
    cout<< "Grade is D";
}
else if(mark < 40){
    cout<< "Grade is E";
}
return 0;
}



