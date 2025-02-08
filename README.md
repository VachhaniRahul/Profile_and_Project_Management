<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <h1>Profile and Project Management System</h1>
    <h2>Description</h2>
    <p>
        The <strong>Profile and Project Management System</strong> is a Django web application that allows users to view developer profiles, browse projects, and send messages for collaboration. Users can also upload and manage their own projects. It is designed to help developers and clients connect and efficiently manage projects.
    </p>
    <h2>Features</h2>
    <ul>
        <li><strong>View Developer Profiles:</strong> Browse and explore developer profiles.</li>
        <li><strong>Browse Projects:</strong> View ongoing and past projects uploaded by developers.</li>
        <li><strong>Send Messages:</strong> Directly communicate with developers for collaboration opportunities.</li>
        <li><strong>Upload Projects:</strong> Upload and manage your own projects on the platform.</li>
    </ul>
    <h2>Tech Stack</h2>
    <ul>
        <li><strong>Backend:</strong> Django, Django Rest Framework (DRF)</li>
        <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
        <li><strong>Database:</strong> SQLite</li>
    </ul>
    <h2>Requirements</h2>
    <p>To run this project locally, make sure you have the following installed:</p>
    <ul>
        <li>Python 3.x</li>
        <li>Django 5.x</li>
    </ul>
    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/VachhaniRahul/Profile_and_Project_Management.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd Profile_and_Project_Management</code></pre>
        </li>
        <li>Create a virtual environment:
            <pre><code>python -m venv venv</code></pre>
        </li>
        <li>Activate the virtual environment:
            <ul>
                <li>On Windows:
                    <pre><code>.\venv\Scripts\Activate.ps1</code></pre>
                </li>
                <li>On macOS/Linux:
                    <pre><code>source venv/bin/activate</code></pre>
                </li>
            </ul>
        </li>
        <li>Install the required dependencies:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li>Run migrations to set up the database:
            <pre><code>python manage.py migrate</code></pre>
        </li>
        <li>Start the development server:
            <pre><code>python manage.py runserver</code></pre>
        </li>
        <li>Open your browser and go to:
            <pre><code>http://127.0.0.1:8000/</code></pre>
        </li>
    </ol>
    <h2>Usage</h2>
    <h3>Viewing Developer Profiles</h3>
    <ul>
        <li>Click on the "View Developer Profiles" link to see a list of all available developer profiles.</li>
    </ul>
    <h3>Viewing Projects</h3>
    <ul>
        <li>Click on the "Browse Projects" link to see a list of ongoing and completed projects.</li>
    </ul>
    <h3>Sending Messages</h3>
    <ul>
        <li>Click on "Send Message" to communicate directly with a developer.</li>
    </ul>
    <h3>Uploading Projects</h3>
    <ul>
        <li>Click on "Upload Project" to add a new project to the platform.</li>
    </ul>
   <h2>Contributing</h2>
    <p>
        Contributions are welcome! Please submit a pull request or open an issue for any suggestions or bug reports.
    </p>
</body>
</html>
