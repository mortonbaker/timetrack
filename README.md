# timetrack

## Description
timetrack is a Flask app API that handles incoming GET requests from an authenticated user. It allows users to track time for different projects using the Toggl time tracking service.

## Setup
1. Create a `.txt` file called `toggl_projects.txt` and place it in the root directory of the project.
2. The first time you use the app, it will create links that are output to the `links.txt` file.
3. Take the link for each project and save them on your Android device using the Chrome "Save to Homescreen" function.
4. Each time you click on the saved link icon on your homescreen, Toggl will start tracking time for the corresponding project.

## Usage
1. Make sure you are authenticated as a user.
2. Send a GET request to the appropriate endpoint to start tracking time for a specific project.

## Endpoints
- `/projects`: Returns a list of available projects.
- `/projects/{project_id}`: Starts tracking time for the specified project.

## Authentication
- Authentication is required to access the API endpoints.
- Please refer to the documentation for instructions on how to authenticate.

## Contributing
- Contributions are welcome! Please follow the guidelines outlined in the CONTRIBUTING.md file.

## License
- This project is licensed under the [MIT License](LICENSE).
