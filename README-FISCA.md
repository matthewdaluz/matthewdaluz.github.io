# Fisca - Transaction and Income Tracker

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)
[![Offline](https://img.shields.io/badge/Mode-Offline%20Only-orange.svg)]()

Fisca is a **Canada-only**, **offline-only** Android application designed to help ODSP (Ontario Disability Support Program) recipients manually log transactions and income for easier tax filing and income reporting.

## 🎯 Purpose

Fisca helps people with ODSP or DSO in Ontario by:
- **Tracking all transactions** with detailed information (date, price, GST/HST, total, category, payment method)
- **Recording ODSP income** including regular payments, DSO payments, and additional support
- **Organizing financial data** for easier tax filing and income reporting
- **Maintaining privacy** - all data stays on your device (no internet connection required or used)

## ✨ Features

### Transaction Logging
Record every purchase with:
- **Date of purchase**
- **Item/service description**
- **Price before tax**
- **GST/HST amount** (Ontario's 13% HST)
- **Total price** (including tax)
- **Transaction category** (Groceries, Medical, Housing, Utilities, Transportation, etc.)
- **Payment method** (Cash, Debit, Credit, ODSP Card, Cheque, etc.)
- **Additional notes**

### ODSP Income Tracking
Log various types of income:
- Regular ODSP monthly payments
- DSO (Disability Support Ontario) payments
- Additional support payments
- Other reportable income

### Reports and Summaries
- View transaction history
- Categorize spending
- Track income over time
- Generate summaries for tax filing

## 🔒 Privacy & Security

- **100% Offline**: No internet permissions, no data leaves your device
- **Local Storage**: All data stored securely on your Android device
- **No Accounts**: No sign-up, no login, no personal information collected
- **Your Data, Your Control**: Export and backup your data at any time

## 🇨🇦 Canada-Specific Features

This app is designed specifically for Ontario, Canada:
- HST calculations (13% for Ontario)
- ODSP/DSO income categories
- Compliant with Canadian tax reporting requirements
- Categories relevant to Ontario residents

## 📱 Requirements

- Android 8.0 (API 26) or higher
- No internet connection required
- Minimal storage space

## 🛠️ Building from Source

```bash
# Clone the repository
git clone https://github.com/matthewdaluz/fisca.git
cd fisca

# Build the matthewdaluz.app.fisca
./gradlew assembleDebug

# Install on connected device
./gradlew installDebug
```

## 📄 License

This program is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License v3.0** as published by the Free Software Foundation.

```
Fisca - Transaction and Income Tracking for ODSP Recipients
Copyright (C) 2024 Matthew Daluz

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

See [LICENSE](LICENSE) file for full license text.

## 🤝 Contributing

Contributions are welcome! Since this app is designed for ODSP recipients in Ontario, please ensure any contributions:
- Maintain offline-only functionality (no network calls)
- Are relevant to Canadian/Ontario tax and benefit systems
- Follow the GNU GPLv3 license requirements
- Respect user privacy and data security

## 📧 Contact

For questions, issues, or suggestions, please open an issue on GitHub.

## ⚠️ Disclaimer

This app is provided as-is for personal financial tracking. It is not a substitute for professional financial or tax advice. Always consult with a qualified tax professional or financial advisor for specific guidance on your situation.

## 🗺️ Roadmap

- [x] Basic project structure
- [x] Transaction data models
- [x] ODSP income models
- [ ] Transaction entry UI
- [ ] Income entry UI
- [ ] Local database with Room
- [ ] Transaction list and filtering
- [ ] Income history view
- [ ] Reports and summaries
- [ ] Data export functionality
- [ ] Backup and restore
- [ ] Calculator for HST
- [ ] Receipt photo attachment
- [ ] Multi-language support (English/French)
