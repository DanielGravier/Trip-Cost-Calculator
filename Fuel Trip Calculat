#include <iostream>
using namespace std;

int main (){
 double distance, mpg, fuelPrice, tripCost; //delcaring variables
 
 // Ask the user for the distance of the trip
 cout<<"Enter the distance of the trip (in miles): ";
 cin>>distance;

 // Error handling for invalid input
 if(cin.fail() || distance <=0){
     cout<<"Invalid input. Distance must be a positive number"<< endl;
     return 0;
 }
 // Ask the user for the car's efficiency
 
 cout<<"Enter the car's fuel efficiency (miles per gallon): ";
 cin>>mpg;
 
 // Error handling for invalid input
 
 if(cin.fail() || mpg <=0){
     cout<<"Invalid input. Miles per gallon must be a positive number"<< endl;
     return 0;
 }
 // Ask the user for the price of the fuel per gallon
 
  cout<<"Enter the price of the fuel per gallon: ";
    cin>>fuelPrice;
    
    // Error handling for invalid input
    
 if(cin.fail() || fuelPrice <=0){
     cout<<"Invalid input. The Fuel price must be a positive number"<< endl;
     return 0;
 }
    //Calculate the entirity of the trips cost
    tripCost = (distance / mpg) * fuelPrice;
    
    //The price you pay for fuel
    
    cout<<"The total price of fuel to arrive at your destination for your trip is: $ "<< tripCost<< endl;
    
    return 0;
    
    
}
