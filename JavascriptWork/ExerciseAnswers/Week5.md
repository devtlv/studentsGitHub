### Solution WEEK 5 REMOTE LEARNING Exercise: Build an Interactive Todo List Application

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Todo List</title>
    <style>
      .completed {
        text-decoration: line-through;
      }
    </style>
  </head>
  <body>
    <h1>Todo List</h1>
    <form id="todo-form">
      <input type="text" id="task-input" placeholder="Add new task" />
      <button type="submit">Add</button>
    </form>
    <ul id="task-list"></ul>
    <button id="clear-completed">Clear Completed</button>

    <script>
      // Function to create a new task item
      function createTaskItem(taskContent) {
        const li = document.createElement("li");
        li.innerText = taskContent;
        li.addEventListener("click", toggleTask);
        return li;
      }

      // Function to add a new task
      function addTask(event) {
        event.preventDefault();
        const taskInput = document.getElementById("task-input");
        const taskContent = taskInput.value.trim();
        if (taskContent !== "") {
          const taskItem = createTaskItem(taskContent);
          document.getElementById("task-list").appendChild(taskItem);
          taskInput.value = "";
        }
      }

      // Function to toggle task completion
      function toggleTask() {
        this.classList.toggle("completed");
      }

      // Function to remove completed tasks
      function clearCompletedTasks() {
        const completedTasks = document.querySelectorAll(".completed");
        completedTasks.forEach((task) => task.remove());
      }

      document.getElementById("todo-form").addEventListener("submit", addTask);
      document.getElementById("clear-completed").addEventListener("click", clearCompletedTasks);
    </script>
  </body>
</html>
```

1. A form to input new tasks and a button to add them to the todo list.
2. The list of tasks is displayed dynamically on the webpage.
3. Tasks can be marked as completed by clicking on them.
4. There is a feature to remove tasks from the list.
5. A button is provided to clear all completed tasks at once.
