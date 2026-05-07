 PROG103_Assignment1_nathanielernestawoonorrenner_905005845
 Student Grading System


 Features

 Input student name and ID
 Accept three subject marks
 Automatically calculate average
 Assign grades:

  A → 80 and above
  B→ 60–79
   C Below 60
  Supports multiple student entries
  Handles invalid inputs gracefully


Built With

 Python 3



Getting Started

 1. Clone the Repository

bash
git clone https://github.com/your-username/student-grading-system.git
cd student-grading-system
```

2. Run the Program


python student_grading.py

 Usage Example


 Enter Student Details 
Enter name: John Doe
Enter ID: 101
Enter mark 1: 75
Enter mark 2: 80
Enter mark 3: 70

 Student Result 
Name: John Doe
ID: 101
Average: 75.00
Grade: B

Add another student? (yes/no): no

Program Ended.




 Project Structure


student-grading-system/
│
├── student_grading.py    Main program file
└── README.md             Project documentation




 How It Works

1. The program collects student details
2. It calculates the average using:

   
   average = (m1 + m2 + m3) / 3
   
3. A grade is assigned based on the average
4. The user can choose to enter another student



 Error Handling

 Prevents crashes from non-numeric inputs
 Prompts user to re-enter valid data



 Future Improvements

 Save results to a file (CSV/Excel)
 Add GPA calculation system
 Build a graphical user interface (GUI)
 Connect to a database



 Author

Nathaniel Awoonor-Renner



 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this software.



 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.


 Support


