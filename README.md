# Projects-Index
List of All Projects and Repo Link

# Project Domains I have worked on : 
1) Machine Learning 
2) Web Development
3) Android Application Development
4) Academic Project 

# Machine Learning 
1) [Car Price Prediction](https://github.com/Sameer411/Car-Price-Prediction)
2) [Heart Disease Prediction](https://github.com/Sameer411/Bertelsmann-Scholarship-Study-Jam-1.0-ML-Project-Heart-Disease-Prediction)
3) [Emojify](https://github.com/Sameer411/Emojify-Bertelsmann-Scholrship-Program)
4) [Malware Detection](https://github.com/Sameer411/Malware-Detection-Using-Machine-Learning)
5) [Pneumonia Detection](https://github.com/Sameer411/Pneumonia-Detection-Bertelsmann-Scholarship)
6) [Movie Recomendation System](https://github.com/Sameer411/Movie-Recommendation-ML)
7) [Covid-19 Prediction using chest Xray](https://github.com/Sameer411/Covid19_Prdiction_Using_Chest_X-Ray)
8) [PDF Encryption](https://github.com/Sameer411/PDF-Encryption)

# Web Development 
1) [Weather Prediction](https://github.com/Sameer411/Weather-Web-Project)
2) [Foodies Restaurant](https://github.com/Sameer411/Foodies-restaurant-Website)
3) [AI based Chatbot](https://github.com/Sameer411/ChatBot)
4) [To Do Platform](https://github.com/Sameer411/ToDo-App)
5) [Foodies](https://github.com/Sameer411/Foodies)
6) [DOM Game](https://github.com/Sameer411/DOM-Game)
7) [Budgety](https://github.com/Sameer411/Budgety)
8) [Login Page](https://github.com/Sameer411/Login-Page-Template)

# Android Application 
1) [Weather Application Using Kotlin](https://github.com/Sameer411/Weather-App)
2) [Text Recognizer Using Kotlin](https://github.com/Sameer411/Text-Recognizer)
3) [Distance Convertor Using Java](https://github.com/Sameer411/Distance-Convertor)
4) [Calculator Using Java](https://github.com/Sameer411/Calculator_Android_Studio)
5) [Location Tracker Using Java](https://github.com/Sameer411/Maps-Android-Application)

# Academic Projects
1) [American ign Language Convertor](https://github.com/Sameer411/Sign-Language-to-Text-Conversion)
2) [Plagiarism Detection Software](https://github.com/Sameer411/Plagiarism-Detection-Software)



/*
        Constructor 

*/


                                                // Code 1 -> Basic Input Output

#include<iostream>
using namespace std; 

int main()
{
    int var = 6;
    cout<<"Value of Var = "<<sum;
    
    return 0;
}


                                                // Code 2 -> Creating class 

#include <iostream>  
using namespace std;  
class Student 
{  
   public:  
      int id;//data member (also instance variable)      
      string name;//data member(also instance variable)      
};  

int main() 
{  
    Student s1; //creating an object of Student   
    s1.id = 201;    
    s1.name = "Sameer Rathod";   
    cout<<s1.id<<endl;  
    cout<<s1.name<<endl;  
    return 0;  
}  



                                                // Code 3 -> Constructor Program 

// Cpp program to illustrate the
// concept of Constructors
#include <iostream>
using namespace std;

class construct
{
public:
	int a, b;
	// Default Constructor
	construct()
	{
		a = 10;
		b = 20;
	}
};

int main()
{
	// Default constructor called automatically
	// when the object is created
	construct c;
	cout << "a: " << c.a << endl
		<< "b: " << c.b;
	return 1;
}
