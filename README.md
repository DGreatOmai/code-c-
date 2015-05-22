# code-c-

/*
 *  Question1.cpp
 *
 *  Name:           [ OMAI, OLUCHI SYLVANUS ]
 *  Department:     [ STATISTICS ]
 *  Matric. No:     [ 45306461 ]
 *
 *  Program that reads an integer and determines
 *  and prints whether it’s odd or even
 *
 *  Stub file to enable you complete assignment #1 - question #1
 */

#include <iostream>
using namespace std;

int main()
{
    // declare variable to hold integer value
 
  int j,k;
    
    // display welcome messages to user
    cout << "Welcome - This program reads an integer\n";
    cout << "and determines if it is odd or even\n\n";
    
	
	std:: cout <<"Enter an integer\n";
	std:: cin >> j;
	if (j&1==1)
	std:: cout <<"odd\n";
	else
	std:: cout <<"even\n";
    
    return 0;
}


.
/*
 *  Question2.cpp
 *
 *  Name:           [ OMAI, OLUCHI SYLVANUS ]
 *  Department:     [ STATISTICS ]
 *  Matric. No:     [ 45306461CE ]
 *
 *  Program that reads two integers and determines
 *  if first is a multiple of second
 *
  */

#include <iostream>
using namespace std;

int main()
{
    // Variable declaration
    int j;
    int k;
    
    // display welcome messages to user
    cout << "Welcome - This program reads two integers\n";
    cout << "and determines if first is a multiple of second\n\n";
    
    {

	std:: cout <<"Enter an integer\j";
	std:: cin >> j;
	std:: cout <<"Enter an integer\k";
	std:: cin >> k;
	
	if (j%k==0)
	std:: cout << j <<" is a Multiple of" << k;
	
	else
	std:: cout << j << " is Not a multiple of" << k;
	
	return 0;
}



/*
 *  Question3.cpp
 *
 *  Name:           [ OMAI, OLUCHI SYLVANUS ]
 *  Department:     [ STATISRICS ]
 *  Matric. No:     [ 45306461CE ]
 *
 *  Program that prints a box, an oval, an arrow and a diamond
 *
 *  
 */

#include <iostream>
using namespace std;

int main()

{
    
	std::cout<<"********         ***                *               *  \n";
	std::cout<<"*      *       *     *	           ***            *   * \n";
	std::cout<<"*      *      *       *	          *****          *     * \n";  
	std::cout<<"*      *      *       *	            *           *       *\n";
	std::cout<<"*      *      *       *             *          *         *\n";
	std::cout<<"*      *      *       *             *           *       *\n";
	std::cout<<"*      *      *       *             *            *     *\n";
	std::cout<<"*      *       *     *              *             *   *  \n";
	std::cout<<"********         ***                *               *  \n";

	return 0;
	
}


QUESTION 4.
/*
 *  Question4.cpp
 *
 *  Name:           [ OMAI, OLUCHI SYLVANUS ]
 *  Department:     [ STATISTICS ]
 *  Matric. No:     [ 45306461CE ]
 *
 *  Program that inputs a five-digit integer,
 *  separates the integer into its digits and prints them separated by three spaces each
 *
 *  
 */

#include <iostream>
#include <string>
using namespace std;

int main()
{
    
    int fivedigits;
	int i,j,k,l,m;
    
    // display welcome messages to user
    cout << "Welcome - This program reads a five-digit integer\n";
    cout << "separates the integer into its digits and prints them\n";
    cout << "separated by three spaces each\n\n";
    
    
	std:: cout<< "please enter the five digits";
	std:: cin>> fivedigits;
	if (fivedigits<10000)
	{
	std:: cout<< "incorrect digits! Try again!";
	
	if (fivedigits>99999)
	
	std:: cout<< "correct digits!";
	}
	
	i=(fivedigits/10000);
	j=(fivedigits/1000)%10;
	k= (fivedigits/100)%10;
	l=(fivedigits/10)%10;
	m= fivedigits%10;
	
	std:: cout<<i;
	std:: cout<<"     "<<j;
	std:: cout<<"     "<<k;
	std:: cout<<"     "<<l;
	std:: cout<<"     "<<m;
	
	return 0;
}


QUESTION 5.
/*
 *  Question5.cpp
 *
 *  Name:           [ OMAI, OLUCHI SYLVANUS ]
 *  Department:     [ STATISTICS ]
 *  Matric. No:     [ 45306461CE ]
 *
 *  Program that calculates the squares and cubes of the integers from 0 to 10
 *
 *  
 */

#include <iostream>
#include <math.h>   // library to use pow() function to calculate squares and cubes
using namespace std;

int main()
{
    
    // display welcome messages to user
    cout << "Welcome - This program calculates the squares and cubes\n";
    cout << "of the integers from 0 to 10 and prints using tabs\n\n";
    

  cout << "integer\t\psquare\t\pcube\n";
  cout << 0 << "\t\t" << 0*0 << "\t\t" << 0*0*0 << "\n";
  cout << 1 << "\t\t" << 1*1 << "\t\t" << 1*1*1 << "\n";
  cout << 2 << "\t\t" << 2*2 << "\t\t" << 2*2*2 << "\n";
  cout << 3 << "\t\t" << 3*3 << "\t\t" << 3*3*3 << "\n";
  cout << 4 << "\t\t" << 4*4 << "\t\t" << 4*4*4 << "\n";
  cout << 5 << "\t\t" << 5*5 << "\t\t" << 5*5*5 << "\n";
  cout << 6 << "\t\t" << 6*6 << "\t\t" << 6*6*6 << "\n";
  cout << 7 << "\t\t" << 7*7 << "\t\t" << 7*7*7 << "\n";
  cout << 8 << "\t\t" << 8*8 << "\t\t" << 8*8*8 << "\n";
  cout << 9 << "\t\t" << 9*9 << "\t\t" << 9*9*9 << "\n";
  cout << 10 << "\t\t" << 10*10 << "\t\t" << 10*10*10 << "\n";
 
   return 0;
}




