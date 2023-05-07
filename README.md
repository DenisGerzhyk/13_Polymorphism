# 13_Polymorphism

File 1-4:

1).
This program defines three classes: Animal, Cat, Dog, and Fish. The Animal class has a constructor that initializes an instance variable sound with the sound argument passed to the constructor. It also has a method make_sound that does nothing, as it is meant to be overridden by the subclasses. The Cat, Dog, and Fish classes inherit from the Animal class and each implement the make_sound method to print out their respective sounds. The program then creates instances of each of the classes and calls their make_sound methods.

2).
This program defines four classes: Shape, Circle, Square, and Rectangle. The Shape class has a constructor that does nothing and an area method that does nothing, as it is meant to be overridden by the subclasses. The Circle, Square, and Rectangle classes inherit from the Shape class and each implement the area method to calculate the area of their respective shapes. The program then creates instances of each of the classes and calls their area methods to print out their respective areas.

3).
This program defines a class ObjectList with a constructor that initializes an instance variable list with the list argument passed to the constructor. It also has a method print_info that iterates over the elements of the list and prints out the type of each element and its attributes (if any). The program then creates an instance of the ObjectList class with a list of various types of objects and calls its print_info method.

4).
This program defines four classes: Building, School, Hospital, and Museum. The Building class has a constructor that initializes instance variables name, address, and count_of_floor with the corresponding arguments passed to the constructor. It also has a method description that prints out the name, address, and count of floors of the building. The School, Hospital, and Museum classes inherit from the Building class and each implement the description method to call the superclass description method. The program then creates instances of each of the classes and calls their description methods to print out information about the buildings.

File 5:

This code defines three classes: Group, Human, and Student, as well as an output module that demonstrates the functionality of the Group class.

The Group class has an attribute number which represents the group number, and a set attribute group to store the Student objects in the group. The class has methods to add a student to the group (add_student()), remove a student from the group by last name (delete_student()), and find a student by last name (find_student()). The __str__() method is overridden to return a string representation of the group and its students.

The Human class represents a human and has attributes gender, first_name, last_name, and age. The __str__() method is overridden to return a string representation of a human's information.

The Student class is a subclass of Human and has an additional attribute record_book. It inherits the __init__() and __str__() methods from Human, but overrides __str__() to include the record book number.

The output module creates two Student objects, adds them to a Group object gr, and prints the string representation of gr. It then finds a student by last name and attempts to find a non-existent student. It finally deletes both students from the group and prints the updated string representation of the group.

File 6:

This is a Python code that defines three classes: Human, Student, and Group.

Human class defines the basic attributes of a human such as gender, first_name, last_name, and age. It also has a __str__ method which returns a string representation of an instance of this class.

Student class is derived from Human and has an additional attribute record_book. The __str__ method of this class returns the value of record_book attribute.

Group class has a number attribute and a group attribute which is a set of Student instances. It also has several methods to manipulate the group attribute such as add_student, delete_student, and find_student. The __str__ method of this class returns a string representation of all Student instances in the group.

The code creates two instances of Student class, st1 and st2, and one instance of Group class, gr. Then, it adds the two Student instances to the group attribute of gr using add_student method. It then prints the gr instance using print(gr).

Next, it calls find_student method of gr instance twice with two different last_name arguments. The first call searches for a student with last name "Jobs" which should return the st1 instance. The second call searches for a student with last name "Jobs2" which should return None.

Afterwards, it calls delete_student method of gr instance twice with two different last_name arguments. The first call removes the student with last name "Taylor" from the group attribute of gr, leaving only one student in the group. Finally, it prints the gr instance again.




