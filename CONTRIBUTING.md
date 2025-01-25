# Contributing to MsingiAI's Language Tokenizers Repository  

Thank you for your interest in contributing to the **MsingiAI Language Tokenizers Repository**! We aim to build open-source tools and resources for African language processing. Whether you’re a developer, linguist, or researcher, your contributions can help us make a significant impact.  

## How You Can Contribute  

### 1. 🛠️ Code Contributions  
We welcome code contributions for:  
- **New Tokenizers**: Build tokenizers for underrepresented African languages.  
- **Improved Tokenization**: Optimize existing tokenizers for efficiency or accuracy.  
- **Support for Scripts**: Add support for languages using non-Latin scripts (e.g., Amharic, Tifinagh).  
- **Code-Switching**: Improve tokenizers to handle code-switched text.  

### 2. 📚 Documentation  
- Write clear documentation for new or existing tokenizers.  
- Add usage examples for tokenizers in the repository.  
- Translate documentation into multiple African languages if possible.  

### 3. 📊 Dataset Contributions  
- Contribute raw or preprocessed text data for African languages.  
- Share datasets for tokenization benchmarks and evaluations.  
- Ensure the data is publicly available and ethically sourced.  

### 4. 🧪 Testing and Benchmarks  
- Create or improve benchmark scripts for evaluating tokenizers.  
- Test tokenizers with diverse datasets to ensure robustness.  

### 5. 🤝 Community Engagement  
- Share ideas, feedback, or challenges in the [Discussions](https://github.com/your-repo/discussions) section.  
- Help others in the community by answering questions or reviewing pull requests.  

## Contribution Workflow  

### Step 1: Fork the Repository  
1. Click on the “Fork” button in the top-right corner of the repository.  
2. Clone your fork to your local machine:  
   ```bash  
   git clone https://github.com/your-username/language-tokenizers.git  
   cd language-tokenizers  
   ```  

### Step 2: Create a Branch  
Create a branch for your feature or fix:  
```bash  
git checkout -b feature/your-feature-name  
```  

### Step 3: Make Changes  
- Add your changes or new files to the appropriate directory.  
- Follow the [Coding Standards](#coding-standards) below.  

### Step 4: Test Your Changes  
Run the test suite to ensure your changes don’t break anything:  
```bash  
python -m unittest discover tests  
```  

### Step 5: Commit and Push  
1. Commit your changes with a clear message:  
   ```bash  
   git add .  
   git commit -m "Add tokenizer for Yoruba language"  
   ```  
2. Push the changes to your branch:  
   ```bash  
   git push origin feature/your-feature-name  
   ```  

### Step 6: Open a Pull Request  
1. Go to the original repository on GitHub.  
2. Click the “Compare & Pull Request” button.  
3. Fill out the PR template and submit your request for review.  

## Coding Standards  

- **Python Version**: Use Python 3.8 or later.  
- **Libraries**: Prefer widely-used libraries like `tokenizers`, `nltk`, or `spacy` unless there’s a specific need.  
- **Style Guide**: Follow [PEP 8](https://peps.python.org/pep-0008/). We recommend using `black` for formatting.  
- **Directory Structure**:  
   - **`src/`**: Core tokenizer implementations.  
   - **`tests/`**: Unit tests for tokenizers.  
   - **`docs/`**: Documentation files.  

## Code of Conduct  

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a welcoming environment for all contributors.  

## License  

By contributing to this repository, you agree that your contributions will be licensed under the repository’s [LICENSE](LICENSE).  

## Need Help?  

If you’re stuck or have questions:  
- Open an issue [here](https://github.com/Msingi-AI/MsingiAI-Tokenizers/issues).  
- Join our [Discussion forum](https://github.com/MsingiAI-Tokenizers/discussions).  

We’re excited to collaborate with you to build impactful tools for African NLP. Let’s make it happen! 🚀  
