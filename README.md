# 🎃 Pumpki - Your Breathing Buddy

A beautiful, neurodivergent-friendly companion for breathing exercises and self-regulation with brain science education. Built with accessibility, compassion, and evidence-based techniques at its core.

![Burnt Orange Ember Theme](https://img.shields.io/badge/theme-burnt_orange-d87449)
![No Dependencies](https://img.shields.io/badge/dependencies-none-success)
![Privacy First](https://img.shields.io/badge/privacy-local_storage_only-blue)
![Accessibility](https://img.shields.io/badge/accessibility-WCAG_friendly-green)

## ✨ Features

### 🫁 Guided Breathing Exercises
- **Box Breathing (4-4-4-4)** - Balance & Focus
- **Calming Breath (4-6)** - Anxiety & Overwhelm
- **Energizing Breath (6-4)** - Low Energy States

Visual breathing guide with Pumpki, an animated pumpkin companion that breathes with you. Optional gentle audio cues with extra-soft hold sounds for sensitive ears.

### 🧘 Body Scan & Check-In
- Interactive body diagram to track physical sensations
- Guided body scan with step-by-step instructions
- Quick check mode for rapid assessment
- Sensation tagging system (warm, cool, tight, relaxed, etc.)
- Save and track body states over time

### 😊 Mood & Arousal Tracking
- 5-level arousal state tracker (Very Calm → Overwhelmed)
- Automatic breathing pattern recommendations based on current state
- Weekly mood visualization chart
- Pattern recognition over time

### 📊 Progress & History
- Track breathing sessions with duration and cycle count
- Body check-in history
- Streak tracking for consistency
- Total minutes practiced
- Exportable data for backup or analysis

### 🚨 Emergency Mode
- Quick access to crisis breathing techniques
- 5-4-3-2-1 Grounding exercise
- Cold water technique instructions
- Safe space guidance
- Clear, compassionate messaging

### 🎨 Design & Accessibility
- **Burnt Orange Ember Theme** - Warm, cozy, sophisticated dark aesthetic
- **High Contrast Mode** - For visual accessibility
- **Reduced Motion Mode** - For vestibular/motion sensitivity
- **Audio Controls** - Toggle sound on/off
- **Glassmorphism UI** - Modern, elegant interface with backdrop blur
- **Responsive Design** - Works on desktop, tablet, and mobile

### 🧠 Brain Science Tips
Educational neuroscience facts integrated throughout:
- How breathing affects the vagus nerve
- Understanding the amygdala and stress response
- Neuroplasticity and habit formation
- Interoception and body awareness

## 🚀 Getting Started

### Installation

1. **Download the HTML file** - Pumpki is a single-file application
2. **Open in your browser** - Just double-click the HTML file
3. **Bookmark it** - Add to your favorites for quick access

That's it! No server, no installation, no dependencies.

### First Use

1. **Select your current mood** on the arousal scale
2. **Choose a breathing pattern** - Pumpki will recommend one based on your mood
3. **Click "Start Breathing"** - Follow along with visual and audio cues
4. **Try a body scan** - Tap body parts to indicate how they feel
5. **Check your progress** - View stats and history in the My Progress tab

## 📱 Usage Tips

### For Best Results
- Use in a quiet, comfortable space
- Wear headphones for the best audio experience
- Practice daily for 5-10 minutes
- Track your progress to see patterns
- Use emergency mode when feeling overwhelmed

### Recommended Patterns
- **Morning** - Energizing Breath (6-4)
- **Work/Study** - Box Breathing (4-4-4-4)
- **Evening/Anxiety** - Calming Breath (4-6)
- **Crisis** - Extended Calming Breath

## 🔐 Privacy & Data

### Your Data Stays Local
- **All data stored locally** in your browser (IndexedDB)
- **No tracking or analytics**
- **No account required**
- **No data sent to servers**
- **Export anytime** - Download your data as JSON
- **Import anywhere** - Restore from backup files

### Data Management
- Export data for backup
- Import previous backups
- Clear old data (30+ days)
- Delete individual entries
- Complete data portability

## 🛠️ Technical Details

### Built With
- **Pure HTML/CSS/JavaScript** - No frameworks
- **Canvas API** - For Pumpki animation
- **Web Audio API** - For breathing cues
- **IndexedDB** - For local data storage
- **CSS Custom Properties** - For theming
- **Responsive Grid/Flexbox** - For layout

### Browser Compatibility
- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Single file** - ~50KB uncompressed
- **No external dependencies**
- **Instant load time**
- **Minimal battery impact**
- **Works offline** after first load

## 🎨 Design System

### Color Palette
```css
Primary Orange: #d87449
Orange Light:   #e88b5d
Orange Dark:    #bf5830
Warm Amber:     #e8a870
Sage Green:     #7a8f65
Calm Blue:      #7a8f9d
Warm Yellow:    #d8b870
```

### Typography
- **Headings**: Poppins (Google Fonts)
- **Body**: Inter (Google Fonts)
- **Weights**: 300-700 for hierarchy

### Layout
- **Border Radius**: 24px (large), 16px (small)
- **Shadows**: Warm brown undertones
- **Transitions**: Cubic bezier easing
- **Backdrop Blur**: 16px for glass effect

## ♿ Accessibility Features

### Visual
- High contrast mode toggle
- Large, clear typography
- Color-blind friendly status indicators
- Sufficient color contrast ratios (WCAG AA)

### Motion
- Reduced motion mode
- Respects `prefers-reduced-motion` media query
- Static alternatives for animations

### Audio
- Audio can be toggled off
- Visual cues work independently
- No audio-only information

### Interaction
- Keyboard navigable
- Large touch targets (44px minimum)
- Clear focus indicators
- No time limits on interactions

## 🧩 Feature Breakdown

### Breathing Module
- **3 breathing patterns** with customizable durations
- **Audio cues** with phase-specific tones
- **Visual animation** synced to breathing
- **Cycle tracking** for session depth
- **Duration tracking** for statistics

### Body Scan Module
- **Interactive SVG body diagram**
- **3 state system**: Comfortable, Neutral, Tense
- **Guided scan mode** with 10 body areas
- **Quick check mode** for rapid assessment
- **10 sensation tags** for detailed tracking

### History Module
- **4 statistics cards**: Sessions, Body Checks, Streak, Minutes
- **7-day mood chart** with emoji visualization
- **Entry list** with filtering (All, Breathing, Body Checks, Mood)
- **Entry details** with timestamps and metadata
- **Delete functionality** for individual entries

### Emergency Module
- **Crisis breathing** - Immediate calming technique
- **Grounding exercises** - 5-4-3-2-1 sensory awareness
- **Physical techniques** - Cold water reset
- **Safe space guidance** - Step-by-step comfort
- **Educational content** - Understanding stress responses

## 🤝 Contributing

This is a single-file educational project. Contributions welcome via:
1. Fork the repository
2. Make your changes
3. Test thoroughly across browsers
4. Submit a pull request

### Areas for Contribution
- Additional breathing patterns
- More body scan variations
- Internationalization/translations
- Additional accessibility features
- Bug fixes and optimizations

## 📄 License

This project is provided as-is for personal use and education. Feel free to use, modify, and share.

## 🙏 Credits

### Design Inspiration
- **Daily Compass** - Design system and aesthetic inspiration
- **Neuroscience Research** - Evidence-based breathing techniques
- **Accessibility Guidelines** - WCAG 2.1 standards

### Fonts
- [Inter](https://fonts.google.com/specimen/Inter) by Rasmus Andersson
- [Poppins](https://fonts.google.com/specimen/Poppins) by Indian Type Foundry

### Built With Love For
- People with ADHD, autism, anxiety, and other neurodivergent experiences
- Anyone learning self-regulation skills
- Individuals practicing mindfulness and body awareness
- People seeking evidence-based mental health tools

## 📞 Support & Feedback

This tool is designed to complement, not replace, professional mental health support. If you're in crisis:
- 988 Suicide & Crisis Lifeline (US): Call or text 988
- Crisis Text Line: Text HOME to 741741
- International Association for Suicide Prevention: https://www.iasp.info/resources/Crisis_Centres/

---

**Made with 🧡 for neurodivergent brains everywhere**

*Remember: Your nervous system is doing its best. Be gentle with yourself.* 🎃
