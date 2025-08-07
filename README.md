# Darija Translator 🇲🇦

An AI-powered translator specifically designed for Moroccan Darija (Moroccan Arabic). This tool provides accurate translations between Darija and other languages including Arabic, English, and French, focusing on contextual meaning rather than literal word-by-word translation.

## 🌟 Features

- **Contextual Translation**: Translates by meaning, not word-for-word (e.g., "زيد نقص" → "decrease more" not "add less")
- **Darija-Focused**: Specialized in Moroccan Arabic with cultural context understanding
- **Multi-language Support**: Translates between Darija and:
  - 🇸🇦 Modern Standard Arabic (العربية الفصحى)
  - 🇺🇸 English
  - 🇫🇷 French
- **Clean Output**: Returns only the translation without explanations
- **Interactive Web Interface**: User-friendly Gradio interface
- **Bidirectional Translation**: Supports both directions (Darija ↔ Other Languages)

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/darija-translator.git
   cd darija-translator
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the project root:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Run the application**
   ```bash
   jupyter notebook darjia_translator.ipynb
   ```
   
   Or convert to Python and run directly:
   ```bash
   jupyter nbconvert --to python darjia_translator.ipynb
   python darjia_translator.py
   ```

## 📖 Usage

1. **Start the application** - The Gradio interface will launch automatically
2. **Access the translator** at `http://127.0.0.1:7866` (or the displayed URL)
3. **Enter your text** in the input field
4. **Select source and target languages**
5. **Click "Translate"** to get your translation

### Example Translations

| Input (Darija) | Output (English) |
|----------------|------------------|
| "Bghit nakul" | "I want to eat" |
| "Kifach ndir had shi?" | "How do I do this thing?" |
| "Safi, bslama" | "Okay, goodbye" |

| Input (English) | Output (Darija) |
|----------------|------------------|
| "I want to eat" | "بغيت الناكل" |
| "How are you?" | "كيف داير؟" |
| "Thank you very much" | "الله يعطيك الصحة" |

## 🏗️ Project Structure

```
darija-translator/
├── darjia_translator.ipynb       # Main Jupyter notebook
├── .env                         # Environment variables (create this)
├── requirements.txt             # Python dependencies
└── README.md                   # Project documentation
```

## 🤖 Translation Features

### Contextual Understanding
- **Idiomatic Expressions**: Correctly translates Darija idioms and expressions
- **Cultural Context**: Maintains cultural nuances in translations
- **Colloquial Speech**: Handles informal Darija speech patterns

### Language Pairs Supported
- **Darija ↔ English**: Bidirectional translation
- **Darija ↔ Arabic**: Modern Standard Arabic support
- **Darija ↔ French**: French language support
- **Smart Detection**: Automatic handling of mixed Arabic/Latin script

## 🛠️ Technical Details

- **AI Model**: OpenAI GPT-4o-mini
- **Interface**: Gradio web interface
- **Translation Method**: Contextual meaning-based translation
- **Script Support**: Both Arabic and Latin scripts for Darija
- **Response Format**: Clean translation output without explanations

## 🔧 Configuration

The system prompt is optimized for Darija translation with these key features:

- Meaning-based translation (not literal)
- Clean output without explanations
- Support for both Arabic and Latin script Darija
- Cultural context preservation

## 📱 Interface Features

- **Dual-column Layout**: Clear input/output separation
- **Language Dropdowns**: Easy language selection
- **Example Translations**: Pre-loaded examples to try
- **Clear Function**: Reset input and output
- **Responsive Design**: Works on desktop and mobile

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

### Areas for Contribution
- Additional example translations
- UI/UX improvements
- Performance optimizations
- Support for more Darija dialects
- Batch translation features

## 🎯 Use Cases

- **Language Learning**: Learn Darija or practice other languages
- **Communication**: Bridge language gaps in conversations
- **Content Translation**: Translate social media posts, messages
- **Cultural Exchange**: Understand Moroccan expressions and idioms
- **Travel**: Navigate Morocco with better language understanding

## ⚠️ Important Notes

- **Contextual Translation**: This tool prioritizes meaning over literal translation
- **Darija Variations**: Focuses on general Moroccan Darija (may vary by region)
- **Script Support**: Accepts both Arabic script (العربية) and Latin script
- **Clean Output**: Returns only translations without explanations or analysis

## 🌍 Language Support Details

### Darija (الدارجة المغربية)
- Both Arabic and Latin script input
- Regional expressions and idioms
- Colloquial speech patterns
- Cultural context preservation

### Arabic (العربية الفصحى)
- Modern Standard Arabic
- Formal and informal registers
- Classical expressions

### English
- American and British English
- Colloquial expressions
- Formal and informal language

### French (Français)
- Metropolitan French
- Common in Moroccan context
- Formal and informal registers

## 🙏 Acknowledgments

- OpenAI for providing the GPT-4o-mini model
- Gradio team for the excellent web interface framework
- The Moroccan community for cultural and linguistic insights
- Contributors to Darija language preservation efforts

## 📞 Support

- **Technical Issues**: Open an issue on GitHub
- **Translation Questions**: Check the examples or create a discussion
- **Feature Requests**: Submit an issue with the enhancement label

---

**Made with ❤️ to bridge language barriers and preserve Moroccan Darija**

*"الدارجة المغربية - لغة القلب والوطن"*
