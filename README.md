# Flashy
### Flashy is a lightweight, mobile-friendly flashcard study application designed for quick reviews, active recall, and efficient learning. It features a clean interface, dark mode, and easy customization — all hosted on GitHub Pages.  

## 🚀 Features  

### Study Modes  
- **Practice Mode**: Study at your own pace  
- **Timed Mode**: Add a countdown for exam-style practice  
- **Review Mode**: Focus on missed or flagged questions  

### Smart Learning Features  
- **Interactive Flashcards**: Flip cards with questions and answers  
- **Shuffle Mode**: Randomize order for better retention  
- **Progress Tracking**: Track correct/incorrect answers  
- **Hints**: Optional hints for tough questions  
- **Mark for Review**: Flag cards for later  

### Admin Panel  
- **Password Protected**: Simple admin login  
- **Card Management**: Add, edit, or delete flashcards  
- **Categories**: Organize cards by subjects or topics  
- **Export**: Download your flashcard sets as JSON  

### Mobile Optimization  
- **Responsive Design**: Works well on phones, tablets, and desktops  
- **Touch Gestures**: Swipe and tap for navigation  
- **PWA Support**: Install as a mobile app for offline use  
- **Dark Mode**: Optimized for late-night studying  

## 📚 Supported Use Cases  
- Exam prep  
- Class review  
- Language learning  
- Memorization practice  
- Personal knowledge building  

## 🛠️ Installation & Setup  

### GitHub Pages Hosting  
1. **Fork/Clone this repository**  
2. Add your files:  
   - `index.html` (main app)  
   - `sw.js` (for offline support)  
   - `manifest.json` (PWA config)  
3. Enable GitHub Pages in repo settings  
4. Access your app at:  
   - `https://yourusername.github.io/flashy/`  

### File Structure  
flashy/
├── index.html # Main application
├── sw.js # Service worker
├── manifest.json # PWA manifest
└── README.md # This file


### Admin Access  
- **Default Password**: `admin123`  
- **Change It**: Update `adminPassword` in JavaScript  

## 🎨 Design Features  
- **Minimalist UI** for distraction-free learning  
- **Dark/Light Mode** toggle  
- **Smooth animations** for card flips  
- **Responsive typography** for readability  

## ⚡ Performance Features  
- **Local Storage**: Saves progress in browser  
- **Offline Ready**: Works without internet (via PWA)  
- **Lightweight**: Minimal dependencies  
- **Fast Loading**: Optimized for quick access  

## 🔒 Security Notes  
- Admin password stored in client-side code  
- For personal use only (not secure for sensitive data)  

## 🤝 Contributing  
Contributions are welcome!  
- Add more features  
- Improve UI/UX  
- Optimize performance  
- Enhance documentation  

## 📄 License  
This project is open source and available under the MIT License.  

## 🎯 Study Tips  
1. Practice daily for better retention  
2. Shuffle cards to avoid memorizing order  
3. Use timed mode to simulate pressure  
4. Review mistakes — they’re your best teacher  
5. Take breaks to avoid burnout  
"""

# Save to file
file_path = "/mnt/data/README.md"
with open(file_path, "w") as f:
    f.write(content)

file_path


