# 🐾 PetAid — Emergency First Aid Guide

A comprehensive, AI-powered emergency first aid guide for pets. Provides step-by-step instructions for 60+ pet emergency scenarios with real-time voice guidance using Web Speech API and Google Gemini.

## Features

✨ **60+ Emergency Scenarios**
- Life-threatening emergencies (choking, cardiac arrest, trauma)
- Toxin & ingestion emergencies (poisoning, swallowed objects)
- Neurological & respiratory emergencies
- Temperature-related emergencies
- Injury & wound care

🎙️ **Voice-Powered Guidance**
- Real-time voice input using Web Speech API
- AI-generated responses with Google Gemini 2.0 Flash
- Text-to-speech for hands-free guidance during emergencies
- Built-in fallback for browsers without API key

🧰 **Emergency Preparedness**
- Interactive first aid kit checklist (18 essential items)
- Saved vet contact management
- Pet health profile storage
- Emergency contact shortcuts

⏱️ **Real-Time Timer**
- Automatic timer on emergency guide screens
- Critical action tracking

📱 **Mobile-First Design**
- Responsive design for phones, tablets, and desktop
- Bottom navigation for easy thumb access
- Optimized for quick interactions during emergencies

## Project Structure

```
petaid/
├── frontend/
│   ├── index.html          # Main HTML structure
│   ├── styles.css          # All styling and animations
│   ├── script.js           # Core application logic
├── backend/                # Future backend expansion
├── package.json            # Project metadata
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

## Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/greeshmacreates/petaid.git
cd petaid
```

2. Open the app:
```bash
cd frontend
# Open index.html in your browser (or use a local server)
```

### Using Voice Features

To enable AI-powered voice guidance:

1. Get a free Gemini API key at [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Open PetAid and tap the "🔑 API Key" button when prompted
3. Paste your API key (stored locally in your browser only)
4. Start an emergency and tap 🎙️ Talk to ask questions

### Browser Requirements

- **Chrome/Chromium**: Full support (best for voice features)
- **Safari**: Works well
- **Firefox**: Supported
- **Edge**: Full support

## Emergency Categories

- **Life-Threatening** (Red) - Requires immediate vet attention
- **Urgent** (Orange) - Needs vet attention within hours
- **Moderate** (Green) - Monitor closely, plan vet visit

## Data Privacy

- All data is stored **locally in your browser** using localStorage
- No data is sent to servers except API calls to Google Gemini (when voice is enabled)
- API key is stored locally and never transmitted
- Clear data anytime from your browser settings

## Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Voice**: Web Speech API for recognition & synthesis
- **AI**: Google Generative AI (Gemini 2.0 Flash)
- **Storage**: Browser localStorage
- **Design**: Custom CSS with CSS Variables for theming

## Contributing

Found a bug or have a suggestion? Please open an issue or submit a pull request!

## License

MIT License - feel free to use for personal or commercial projects

## Disclaimer

⚠️ **PetAid is NOT a substitute for veterinary care.** This guide provides educational first aid information only. Always contact a licensed veterinarian as soon as possible during any pet emergency.

## Support

For questions or feedback, reach out or open an issue on GitHub.

---

**Made with ❤️ for pet owners everywhere. Stay prepared. Stay calm. Save lives.**
