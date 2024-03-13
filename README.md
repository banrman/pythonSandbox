# pythonSandbox


# Installation

python3 --version
https://www.python.org/downloads/
python3 -m venv .venv
Active - source .venv/Scripts/activate
Deactivate - just type deactivate

## What's the point of a virtual environment?

Virtual environments in Python are used to create isolated environments for Python projects. Here are some key points about why virtual environments are useful:

1. **Dependency Isolation**: Virtual environments allow you to install Python packages and dependencies specific to a project without affecting other projects or the system Python installation. This helps prevent conflicts between different versions of packages that different projects may require.

2. **Version Management**: Virtual environments make it easy to manage different versions of Python for different projects. You can create a virtual environment with a specific version of Python and install packages that are compatible with that version.

3. **Reproducibility**: Virtual environments help ensure that your project is reproducible by capturing the exact versions of Python and packages used. This is important for sharing your code with others or deploying it to different environments.

4. **Sandboxing**: Virtual environments provide a sandboxed environment for your project, which means that any changes made to the environment (e.g., installing or upgrading packages) are isolated and do not affect other projects or the system.

5. **Cleanup**: Virtual environments make it easy to clean up dependencies when you no longer need them. You can simply delete the virtual environment directory to remove all installed packages and dependencies.

Overall, virtual environments are a valuable tool for managing dependencies, isolating projects, and ensuring reproducibility in Python development.

---

Let me know if you need any further clarification or information!