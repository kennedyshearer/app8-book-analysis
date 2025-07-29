# 📚 Natural Language Processing eBook Analysis

A comprehensive collection of Jupyter notebooks demonstrating various Natural Language Processing (NLP) and text analysis techniques applied to "Miracle in the Andes" by Nando Parrado.

![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-3.8+-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🎯 Project Overview

This project serves as a practical introduction to text analysis, regular expressions, and NLP techniques using Python. The analysis is performed on "Miracle in the Andes," a gripping survival story about the 1972 Uruguayan Air Force Flight 571 crash in the Andes mountains. Through three comprehensive notebooks, you'll learn fundamental text processing techniques from basic string manipulation to advanced sentiment analysis.

## 📁 Repository Contents

### 📓 Notebooks

| Notebook | Description | Key Techniques |
|----------|-------------|----------------|
| **`Book_Analysis.ipynb`** | Basic text analysis using string methods and regular expressions | Chapter counting, word frequency, sentence extraction, regex patterns |
| **`Regex_Book.ipynb`** | Advanced regular expression techniques | Paragraph extraction, chapter title extraction, custom search functions |
| **`NLP-Book_Analysis.ipynb`** | Natural Language Processing analysis | Sentiment analysis, stopword filtering, NLTK integration |

### 📄 Data Files

- **`miracle_in_the_andes.txt`** - Complete text of "Miracle in the Andes" (459KB, 2,356 lines)

### ⚙️ Configuration

- **`.gitignore`** - Git ignore configuration for Python projects
- **`README.md`** - This documentation file

## ✨ Key Features

### 🔍 Text Analysis Capabilities
- **Word Frequency Analysis**: Count and rank the most frequently used words with statistical insights
- **Sentiment Analysis**: Analyze emotional tone at both book and chapter levels using NLTK's VADER
- **Pattern Matching**: Extract specific text patterns using advanced regular expressions
- **Chapter Analysis**: Break down the book into chapters for granular analysis
- **Custom Search Functions**: Find and count occurrences of any word or phrase

### 🛠️ Technologies Used
- **Python 3.7+**: Primary programming language
- **NLTK**: Natural Language Toolkit for advanced NLP operations
- **Regular Expressions (re)**: For pattern matching and text extraction
- **Jupyter Notebooks**: Interactive development and visualization environment

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7 or higher installed on your system.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kennedyshearer/app8-book-analysis.git
   cd app8-book-analysis
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install nltk jupyter matplotlib seaborn
   ```

4. **Download NLTK datasets**
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('vader_lexicon')
   nltk.download('punkt')
   ```

### 🏃‍♂️ Running the Analysis

1. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open any notebook**
   - Start with `Book_Analysis.ipynb` for basic concepts
   - Progress to `Regex_Book.ipynb` for pattern matching
   - Finish with `NLP-Book_Analysis.ipynb` for advanced NLP

3. **Run cells sequentially** to see the analysis results

## 📊 Analysis Results & Insights

The notebooks demonstrate various insights about "Miracle in the Andes":

- **📈 Most Common Words**: After filtering stop words, identify key themes and concepts
- **😊 Sentiment by Chapter**: Track the emotional journey throughout the survival story
- **🔍 Pattern Extraction**: Find specific themes, locations, or concepts mentioned in the text
- **📋 Statistical Analysis**: Word counts, chapter lengths, and frequency distributions
- **🎯 Custom Searches**: Interactive functions to explore specific vocabulary usage

### Sample Results
- **Total Chapters**: 10 chapters identified through regex pattern matching
- **Unique Words**: Thousands of unique words after preprocessing
- **Sentiment Trends**: Chapter-by-chapter emotional analysis revealing the story's arc

## 🎓 Educational Value

This project is perfect for:

- **📚 Learning NLP Fundamentals**: Understand core concepts through practical examples
- **🔤 Mastering Regular Expressions**: See regex in action with real-world text processing
- **🧠 Exploring Text Analysis Workflows**: Learn industry-standard approaches
- **🐍 Hands-on NLTK Experience**: Work with one of Python's most popular NLP libraries
- **📊 Understanding Sentiment Analysis**: Implement and interpret emotional text analysis
- **🔬 Data Science Portfolio**: Add a complete text analysis project to your portfolio

## 🔮 Future Enhancements

Potential areas for expansion:

- **🏷️ Named Entity Recognition (NER)**: Identify people, places, and organizations
- **📝 Topic Modeling**: Discover hidden themes using LDA or similar techniques
- **📚 Comparative Analysis**: Compare with other survival stories or literary works
- **📈 Advanced Visualizations**: Create interactive charts and word clouds
- **🧹 Enhanced Preprocessing**: Implement lemmatization and advanced text cleaning
- **🤖 Machine Learning**: Apply classification or clustering techniques
- **🌐 Web Interface**: Create a Flask/Streamlit app for interactive analysis

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions
- Add new analysis techniques
- Improve visualizations
- Apply methods to other texts
- Enhance documentation
- Add unit tests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Nando Parrado** - Author of "Miracle in the Andes"
- **NLTK Team** - For providing excellent NLP tools
- **Jupyter Project** - For the interactive notebook environment
- **Python Community** - For the amazing ecosystem of data science tools

## 📞 Contact

**Kennedy Shearer** - [GitHub Profile](https://github.com/kennedyshearer)

Project Link: [https://github.com/kennedyshearer/app8-book-analysis](https://github.com/kennedyshearer/app8-book-analysis)

---

⭐ **Star this repository if you found it helpful!** ⭐