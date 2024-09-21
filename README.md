# SocialMediaWatchOS 

A minimalist social media UI app for Apple Watch, inspired by Instagram. This project serves as a foundation for developing a social media app that runs exclusively on watchOS. The app demonstrates a feed of posts that includes images, names, and locations, allowing users to like posts.

## Featues 
• Displays social media posts in an Instagram-like layout<br />
• Users can like posts by tapping the heart icon<br />
• Posts include a profile image, username, photo, and location<br />
• SwiftUI-based interface, optimized for watchOS<br />
• Example data is provided through the DummyData module<br />

## Installation 

1. Install Xcode: Make sure you have the latest version of Xcode installed on your Mac. <br />
2. Clone the repository: Use the following command to clone the repository: 
`git clone https://github.com/yourusername/SocialMediaWatchOS.git`<br />
3. Open the project: Open the `SocialMediaWatchOS.xcodeproj` file in Xcode.<br />
4. Build and run: Select a Watch Simulator or a connected Watch device in the scheme and click Run<br />

## Project Structure
**Feed.swift**: The data model that defines the structure of a post (name, image URL, location).<br /><br />
**PostView.swif**t: The view that displays individual posts, including the header, image, and footer (like functionality).<br /><br />
**PostViewModel.swif**t: The view model that handles the logic for the "like" state and animations.<br /><br />
**ContentView.swift**: The main view that displays a list of posts. <br /><br />
**DummyData.swift**: Provides sample content for the app. <br /><br />

## App Preview
![Simulator Screenshot - Apple Watch Series 10 (46mm) - 2024-09-21 at 10 54 50](https://github.com/user-attachments/assets/19025a58-632d-4314-bc5a-9b817ca47362)

## Future Enhancements
• Integration of real social media feeds through an API <br />
• Comment functionality <br />
• Share posts feature <br />
• Upload your own posts <br />
• Complete offline and online functionality <br />
