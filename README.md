# Github_Profile_Searcher


This project is a web application that allows users to search for GitHub profiles and display relevant information in a user-friendly manner. It fetches user data and repositories from the GitHub API and displays them in an attractive card layout.

__Features__
* Search GitHub Profiles: Users can enter a GitHub username and retrieve the corresponding profile information.
* Profile Information Display: Displays user information such as avatar, name, bio, and number of public repositories.
* Repository Information Display: Lists up to 5 public repositories with links to visit each repository on GitHub.
* Error Handling: Provides error feedback if the profile is not found.
* 
__Technologies Used__
__HTML:__ To create the structure and layout of the application.
__CSS:__ For styling the application, including colors, card layout, alignment, and headings.
__JavaScript:__ To handle the logic, make API calls, and dynamically update the HTML content.
__GitHub API:__ To fetch user and repository data.
__Axios:__ To make API requests.

__Project Structure__
index.html: The main HTML file that contains the input field and divs where the profile and repository information will be displayed.
styles.css: The CSS file that styles the application, including the card layouts and overall design.
script.js: The JavaScript file that handles API calls, error handling, and dynamically updating the HTML content.

__How It Works__
* User Input: The user enters a GitHub username in the input field.
* API Calls:
The userGetFunction makes an API call to fetch the user profile information.
The repoGetFunction fetches the repositories of the user.
* Display Information:
The userCard function displays the user profile information in a card.
The repoCardFunction displays up to 5 repositories in a clickable format.
Error Handling: If the username is not found, an error message is displayed.

__Usage__
Clone the repository:
git clone https://github.com/yourusername/github-profile-search.git

Navigate to the project directory:
cd github-profile-search

__Screenshots:__


__Contributing__
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

__License__
This project is licensed under the MIT License.


