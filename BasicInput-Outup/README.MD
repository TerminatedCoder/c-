* Cpp I/O operation is using the stream is the sequence of the bytes or flow of data. It makes performance fast.

* If bytes flow from main memort to device like printer display screen, or network connection this is called as output operations.

* If bytes flow from device like printer, display to memory this is called input operation.


==============================================================

==> Header files:-
                These are those files that store predefined functions. It contains definitions of functions that you can include or import using a preprocessor directive #include. This preprocessor directive tells the compiler that the header file needs to be processed prior to the compilation.

==> Some Header Files and its usage
--> 
   1. <iostream>   It is used to define 'cout' 'cin' and cerr objects which corrosponds to standard output stream, standard input 
                    stream respectively.  
   2. <iomanip>     It is used to declare services useful foe performing formatled I/O such as sefprecision.

   3. <fstream>     It is used to declare services for user-control file processing.


==============================================================

=======>            Standard Output stream            <=======

--> The cout is predefine object of ostream class. It is connected with standard output device, which is usually a display screen. The cout is used in conjuction with the stream insertion operator(<<) to display output.

=======> Here is the example for output stream <=============

#include<iostream>
using namespace std;

int main(){
    cout<<"Hello";
};

output//-->
            Hello

==============================================================

=======>            Standard Input stream            <=======

--> The cin is predefined object of istream class it is connected with the standard input device, which is usually as keyword.
--> The cin is used in conjunction with stream exhaction operator(>>) to read the input form a console.

=======>  Here is the example for Input stream  <=============

 #include<iostream>
using namespace std;

int main(){
    int input;
    cout<<"Enter some value: \n";
    cin>>input;
    cout<<"This is your input: "<<input;
};

OUtput//--> 
            Enter some value: 5(user enter value and hit enter)
            This is your input: 5

==============================================================

=======>         Standard end-line(endl) and \n       <=======

--> This endl and \n are predefine object of ostream class. It is used to insert a new line charactors and flushes the stream.

=======>      Here is the example for endl      <=============

#include<iostream>
using namespace std;
int main(){
    cout<<"Hello ";
    cout<<"This test in the same line"<<endl;
    cout<<"This text in the new line\n";
    cout<<"This text also in the new line";
};

Output//-->
            Hello This test in the same line
            This text in the new line.
            This text also in the new line.

===============================================================