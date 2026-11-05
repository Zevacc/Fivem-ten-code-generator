# Fivem-ten-code-generator
# 📻 ten-code

![HTML](https://img.shields.io/badge/HTML-single%20file-e34c26) ![Made with AI](https://img.shields.io/badge/made%20with-Claude%20AI-8a63d2) ![No install](https://img.shields.io/badge/install-none-brightgreen)

A fast, minimal radio message generator for police, sheriff, EMS and fire units. Pick a scenario, fill in a few details, and get a ready-to-send radio line built with standard 10-codes.

```
2P34 10-80, 2P34 in pursuit of suspect, Black Ford, plate ABC123, northbound, at [1064] N HWY Overpass
```

It is a single HTML file. No install, no build step, no account.

## ✨ Features

- **Sign in with your radio code.** Type `234` and pick your department. The department letter is added automatically: `2P34` for Police, `2S34` for Sheriff, `2E34` for EMS, `2F34` for Fire. For a multi-digit zone, separate it with a space or dash, like `12-34`.
- **Scenarios by category.** Traffic, Crime, Help, Status and Fire. Each scenario asks only for the details it needs (plate, color, make, direction, location, suspect description, injuries).
- **Quick fill.** Tap a preset for colors, makes, directions and common locations. Values carry over when you switch scenarios, so a plate you typed once is reused.
- **Auto copy.** The generated message is copied to the clipboard right away.
- **Auto speak.** The message is read aloud in English, with the call sign spelled in the phonetic alphabet (2P34 becomes "two papa three four") and plates read letter by letter.
- **Voice input.** Tap **Say location** to speak a location and get the message instantly, or use the microphone next to any field to dictate it.
- **Switches.** Auto copy and auto speak can each be turned off. Your choice is remembered.
- **10-code reference.** A searchable list of common codes (APCO), tucked away until you need it.
- **Light and dark mode** that follow your system setting.

## 🚀 Usage

1. Download `emergency-radio.html`.
2. Open it in a browser. Chrome or Edge is recommended.
3. Enter your radio code and choose your department.
4. Pick a category and scenario, fill in the fields, and press **Generate** (or press Enter).

## 📋 Scenarios

| Category | Scenarios |
| --- | --- |
| Traffic | Traffic stop, Plate check, Driver check, Accident, Hit and run, DUI |
| Crime | Pursuit, Armed suspect, In custody, Crime in progress |
| Help | Emergency, Need backup, Ambulance, My location |
| Status | Start shift, In service, Out of service, On scene, Done |
| Fire | Fire alarm, Fire update |

## 🌐 Browser support

| Feature | Chrome / Edge | Firefox / Safari |
| --- | --- | --- |
| Message generation, copy | Yes | Yes |
| Speaking messages aloud | Yes | Mostly |
| Voice input (microphone) | Yes | Limited or unavailable |

Voice input asks for microphone permission the first time you use it.

## 🛠️ Customizing

Everything lives in `emergency-radio.html`:

- **Scenarios and message templates:** the `CATS` object.
- **Quick-fill presets:** the `QF` object.
- **Department letters:** the `LET` object.
- **10-code reference list:** the `CODES` array.

## 📝 Notes

This tool is meant for roleplay, training and simulation. It is not connected to any real dispatch system. The 10-codes follow the APCO list, and meanings differ between agencies, so adjust the templates to match yours.

## 🤖 Built with AI

This project was made with the help of AI. The code and this README were written by [Claude](https://claude.ai) (Anthropic) from my instructions, and I directed the design, features and wording. AI-written code can contain mistakes, so test it before relying on it and feel free to open an issue or a pull request.
