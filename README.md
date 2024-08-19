   # Todo-CLI-Go
   ![](https://github.com/hackice20/todo-cli-go/blob/main/Screenshot%202024-08-19%20085905.png)


   Todo-CLI-Go is a command-line interface (CLI) tool written in Go for managing a simple to-do list. It allows users to add, list, edit, and toggle tasks directly from the command line.

   ## Setup

   Follow these steps to get your Todo-CLI-Go project up and running:

   1. **Clone the Repository**

      ```bash
      git clone https://github.com/your-username/todo-cli-go.git
      ```

   2. **Go Setup**

      Navigate to the project directory:

      ```bash
      cd todo-cli-go
      ```

      Ensure you have Go installed. If not, download and install it from [the Go website](https://golang.org/dl/).

   3. **Build the Project**

      Build the project using the Go build command:

      ```bash
      go build -o todo
      ```

      This will create an executable file named `todo` in the project directory.

   ## CLI Commands

   Here are the commands you can use with the Todo-CLI-Go tool:

   | Command                         | Description                      |
   |---------------------------------|----------------------------------|
   | `./todo -add "task"`            | Add a new to-do item             |
   | `./todo -list`                  | List all to-do items             |
   | `./todo toggle <id>`            | Mark a to-do item as done        |
   | `./todo edit "<id> new_name"`   | Edit the name of an existing to-do item |

   ## Example Usage

   1. **Add a new to-do item:**

      ```bash
      ./todo -add "Buy groceries"
      ```

   2. **List all to-do items:**

      ```bash
      ./todo -list
      ```

   3. **Mark a to-do item as done:**

      ```bash
      ./todo toggle 1
      ```

   4. **Edit a to-do item:**

      ```bash
      ./todo edit "1 Buy groceries and more"
      ```

  
