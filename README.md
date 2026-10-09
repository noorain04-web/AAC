# HearLink AAC — Adult Aphasia

An adaptable, mobile-first Hindi/English AAC prototype for adults with aphasia. It is designed to support both people who benefit from immediate ready-made messages and people who need help building and editing longer messages.

## Features

- Persistent essential-message buttons (help, stop, yes/no, pain, toilet, water, time, repeat, call family).
- Topic grids for home, food and drink, personal care, relationships/conversation, feelings, health, travel, choices, and social topics/opinions.
- Two pathways: **Quick messages** (tap to speak) and **Conversation builder** (sentence starters and connector/question words, removable message components, typed text, editing and review).
- Bilingual Hindi/English labels and speech-language selection.
- Personal cards with custom labels, symbols and spoken messages.
- Locally saved messages, selectable installed device voice, adjustable speech rate, text/button size preferences, and responsive layout.
- Offline shell through a service worker.

## GitHub Pages setup

1. Open **Settings → Pages**.
2. Select deployment from the `main` branch and `/ (root)`.
3. Open the HTTPS URL on the intended phone/tablet.
4. Test the actual voice, Hindi text rendering, taps, personal vocabulary and stored messages on the target device.

## Important limitations and safety

- This is a **prototype**, not a validated clinical AAC product and not a diagnostic or treatment tool. Vocabulary, translations, button layout and symbol interpretations need review with the adult user and, where appropriate, a speech-language therapist and communication partners.
- Speech uses voices installed on the device/browser. Install or enable a Hindi voice if needed; voice quality and language availability differ by device.
- A browser app cannot guarantee Bluetooth hearing-aid, headphone, or external PA routing.
- The app does not call emergency services or caregivers. Keep another way to request urgent help.
- Personal cards and saved messages are stored in local browser storage on the current device. Clearing browser/site data can erase them. Avoid entering sensitive information on shared devices.
- Emoji are placeholders, not the project’s 1,055 IDC symbol collection. Add only images you have permission to use and redistribute.
- Conversation builder assembles selected chunks of text; it does not infer grammar or guarantee that the selected pieces form a natural sentence. Users can edit the final message before speaking.

## Suggested evaluation before clinical use

Co-design with adults with different aphasia profiles. Check whether users can communicate their intended message, understand the symbol-card mapping, navigate without excessive effort, personalize vocabulary, use the app in real contexts, and access a reliable voice. Include communication partners in testing. Do not claim clinical efficacy without appropriate evaluation.
