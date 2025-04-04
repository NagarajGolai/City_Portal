
# City Portal

City Portal is a smart city platform that provides real-time updates on public safety, local events, news, and emergency services. It helps citizens stay informed, access essential resources, and engage with their community—all in one place.


## Deployment
To deploy this project run
### Step 1: Download the ZIP File
- Go to your GitHub repository.
- Click the “Code” button (green).
- Select “Download ZIP” and save it to your system.
- Extract the ZIP file to your preferred location (e.g., E:\CityPortal).

### Step 2: Open Terminal and Navigate to the Project Folder
If your project is in "E:\CityPortal", open Command Prompt and run:
```bash
  cd E:\DjangoProject
```
### Step 3: Create and Activate a Virtual Environment
```bash
python -m venv venv
```
#### Activate it:

+ Windows (CMD/PowerShell):
```bash
venv\Scripts\activate
```
+ Linux/Mac:

```bash
source venv/bin/activate
```

### Step 4: Install Dependencies
The project should have a requirements.txt file. Install dependencies by running:
```bash
pip install -r requirements.txt
```
If this does not work, install Django manually:

```bash
pip install django
```

### Step 5: Run Migrations
```bash
python manage.py migrate
```

### Step 6: Create a Superuser (Optional, for Admin Panel)
```bash
python manage.py createsuperuser
```
Follow the prompts to set up a username and password.

### Step 7: Run the Django Server
```bash
python manage.py runserver
```
Now, open http://127.0.0.1:8000/ in your browser.
