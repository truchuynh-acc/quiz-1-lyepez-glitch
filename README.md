[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
/*
* Name: Lucas Yepez
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
public:
    std::string model;
    int year;
    std::string color;
    


    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
    void setModel(std::string mdl){
    	model = mdl;
    }
    std::string getModel(){
    	return model;
    }
    void setYear(int yr){
    	year = yr;
    }
    int getYear(){
    	return year;
    }
    void setColor(std::string clr){
    	color = clr;
    }
    std::string getColor(){
    	return color;
    }
};

int main() {
        Car myCar;
        Car Toyota;

	Toyota.setColor("Red");
	Toyota.setModel("Hundai");
	Toyota.setYear(2023);
//	std::cout << Toyota.getModel();
//	std::cout << Toyota.getColor();
//	std::cout << Toyota.getColor();
//	std::cout << Toyota.getYear();
	Toyota.displayDetails();

        return 0;
}

```
