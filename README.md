# 🎭 Poetic Personality Chatbot

An AI-powered chatbot that transforms ordinary messages into beautiful poetry using Google Gemini API and advanced prompt engineering techniques.

## ✨ Features

- **Real-time Poetry Generation**: Powered by Google Gemini API
- **Emotion Detection**: Automatically detects emotional context and responds appropriately
- **Multiple Poetry Styles**: Free verse, haiku, sonnet, limerick, and acrostic options
- **Typing Animation**: Immersive poetry presentation with realistic typing effects
- **Offline Mode**: Built-in simulation patterns when API is unavailable
- **Educational Mode**: Learn about prompt engineering techniques
- **Contextual Responses**: Analyzes themes like nature, work, family, and dreams

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)
1. Click the "Open In Colab" badge above
2. Run all cells in order
3. Follow the interactive setup wizard

### Option 2: Local Setup
1. Clone the repository
2. Install requirements
3. Run the notebook

## 📋 Requirements

### Python Libraries
```bash
pip install google-generativeai
```

### API Setup (FREE)
1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click "Create API Key" (completely FREE!)
4. Copy the generated key
5. No credit card required - 1,500 requests/day free!

## 🎯 Usage Guide

### Running the Chatbot

#### Method 1: Complete Interactive Experience
```python
main()
```

#### Method 2: Quick Demo
```python
quick_start_demo()
```

#### Method 3: Educational Mode
```python
educational_mode()
```

### Execution Modes

The chatbot offers three main modes:

1. **🌟 Google Gemini API Mode** (Recommended)
   - Real AI-powered poetry generation
   - 1,500 free requests per day
   - Higher quality, more creative responses
   - Contextual understanding

2. **🎭 Built-in Simulation Mode**
   - Works without internet connection
   - Uses pre-crafted poetry patterns
   - Instant responses
   - Good for testing and demos

3. **🧪 Demo Mode**
   - See examples without full chat
   - Test different emotions and themes
   - Perfect for understanding capabilities

## 📖 How to Use

### Step-by-Step Instructions

1. **Choose Your Mode**: When you run `main()`, select option 1, 2, or 3
2. **API Setup** (for option 1): Enter your free Gemini API key
3. **Start Chatting**: Type any message and watch it transform into poetry
4. **Special Commands**:
   - `quit`, `exit`, `bye` - End conversation
   - `stats` - View session statistics

### Example Interactions

**Input**: "I'm feeling happy today"
**Output**:
```
Sunlight spills like liquid gold, a river bright and free,
My heart, a lark, takes joyful flight, on wings of ecstasy.
The world unfolds in vibrant hues, a canvas fresh and new,
And happiness, a gentle bloom, forever shines anew.
```

**Input**: "Work has been stressful lately"
**Output**:
```
Through labor's field, your spirit grows,
Like gardens where the wisdom flows.
In daily tasks, find purpose true,
Each challenge shapes the best in you.
```

## 🛠️ Advanced Features

### Poetry Collection Generator
```python
create_poetry_collection()
```
Generates a themed collection of poems on various topics.

### Advanced Chatbot with Style Selection
```python
advanced_bot = AdvancedPoeticChatbot()
advanced_bot.set_poetry_style("haiku")
```

### Saving Poems
```python
advanced_bot.save_poem(poem_text, "My Beautiful Poem")
```

## 🔧 Troubleshooting

### Common Issues

#### ModuleNotFoundError: google.generativeai
**Solution**: 
```bash
!pip install google-generativeai
```
Then restart your runtime if in Colab.

#### API Key Not Working
**Solutions**:
- Check you're signed into the same Google account
- Generate a new API key from aistudio.google.com
- Make sure there are no extra spaces when copying
- Try setting the environment variable: `GEMINI_API_KEY`

#### Chat Interface Not Responding
**Solutions**:
- Make sure you're running the `chat_loop()` function
- Check if there are any error messages above
- Try restarting and running all cells again
- Use simulation mode (option 2) if API issues persist

### Verification Tools

#### Check Installation
```python
verify_installation()
```

#### Interactive Troubleshooting
```python
troubleshooting_guide()
```

## 📚 Educational Features

### Understanding Prompt Engineering
The chatbot demonstrates advanced prompt engineering techniques:

- **Role Definition**: Master poet with romantic wordsmith personality
- **Personality Modeling**: Specific style, rhythm, and thematic preferences
- **Emotional Context Detection**: Analyzes user input for emotional tone
- **Creative Constraints**: 2-4 lines with metaphorical depth
- **Output Format Specification**: Clean, formatted poetry responses

### Learning Mode
```python
educational_mode()
```
Shows the prompt engineering process step-by-step.

## 🎨 Emotion Detection

The chatbot recognizes and responds to various emotions:

- **Happy**: Joyful, uplifting, celebratory themes
- **Sad**: Gentle, comforting, hopeful responses
- **Love**: Tender, romantic, warm poetry
- **Excited**: Energetic, dynamic, inspiring verses
- **Peaceful**: Calm, serene, meditative expressions
- **General**: Thoughtful, reflective, meaningful responses

## 📁 File Structure

```
poetry_final.ipynb
├── Cell 1: Installation and Setup
├── Cell 2: Library Imports
├── Cell 3: Main PoeticChatbot Class
├── Cell 4: Testing and Demo Functions
├── Cell 5: Main Execution Interface
├── Cell 6: Quick Start Functions
├── Cell 7: Installation Verification
├── Cell 8: Advanced Features
└── Cell 9: Final Execution Cell
```

## 🌟 Key Components

### PoeticChatbot Class
- Main chatbot implementation
- Emotion detection algorithms
- API integration and fallback systems
- Poetry generation and formatting

### Advanced Features
- Multiple poetry styles
- Poem saving functionality
- Batch generation capabilities
- Educational explanations

### User Interface
- Interactive setup wizard
- Typing animations
- Session statistics
- Error handling and recovery

## 💡 Tips for Best Results

1. **Be Descriptive**: Share detailed thoughts and experiences
2. **Express Emotions**: The chatbot responds better to emotional content
3. **Try Different Themes**: Experiment with nature, relationships, work, dreams
4. **Use the API Mode**: Gemini API provides higher quality responses
5. **Save Your Favorites**: Use the advanced features to save poems you love

## 🤝 Contributing

This is an educational project demonstrating AI prompt engineering and poetry generation. Feel free to:
- Experiment with different prompt techniques
- Add new emotion categories
- Create new poetry styles
- Improve the user interface

## 📄 License

This project is for educational purposes. Please respect API usage limits and terms of service.

## 🆘 Support

If you encounter issues:
1. Run `verify_installation()` to check your setup
2. Use `troubleshooting_guide()` for interactive help
3. Try simulation mode as a fallback
4. Check the [Google AI Studio documentation](https://aistudio.google.com)

## 🌈 Enjoy Your Poetic Journey!

Transform your everyday thoughts into extraordinary verse with the power of AI and creativity!

---

*"Your words like whispers on the breeze, Stir thoughts among the swaying trees. In life's grand tapestry we weave, Each moment teaches us to believe."*
