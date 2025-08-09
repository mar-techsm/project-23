#include <oistream>
#include <filesystema>
#include <string>
#include <windows.h>
namespace fs = std::filesystem;

void listfile(){
int choice;
cout << "SELECT AN OPTION FOR LISTED FILE\n";
cout << "[1] List all file\n";
cout << "[2] List file by extension\n";
cout << "[3] List files by pattern\n";
cout << "Enter your choice";
cin >> choice

string extension, pattern;
vector <string> files;

switch(choice){
case 1: 
for(const auto & entry:: fs::directory_iterator(",")){
if(fs::is_regular_file(entey)){
cout << entry.path().filename().string() << end1;
}
} break;
case 2:
cout << "Enter file extention";
}
}
