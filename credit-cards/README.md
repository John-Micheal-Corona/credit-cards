# credit-cards
/*
John Corona
Date: 02/20/2022
Professor: Kyle Muldrow
CIN: 0966283
*/

# include <iostream>
# include <iomanip>

using namespace std;
int main()

{
    //part 1
 double weight;
 double poundWeight;

 cout<<"Enter the weight in kilogram"<<endl;
 cin>>weight;
 poundWeight=(weight*2.2);
 cout<<"The weight in kilograms is:"<<setprecision(2)<<fixed<<weight<<endl;
 cout<<"The weight in pounds is:"<<setprecision(2)<<poundWeight<<endl;

 cout << endl;
 cout << endl;
 //Part 2

 double averageDailyBalance;
 double netBalance;
 double d1;
 double d2;
 double payment;
 double interest;
 double monthlyInterestRate;

 cout<<"Enter the net Balance: ";
 cin >> netBalance;
 cout<< "Enter payment made: ";
 cin >> payment;
 cout << "Enter the number of days in the billing cycle: ";
 cin >> d1;
 cout << "Enter the number of days  payment is made before billing cycle: ";
 cin >> d2;
 cout << "Enter interest pre month ";
 cin >> monthlyInterestRate;

 averageDailyBalance=(netBalance*d1-payment*d2)/d1;
 interest=averageDailyBalance*0.0152;

 cout<< "total interest: "<< interest<< endl;




return 0;
}


