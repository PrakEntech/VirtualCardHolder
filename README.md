# Virtual Card Holder

This **Virtual Card Holder** project, written in Dart and Flutter, is designed to manage and store digital versions of visiting cards. The application allows users to add, view, edit, and store contact details digitally, making it easier to manage business and personal contacts efficiently.

## Features
- **Add New Contacts**: Users can manually input contact details and add them to the database.
- **Scan Cards**: Ability to scan visiting cards (likely via OCR integration) and extract contact details.
- **View Contacts**: Display a list of all saved contacts, with an option to view full details for each.
- **Edit or Delete Contacts**: Users can easily edit or remove contacts from the system.
- **Database Integration**: All contact details are stored in a local database for persistent storage.

## File Structure
- **main.dart**: Entry point of the application.
- **providers/contact_provider.dart**: Manages the state of contacts across the application.
- **utils/helper_functions.dart**: Contains utility functions to support various operations in the app.
- **utils/constants.dart**: Holds constant values used across the app.
- **models/contact_model.dart**: Defines the structure of the contact data, including fields like name, phone number, email, etc.
- **db/db_helper.dart**: Handles interactions with the local database for storing and retrieving contact information.
- **pages/**: Contains the different screens of the app, including:
  - **home_page.dart**: Displays a list of all saved contacts.
  - **form_page.dart**: A form for adding or editing contact details.
  - **contact_details_page.dart**: Shows detailed information for a selected contact.
  - **scan_page.dart**: Likely integrates with a feature for scanning visiting cards.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PrakEntech/VirtualCardHolder.git
   ```
2. Navigate to the project directory:
   ```bash
   cd VirtualCardHolder
   ```
3. Fetch dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality or add new features.

## Screenshots
