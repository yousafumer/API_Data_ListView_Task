# Flutter API Data List App
This Flutter application fetches data from an API and displays it in a list format. Users can search through the list of data with a search bar, filtering results in real-time.

# Features
Fetches data from the JSONPlaceholder API (https://jsonplaceholder.typicode.com/posts).
Displays data in a list format with titles and subtitles.
Provides a search bar for real-time filtering of list items based on the search query.
Getting Started
Follow these instructions to set up and run the project on your local machine.

# Prerequisites
Flutter SDK
An internet connection (for fetching API data)
Installation
Clone or download the project:
Download the project as a zip file and extract it.
Or, clone the repository (if hosted on GitHub) using:
bash
# Copy code
git clone https://github.com/your-username/repository-name.git
Navigate to the project folder:
bash
# Copy code
cd your-project-folder
Install dependencies: Run the following command in the terminal to get all required packages:
bash
# Copy code
flutter pub get
# Running the App
To run the app on an emulator or connected device, use the following command:

bash
# Copy code
flutter run
# File Structure
main.dart: The main entry point of the app, which launches the ApiDataScreen.
api_data_screen.dart: Contains the UI and logic for fetching data, displaying it, and filtering results based on the search input.
# Dependencies
http: Used to make API requests.
# Additional Notes
Make sure your device or emulator is connected to the internet.
This app uses the JSONPlaceholder API for sample data.
