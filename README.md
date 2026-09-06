# AI Call Agent

Standalone Android project for the AI Call Agent.

## Current milestone

- Basic Compose UI
- Phone number input
- Reason/instructions input
- Supported Android dialer launch
- Initial architecture ready for contact lookup, speech recognition, AI conversation, TTS, and call-state handling

## Planned modules

- ContactResolver
- CallManager
- SpeechRecognizer
- ConversationEngine
- TextToSpeechEngine
- ConversationState
- CallSummary

The first version intentionally opens Android's supported calling interface instead of silently taking over calls. Autonomous calling/conversation requires additional Android telecom capabilities and platform-specific handling.
