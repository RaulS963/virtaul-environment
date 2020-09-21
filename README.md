# virtual-environment

## Creating a virtual environment

The following command creates a virtual environment (directory)
  ```python
  > python -m venv your_virtual_env_dir_name  
  ```

To start the virtual environment goto your virtual env dir and type the following command
  ```python
  your_virtual_env_dir_name> scripts\activate.bat
  ```

Once the virtual environment starts you'll get something like:
  ```python
  (env_name) ..\..\path> 
  ```

  ```python
  (env_name) ..\..\path> pip list
  (env_name) ..\..\path> pip ..some other commands
  ```
To deactivate:
  ```python
  (env_name) ..\..\path> deactivate
  ```
