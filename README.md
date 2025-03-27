# LoL Ult Tracker VN

## Overview
This Python script provides a comprehensive analysis of enemy champions in a League of Legends game, extracting:
- Champion levels
- Item inventories
- Total Ability Haste
- Ultimate cooldown 

## Features
- Fetches real-time enemy champion data from Live Client API
- Calculates Ability Haste from current item builds
- Retrieves ultimate cooldown based on champion level
- Supports concurrent data processing

## Prerequisites
- Python 3.8+
- League of Legends Client running
- Active game in progress

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/lol-enemy-analysis.git
cd lol-enemy-analysis
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Ensure League of Legends client is running
2. Start a game
3. Run the script:
```bash
python main.py
```

## Dependencies
- requests
- urllib3

## Troubleshooting
- Ensure League of Legends client is running
- Check network connectivity
- Verify game is in progress

## Disclaimer
This tool is for educational purposes. Use responsibly and in compliance with Riot Games' terms of service.

## License
GNU v3.0

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss proposed changes.
