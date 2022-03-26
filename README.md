### Project Description ###
This is a simple console for making simple calculation operations like (Addition, Subtraction, Multiplication and Division)

### How it's Work ###
Here is the complete code of the app written in C#. In the program, there are four functional blocks–Addition, Subtraction, Multiplication, and Division. The user has to select one of the options for addition, subtraction, multiplication, and division respectively.

“Press 1 for Addition”.
“Press 2 for Subtraction”.
“Press 3 for Multiplication”.
“Press 4 for Division”.

            Console.WriteLine("Enter the action to be performed");  
            Console.WriteLine("Press 1 for Addition");  
            Console.WriteLine("Press 2 for Subtraction");  
            Console.WriteLine("Press 3 for Multiplication");  
            Console.WriteLine("Press 4 for Division \n");  
            int action = Convert.ToInt32(Console.ReadLine());  
            Console.WriteLine("Enter 1st input");  
            int input_1 = Convert.ToInt32(Console.ReadLine());  
            Console.WriteLine("Enter 2nd input");  
            int input_2 = Convert.ToInt32(Console.ReadLine());  
            int result = 0;  
            
* Switch

            switch (action) {  
                case 1: {  
                    result = Addition(input_1, input_2);  
                    break;  
                }  
                case 2: {  
                    result = Subtraction(input_1, input_2);  
                    break;  
                }  
                case 3: {  
                    result = Multiplication(input_1, input_2);  
                    break;  
                }  
                case 4: {  
                    result = Division(input_1, input_2);  
                    break;  
                }  
                default:  
                    Console.WriteLine("Wrong action!! try again");  
                    break;  
            }  
            Console.WriteLine("The result is {0}", result);  
            Console.ReadKey();  
        }  

* Addition Function

        //Addition  
        public static int Addition(int input_1, int input_2) {  
            int result = input_1 + input_2;  
            return result; 
            
 * Subtraction Function

        //Substraction  
        public static int Subtraction(int input_1, int input_2) {  
            int result = input_1 + input_2;  
            return result; 
            
 * Multiplication Function

        //Multiplication  
        public static int Multiplication(int input_1, int input_2) {  
            int result = input_1 + input_2;  
            return result;  
            
 * Division Funcation

        //Division  
        public static int Division(int input_1, int input_2) {  
            int result = input_1 + input_2;  
            return result;  
