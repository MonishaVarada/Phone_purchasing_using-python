# Mobile Phone Selection Assistant

## Overview
This Python script is an interactive mobile phone selection assistant that helps users choose a phone based on brand, model, storage, and color. It retrieves phone specifications such as **price, processor, RAM, camera, battery, and display** from a predefined dictionary and displays them in a user-friendly manner.

## Features
- 📱 Supports multiple brands (iPhone, Poco)
- 📊 Displays phone specifications based on user selection
- 🛒 Interactive selection process with validation
- ❌ Error handling for invalid inputs (max 3 attempts per choice)

## How to Use
1. **Run the script**: Execute the Python script in a terminal or IDE.
2. **Select a phone brand**: Choose from the available brands.
3. **Select a model**: Pick the specific model.
4. **Choose storage**: Select from 64GB or 128GB variants.
5. **Choose color**: Pick an available color for the selected model.
6. **View details**: The script will display the phone's specifications.

## Requirements
- Python 3.x

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/phone-selection-assistant.git
   ```
2. Navigate to the project folder:
   ```sh
   cd phone-selection-assistant
   ```
3. Run the script:
   ```sh
   python phone_selection.py
   ```

## Example Output
```
Welcome to the Mobile Phone Shop!
Do you want to buy a phone? (yes/no): yes
Which phone do you want to buy?
1. iPhone
2. Poco
Enter the number corresponding to your choice: 1
Which model do you want?
1. iphone13
2. iphone14
...
Here are the details of the phone you selected:
Name: iPhone
Model: iphone14
Storage: 128GB
Color: Black
Price: $849
Processor: A15 Bionic
RAM: 4GB
Camera: 48MP
Battery: 5000mAh
Display: 6.1-inch
```

## License
This project is licensed under the MIT License.

## Contributions
Feel free to fork the repository and submit a pull request for improvements! 🚀

