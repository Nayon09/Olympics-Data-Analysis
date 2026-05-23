# Contributing to Olympics Data Analysis

First off, thank you for considering contributing to the Olympics Data Analysis project! It's people like you that make this project such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps which reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**
* **Include your environment details** (OS, Python version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. Create an issue and provide the following information:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Describe the current behavior and the expected behavior**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Follow the Python styleguides
* Include appropriate test cases
* End all files with a newline
* Avoid platform-dependent code

## Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/Olympics-Data-Analysis.git
   cd Olympics-Data-Analysis
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   pip install -r requirements-dev.txt  # Additional development dependencies
   ```

5. Create a branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
  - 🎨 `:art:` when improving the format/structure of the code
  - 🐛 `:bug:` when fixing a bug
  - ✨ `:sparkles:` when introducing new features
  - 📚 `:books:` when writing docs
  - 🔧 `:wrench:` when fixing configuration files
  - 📦 `:package:` when updating dependencies

### Python Styleguide

All Python code should adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/).

* Use 4 spaces for indentation
* Use descriptive variable names
* Write docstrings for all functions and classes
* Comment complex logic
* Keep functions focused and small

Example:
```python
def fetch_medal_tally(df, year, country):
    """
    Fetch medal tally based on year and country filters.
    
    Parameters:
    -----------
    df : pandas.DataFrame
        The main Olympics dataset
    year : str
        'Overall' for all years, or specific year as string
    country : str
        'Overall' for all countries, or specific country name
        
    Returns:
    --------
    pandas.DataFrame
        Dataframe with medal counts
    """
    # Implementation
    pass
```

### Markdown Styleguide

* Use markdown for all documentation
* Use proper headers hierarchy
* Include code examples where helpful
* Link to external resources when appropriate

## Additional Notes

### Issue and Pull Request Labels

* `bug` - Something isn't working
* `enhancement` - New feature or request
* `documentation` - Improvements or additions to documentation
* `good first issue` - Good for newcomers
* `help wanted` - Extra attention is needed
* `question` - Further information is requested

### Running Tests

```bash
python -m pytest
```

### Building Documentation

```bash
# If applicable
sphinx-build -b html docs docs/_build
```

## Recognition

Contributors will be recognized in:
* The README.md file
* GitHub's contributor page
* Release notes

## Questions?

Feel free to open an issue with the question label, or reach out via:
* GitHub Discussions
* Email: [your-email]

Thank you for contributing! 🎉
