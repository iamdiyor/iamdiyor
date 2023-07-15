- 👋 Hi, I’m @iamdiyor
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<
iamdiyor/iamdiyor is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->#include <stdio.h>

int main() {
  FILE *fptr;

  // Open a file in read mode
   fptr = fopen("filename.txt", "r");

  fprintf(fptr,"trasdf" );
  

  // Store the content of the file
  char myString[100];

  // Read the content and store it inside myString
while(fgets(myString, 100, fptr)) {
  
  
  


  // Print file content
  printf("%s", myString);  
