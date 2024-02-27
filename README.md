## Petting Zoo School Visit Planner

This C# console application assists in planning school visits to a petting zoo. It randomly assigns groups of animals to each school visiting, ensuring an enjoyable and diverse experience for the students. Below is a breakdown of how the application works:

### How to Run the Application
Compile and execute the provided code in a C# environment to run the application.

### Application Flow
1. The application maintains a list of animals available in the petting zoo.
2. The `PlanSchoolVisit` method is called for each school visit, specifying the school's name and the number of groups attending (defaulted to 6 if not specified).
3. Inside `PlanSchoolVisit`:
   - `RandomizeAnimals` method is called to shuffle the order of animals in the petting zoo array.
   - `AssignGroup` method is called to assign animals to each group.
   - The school name is printed, followed by the assigned groups of animals.
4. `AssignGroup` method divides the available animals into the specified number of groups, ensuring each group gets an equal share, or as close to it as possible.
5. `PrintGroup` method prints out the assigned groups, with each group labeled and displaying the animals within it.

### Code Structure
- **Main Method**: The entry point of the application.
- **PlanSchoolVisit Method**: Responsible for planning a school visit. It randomizes animals, assigns them to groups, and prints the groups for the specified school.
- **RandomizeAnimals Method**: Shuffles the order of animals in the petting zoo array using the Fisher-Yates shuffle algorithm.
- **AssignGroup Method**: Divides the available animals into the specified number of groups.
- **PrintGroup Method**: Prints the assigned groups of animals for a school visit.

### Note
This application provides a basic tool for planning school visits to a petting zoo. Modifications or enhancements can be made to suit specific requirements, such as handling larger groups, adding more animals, or integrating with a scheduling system. Enjoy the school visits!# Petting-Zoo-Visit
