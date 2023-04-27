
# Mr. Proctor - Online Test Proctoring Extension
![Logo](https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/icons/icon3.png)

## About
Mr. Proctor is a Chrome extension that operates on assessment websites, activating when a user opens a test page. It opens a form for the user to enter their details and redirects to the test page. The extension performs audio-video check, and initiates image proctoring, sending images to the server as per the interval set(configurable). It also comes with an Admin Dashboard which displays user's information along with stored images.


## Installation

- Download the Mr. Proctor- Extension zip file from the GitHub repository.
- Extract the contents of the zip file to a folder on your computer.
- Open the Chrome browser and type `chrome://extensions/` in the address bar.
- Enable Developer mode by clicking the toggle switch in the top right corner of the page.
- Locate the `Load unpacked` button in the top left corner of the page.
- Browse and select the folder where you extracted the extension files in step 2.
- The Mr. Proctor- Extension will be added to your browser and ready to use on supported online assessment websites.
- Please Ensure that backend is setted up on `localhost:3000`

## Features

### Frontend - Chrome Extension
- Allows users to input their details through a form like their name, email, and test invitation code.
<img alt="extension" src="https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/images/extension%20bar.png" width="300" height="400" />
<img alt="form" src="https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/images/popup%20form.png" width="300" height="400" />
- Upon clicking the &quot;Start Test&quot; button, the user is redirected to the test page, while the user's information is sent to the backend server.
<img alt="user-details" src="https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/images/user%20details.png" width="300" height="400" />
- Performs audio and video requirement checks and displays the candidate's live webcam feed on the page.
- Also detects whether user has kept multiple tabs open.
<img alt="test-page" src="https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/images/test%20redirect.png" width="700" height="500" />
- Sends images of the user from the browser to the server at configurable intervals.

### Backend - [Mr. Proctor Backend](https://github.com/pragti-chauhan/mr-proctor-backend)
- A backend API to store all user information and images.
- Images are stored in on cloud data storage `cloudinary storage`
- Images are stored along with timestamps.
<img alt="dashboard" src="https://github.com/pragti-chauhan/mr-proctor-extension/blob/main/images/dashboard.png" width="700" height="500" />
- Handle Set Interval Route
- Admin Dashboard is set up on [Render](https://mr-proctor.onrender.com/)

## Tech Stack

**Frontend:** HTML, CSS, JavaScript

**Backend:** Node, Express, MongoDB, cloudinary storage


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Referrence for making extension](https://github.com/om-mapari/proctor-vision-extension)
 - [Easy and Quick Deployment](https://render.com/)


## Authors

- [pragti-chauhan](https://github.com/pragti-chauhan)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pragti-chauhan-2132a61a2/)
