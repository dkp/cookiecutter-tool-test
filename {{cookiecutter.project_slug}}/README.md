Author: {{ cookiecutter.full_name }} <{{ cookiecutter.email }}>   
Date Created: {% now 'local', '%Y-%m-%d' %}
Tool Test (Name and version): {{ cookiecutter.tool_name }}  
Dataset: {{ cookiecutter.dataset_description }}       
Download Tool from: {{ cookiecutter.tool_download_url }}  
Tool Documentation is available at: {{ cookiecutter.tool_documentation_url }}  Tool Description: {{ cookiecutter.tool_description }} 

----------------

# Project Structure

This is a project to test the software tool {{ cookiecutter.tool_name }}.
- **CHANGES.md** records the history.
- **HOWTO.md** will contain the Markdown evaluation and usage information for the tool.
- **TODO.md** contains a checklist of steps and explanations
- The **code** directory contains any test scripts and code
- The **data** directory contains **inputs** and **outputs**
- The **docs** directory contains documentation
- The **tutorials** directory contains tutorials
- **project_config**: source project_config to put the project code directory in the path. Add extra configuration here. 
