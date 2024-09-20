#include <iostream>
#include <vector>
#include <string>
  
  Using namespace std;

   class Product {
    public:
         string name;
         double price;

          Product(string name,double price) : (name(name), price(price) {}
};

int main() {
    vector<Product> products;
    products.push_back(Products(”Shirts”, 19.99);
products.push_back(Products(”Pants”, 29.99);
products.push_back(Products(”Shoes”’ 49.99);

 double total  = 0,0

 cout <<”Welcome to the shopping app!” << endl;
 cout <<”________________________” << endl;

for (int i =0; i < product.size(); i++) {
   cout << i + 1 <<”.” << produce[I].name << “ -$” << product[I].price 
}

cout << endl;
cout <<” enter the product number you want to buy (or 0 to quit): “;
int choice;
cin >> choice;


  while (choice != 0) {
      if (choice >= 1 && choice <= product.size()) {
       total += product[choice - 1].price;
     cout << product[choice -1].name <<” added to cart.”” << endl;
} else {
cout <<”Invalid choice. Please try again.” << endl;
}

cout << endl;
cout << ”Enter the product number you want to buy (or 0 to quit): “;
cin >> choice;
}

cout << endl;
cout << “Total: $” << total << endl;

eturn 0;
}
