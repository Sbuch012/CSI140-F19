#include <iostream>
#include <vector>
  
using namespace std;

int main()
{
	vector <string> myChickens=
		{"Rhode Island Red",
		"Buff Orpington",
		"Polish Crested",
		"Easter Egger"
		};
	for(string chicken: myChickens)
	{
		cout << chicken << endl;
	}
	cout << "All say hello from linux" << endl;
	
	return EXIT_SUCCESS;
}
