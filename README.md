# Todo-Priority-List
Created a priority list command line interface using python. Used functional programming approach to solve different tasks.
This program is a simple to-do list application with priority that allows users to add, list, delete, and mark tasks as completed. The program reads user input and calls functions accordingly. 

The program has several functions to implement each operation, such as addingTasks, listingTasks, delete, done, report, and Help. The add function appends new tasks to the list of tasks and sorts them in ascending order by priority. It then saves the tasks to a task.txt file. The listing function reads the tasks from the task.txt file and displays them. 

The delete function deletes tasks based on their index and updates the task.txt file accordingly. The done function marks tasks as completed by deleting them from the task list and adding them to a completed.txt file. The report function displays the number of pending and completed tasks and the contents of their respective files. The Help function prints usage instructions. 

The program also creates two files, task.txt and completed.txt, to store the pending and completed tasks, respectively. The program uses the os module to create a new directory in the user's home directory to store the files.
