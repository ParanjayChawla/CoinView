# CoinView: Cryptocurrency tracker

Created with UIKit. This iOS app integrates real-time cryptocurrency data, offering users an intuitive interface to view and interact with the latest market information.

## Features

- **UIKit Based**: Developed using UIKit for a smooth and responsive user interface.
- **Real-Time Cryptocurrency Prices**: Integrates data from the CoinGecko API to provide up-to-date cryptocurrency prices.
- **User-Friendly 'Buy' Feature**: Simulates real-world e-commerce transactions for a hands-on experience.

## Pages Overview

### Page 1: Coin Listing

- **Coins and Prices**: Displays the top 10 coins by market value, followed by other coins. Prices are shown with color coding: green for a positive 24-hour change and red for negative.
- **Thumbnails**: Each coin is represented with its respective thumbnail image.

### Page 2: Coin Details

- **Coin Name**: Displayed next to the thumbnail.
- **Price Information**: Shows the price in both USD and BTC, using the same color scheme as Page 1.
- **Description**: Provides a brief description of the coin in English.
- **'Buy' Button**: Redirects the user to Page 3 for purchasing coins.

### Page 3: Purchase Simulation

- **Price Field**: Users can enter the amount they wish to spend. The quantity of coins to be purchased is calculated automatically.
- **Quantity Field**: Users can enter the quantity of coins they wish to buy. The total price is calculated automatically.
- **Buy Button**: After a transaction, displays an alert with an "OK" button. Clicking "OK" redirects users back to Page 1, encouraging continued engagement with the app.
## Usage

### Prerequisites

- macOS with the latest version of Xcode installed.
- An Apple Developer account (optional, required for deploying to a device).

### Running the Application

1. **Clone the Repository**: First, clone the repository to your local machine using Git:

   ```bash
   git clone https://github.com/ParanjayChawla/CoinView
2. **Open the Project in Xcode**:
- Navigate to the cloned directory.
- Open the **.xcodeproj** file by double-clicking on it or opening it through Xcode.
3. **Install Dependencies** (if any):
- If the project uses CocoaPods, Carthage, or Swift Package Manager, you may need to install dependencies.
- For CocoaPods, run **pod install** in the project directory.
- For Carthage, run **carthage update**.
- For Swift Package Manager, dependencies are usually handled directly within Xcode.
4. **Select a Simulator or Connected Device**:
- In Xcode, choose a simulator or connect your iPhone/iPad to your Mac and select it as the target device.
5. **Build and Run the Application**:
- Press Cmd + R or click on the play button in Xcode to build and run the application.
6. **Explore the App**:
- Once the app is running on the simulator or device, you can explore its features, such as viewing real-time cryptocurrency prices and simulating transactions.
### Troubleshooting
- If you encounter any issues, check that you have the latest version of Xcode installed and that your macOS is up to date.
- Ensure all dependencies are correctly installed and configured.
- Review any error messages in Xcode's console for clues on what might be wrong.
