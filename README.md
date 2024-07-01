# HomebrewAI-V2
Repository for HomebrewAI vervigion 2.

```sh
# Create directories
mkdir -p src bin lib docs tests

# Create initial files
echo -e "def main():\n    print('Welcome to HomebrewAI-V2')" > src/main.py
echo -e "__version__ = '0.1.0'" > src/__init__.py
echo -e "import unittest\n\n\nclass TestMain(unittest.TestCase):\n    def test_main(self):\n        self.assertEqual(1, 1)" > tests/test_main.py
echo -e "__version__ = '0.1.0'" > tests/__init__.py

# Initialize git and make first commit
git init
git add .
git commit -m "Initial project structure and basic files"

# Result
This will be the structure for [HomebrewAI-V2](https://github.com/Da-Coder-Jr/Homebrewai-V2).

```
