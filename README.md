[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
/*
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
        std::string model;
        std::string color;
        int year;
     std::cout << "Enter model" << std::endl;
     std::cin >>model;
     std::cout << "Enter color" << std::endl;
     std::cin >>color;
     std::cout << "Enter year" << std::endl;
     std:: cin >>year;
     

	Toyota.setColor(color);
	Toyota.setModel(model);
	Toyota.setYear(year);
//	std::cout << Toyota.getModel();
//	std::cout << Toyota.getColor();
//	std::cout << Toyota.getColor();
//	std::cout << Toyota.getYear();
	Toyota.displayDetails();

        return 0;
}


```
