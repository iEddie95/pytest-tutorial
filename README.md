# pytest-tutorial

This is a solution for the Python + GitHub Actions Exercise 
1. At first the flow couldn't start, because there was a syntax mistake in line 6 on python-package.yml
  on:[pushes] -> on: push
2. flake8 failed with linting issues because there was blank whitespace in several lines in files: wallet.py and wallet_test.py.
3. Added 'Test with pytest' with verbose output.
4. Added 'Build package before publishing it to the requested repository using Twine.

In this assignment, I learned how to use GitHub actions and workflows, GitHub secrtest for credentials, test Python code with pytest and publish the package to another repository.  
