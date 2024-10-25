# YouTube Automated Testing with Selenium WebDriver

This project demonstrates automated testing of YouTube using **Selenium WebDriver** in Java. The test suite covers a variety of functionalities on the YouTube platform, validating different actions such as login, video search, playback, and user interactions, ensuring they work as expected.

## Project Overview

This project includes several test cases written using **TestNG** to automate actions on YouTube. The tests cover:

- Logging into YouTube
- Searching for videos
- Playing and interacting with videos (like, comment, etc.)
- Interacting with YouTube channels
- Logging out

### Key Features
- **Dynamic Elements**: Test cases 7, 8, and 9 involve dynamic elements such as channel interactions, video playlist management, and logout functionality.
- **JavaScript Execution**: `JavascriptExecutor` is used to handle certain dynamic interactions, like scrolling and clicking elements.
- **Synchronization**: `WebDriverWait` is used to manage timeouts and ensure reliable element interaction.

## Test Cases Overview

1. **Test Login Functionality**  
   Automates logging into YouTube using credentials and verifies successful login.

2. **Test Video Search**  
   Searches for a video using the search bar and verifies the search results are displayed.

3. **Test Video Playback**  
   Automates playing a video and ensures the video starts playing.

4. **Test Like Video**  
   Likes a video and checks if the action is successfully completed.

5. **Test Scroll to Comments**  
   Scrolls down to the comments section and verifies its visibility.

6. **Test Channel Interaction**  
   Opens a YouTube channel and interacts with the "Videos" and "About" tabs.

7. **Test Logout Functionality**  
   Logs out from YouTube and verifies that the sign-in button is displayed again.

8. **Test Add Video to Playlist**  
   Adds a video to the playlist and confirms the action. *(Includes dynamic elements)*

9. **Test Share Video Functionality**  
   Shares a video by copying the link and verifies the success message. *(Includes dynamic elements)*

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/DeshveerBatth/YouTube-Testing.git
