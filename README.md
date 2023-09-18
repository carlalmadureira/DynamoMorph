# DynamoMorph
Python library that simplifies the process of building complex DynamoDB queries and scans. This library can provide an intuitive API for developers to construct queries with ease.

## Setting up a Virtual Environment

A virtual environment helps you isolate your project's dependencies, ensuring that your project doesn't interfere with system-wide packages. To create a virtual environment, follow these steps:

```markdown
1. Open your terminal or command prompt
2. Navigate to your project directory
   ```bash
   cd your_project_directory
   ```

3. Create a virtual environment (replace 'venv' with your preferred name)
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment (commands may vary depending on your OS)
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```
```
```

Your terminal prompt should change, indicating that the virtual environment is active. You can deactivate it later using the deactivate command.

## Install Dependencies:

Now that you have your virtual environment set up, you can install the required Python libraries, including Boto3, within the isolated environment. First, make sure your virtual environment is active (you should see its name in the terminal prompt).

This command will install Boto3 and its dependencies into your virtual environment.

```markdown
pip3 install boto3
   ```

With these steps completed, your project should be set up with an isolated virtual environment and the necessary dependencies for working with AWS using Boto3.