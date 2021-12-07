# Week10_ReadMePractise

## Breakfast

This morning I had a bowl of Aldi's own-brand cereal, with semi-skimmed milk.

### Social Media
Follow me on my [LinkedIn account](https://www.linkedin.com/in/ben-wakefield-clay-b87a94224/)

#### Octocat image

![This is an image of Octocat](https://github.com/StaffsBen/Week10_ReadMePractise/blob/main/583231.png)

##### Ordered List of my favourite games

1. The Legend of Zelda: Majora's Mask
2. Persona 4
3. Fire Emblem: Three Houses
4. The Leegend of Heroes: Trails in the Sky SC
5. Danganronpa 2: Goodbye Despair

###### Checklist of this to do for ProDev

 [x] Create a ReadMe Practise file
 [ ] Complete my portfolio
 [ ] Get started on my Report
 
**GEC code snippet**
======

```
#include <iostream>;

using namespace std;

void inputDetails(int* n1, int* n2);

void outputDetails(int& integer1, int& integer2, int* pointer);

int main() {

	int num1;
	int num2;

	int* pNum = &num1;

	inputDetails(&num1, &num2);

	cout << "The pointer is pointed at Integer 1\n";
	cout << endl;

	outputDetails(num1, num2, pNum);

	pNum = &num2;

	cout << endl;
	cout << endl;
	cout << "The pointer has now switched from Integer 1 to Integer 2\n";
	cout << endl;

	outputDetails(num1, num2, pNum);

	pNum = nullptr;
}

void inputDetails(int* n1, int* n2) {

	int _userInt1;
	int _userInt2;
	
	cout << "Please input an integer\n";
	cout << "Integer 1: ", cin >> _userInt1;
	cout << endl;

	cout << "Please input an integer\n";
	cout << "Integer 2: ", cin >> _userInt2;
	cout << endl;

	*n1 = _userInt1;
	*n2 = _userInt2;
}

void outputDetails(int& integer1, int& integer2, int* pointer) {

	cout << "The value of Integer 1 = " << integer1 << endl;
	cout << "The adress of Integer 1 = " << &integer1 << endl;

	cout << "The value of Integer 2 = " << integer2 << endl;
	cout << "The address of Integer 2 = " << &integer2 << endl;

	cout << "The address that pNum holds is = " << pointer << endl;
	cout << "The dereferenced value of pNum is = " << *pointer << endl;
	cout << "The address of pNum itself is = " << &pointer << endl;
}
```

*Some emojis*
------

:+1:
:smile:
:cat:
