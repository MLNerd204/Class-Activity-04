#include <iostream>
#include <iomanip> // For std::setw and std::left

int main() {
    // Set the width for the columns
    const int courseWidth = 15;
    const int studentWidth = 10;
    std::cout << std::left << std::setw(courseWidth) << "Course"
    << std::right << std::setw(studentWidth) << "Student" << std::endl;
    std::cout<<"-------------------------\n";
    std::cout << std::left << std::setw(courseWidth) << "C++"
    << std::right << std::setw(studentWidth) << 100 << std::endl;
    std::cout << std::left << std::setw(courseWidth) << "JavaScript"
    << std::right << std::setw(studentWidth) << 50 << std::endl;
    return 0;
}


//This program has allowed me to sort out the number student for each are 100 and 50. our text labels are left align, 
//and our numbers are right aligned. 

