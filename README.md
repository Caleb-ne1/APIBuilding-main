
<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="margin-bottom: 20px;">
        <img src="/static/images/random-student-page.png" alt="Random student Page" width="200" height="200">
    </div>
    <div style="display: flex; justify-content: center;">
        <div style="flex: 1;">
            <img src="/static/images/random-dog-page.png" alt="Image 1" width="200" height="200">
        </div>
        <div style="flex: 1;">
            <img src="/static/images/random-fact-page.png" alt="Image 2" width="200" height="200">
        </div>
    </div>
</div>

# APIBuilding Django Project

This Django project provides functionalities to generate random facts, random student details and random dog images. It utilizes external APIs to fetch data and render it in the HTML template.

## Project Overview

The project consists of the following components:

1. **HTML Template**: `index.html` - This template includes sections for displaying random facts, random student details, and random dog images.

2. **Static Files**:
   - `styles.css`: Contains custom CSS styles for the HTML template.
   - `script.js`: Includes JavaScript code to handle dynamic content and API requests.

3. **Views**: `views.py` - Defines view functions to handle different API requests and render the HTML template.

4. **External APIs**:
   - Useless Facts API: Fetches random useless facts.
   - Free Test API: Retrieves random student details.
   - Dog CEO API: Fetches random dog images by breed and sub-breed.

## How to Use

#### 1.Clone the Repository:
<div style="background-color: black; padding: 10px;">
    <pre><code>
    git clone https://github.com/Caleb-ne1/APIBuilding-main.git
    </code></pre>
</div>

#### 2.Navigate to the Project Directory:
<div style="background-color: black; padding: 10px;">
    <pre><code>
    cd repository
    </code></pre>
</div>

#### 4. Install Dependencies
<div style="background-color: black; padding: 10px;">
    <pre><code>
    pip install -r requirements.txt
    </code></pre>
</div>

#### 5. Run the Development Server
<div style="background-color: black; padding: 10px;">
    <pre><code>
    python manage.py runserver
    </code></pre>
</div>

#### 6. Access the Application:
Open a web browser and navigate to http://127.0.0.1:8000/ or http://localhost:8000/ to access the running Django application.

## JavaScript Functions

Inside 'index.html' file `<script>` tag  contains JavaScript functions to interact with the backend and handle dynamic content updates. Here's a summary of the functions:

1. **Fetch Random Fact**: Fetches a random fact from the backend API when the page loads or when the "Next Random Fact" button is clicked.

2. **Fetch Random Student**: Retrieves random student details from the backend API and updates the student information section when the page loads or when the "Next Student" button is clicked.

3. **Fetch Random Dog Image**: Fetches a random dog image from the backend API when the page loads or when the "Generate another image" button is clicked.

4. **Fetch Random Dog Image by Breed**: Fetches a random dog image based on the selected breed from the dropdown menu.

5. **Fetch Random Dog Image by Sub-breed**: Fetches a random dog image based on the selected breed and sub-breed from the dropdown menus.

