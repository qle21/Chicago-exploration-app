## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Explore Chicago App

This Flutter app is your go-to guide for exploring the vibrant city of Chicago. The app features a single screen with three tabs containing information about Chicago restaurants, sports teams, and attractions. The app's design includes an AppBar with a flex space displaying a picturesque image of Chicago. The title, "Explore Chicago," is prominently featured. The default tab on app launch is the one showcasing Chicago attractions.

## Features

1. **Tabs:**
   - Three tabs for restaurants, sports teams, and attractions.
   - Initial display on the attractions tab.

2. **List Views:**
   - Each tab includes a list view of at least 5 items.
   - Items are displayed in boxes with rounded corners, clearly separated from each other.

3. **Box Contents:**
   - Thumbnail picture of the item on the left side of the box (roughly square).
   - Title in the top center of the box.
   - Street address below the title, aligned with the title above (no more than two lines).
   - Thumbs-up and thumbs-down icon buttons for likes and dislikes in the bottom right corner of each box, with the number of button presses displayed.

4. **User Interaction:**
   - Clicking on an item triggers an AlertDialog displaying the clicked item.
   - AlertDialog includes appropriate padding for its content.
   - Dismissing the AlertDialog is done by clicking the "OK" button in the bottom right corner.

5. **Flexible Action Button:**
   - Pressing the flexible action button shows a SnackBar message indicating the currently displayed tab.
   - The SnackBar includes an action button to dismiss the Snackbar.

## Implementation Notes

- Designed for optimal display in portrait mode.
- Tested on a Pixel 5 Android Virtual Device running Android 13 (API 33).

## Getting Started

1. Clone the repository.

2. Open the project in your preferred Flutter IDE.

3. Run the app on a Pixel 5 Android Virtual Device running Android 13 (API 33).

4. Explore the Chicago app and interact with the various tabs and items.

Feel free to customize the app further or add more features based on your preferences or requirements.
