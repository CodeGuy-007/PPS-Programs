				Project File
              		Programming for Problem Solving

```Name: Akshat Saluja
Branch: IT-A1
Roll No: 1921007
Submitted To: Prof. Ranjodh Kaur```


	////////////////////// Farenheit to Centigrade /////////////////////////
	#include <stdio.h>
	float temp_f;     /* degrees fahrenheit */
	float temp_c;     /* degrees centigrade */

	int main() {
	printf("Input a temperature (in Centigrade): ");
	fgets(line_text, sizeof(line_text), stdin);
	sscanf(line_text, "%f", &temp_c);

	temp_f = ((9.0 / 5.0) * temp_c) + 32.0;
	printf("%f degrees Fahrenheit.\n", temp_f);

	return(0);
	}

	Output:
	Input a temperature (in Centigrade): 45                                                                       
	113.000000 degrees Fahrenheit.


