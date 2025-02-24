<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Task-Manager</title>
</head>
<body>
  <h1>Task-Manager</h1>
  <p>A simple and efficient task management application built with Django.</p>

  <h2>Description</h2>
  <p>Task-Manager is designed to help users manage their tasks efficiently. This application provides a user-friendly interface for tracking tasks, setting deadlines, and organizing work.</p>

  <h2>Features</h2>
  <ul>
    <li>Create, update, and delete tasks</li>
    <li>Set deadlines and priorities</li>
    <li>Organize tasks into categories</li>
    <li>User-friendly interface</li>
  </ul>

  <h2>Installation</h2>
  <p>To get started with Task-Manager, follow these steps:</p>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/AndiCrow/Task-Manager.git</code></pre>
    </li>
    <li>Navigate to the project directory:
      <pre><code>cd Task-Manager</code></pre>
    </li>
    <li>Create a virtual environment:
      <pre><code>python -m venv venv</code></pre>
    </li>
    <li>Activate the virtual environment:
      <ul>
        <li>On Windows:
          <pre><code>venv\Scripts\activate</code></pre>
        </li>
        <li>On macOS/Linux:
          <pre><code>source venv/bin/activate</code></pre>
        </li>
      </ul>
    </li>
    <li>Install the required dependencies:
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Apply migrations:
      <pre><code>python manage.py migrate</code></pre>
    </li>
  </ol>

  <h2>Usage</h2>
  <p>To run the application, use the following command:</p>
  <pre><code>python manage.py runserver</code></pre>
  <p>Open your web browser and navigate to <a href="http://localhost:8000">http://localhost:8000</a> to start using the Task-Manager.</p>

  <h2>Contributing</h2>
  <p>Contributions are welcome! Please fork the repository and create a pull request with your changes.</p>

  <h2>License</h2>
  <p>This project is licensed under the MIT License.</p>
</body>
</html>
