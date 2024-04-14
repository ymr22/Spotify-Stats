# Spotify Listening History

Spotify Listening History is a web application that allows users to view their music listening history in real-time using Spotify and Pusher.

## Overview

This application provides users with insights into their recent tracks on Spotify, displaying song titles and the time they were played. It leverages the Spotify API to fetch user listening data and utilizes Pusher to update the listening history in real-time.

## Features

- **Real-Time Updates**: The application updates the listening history in real-time as the user listens to music on Spotify.
- **User Authentication**: Users can connect their Spotify account to the application for personalized music history insights.
- **Recent Tracks Display**: Displays the user's recent tracks, including song titles and play timestamps.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **Pusher**: Real-time communication service for updating the listening history.
- **Spotify API**: Used for accessing user listening data from Spotify.
- **Date-fns**: Library for date formatting.

## Getting Started

To run the application locally, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Navigate to the project directory and run `npm install` to install the necessary dependencies.

3. **Set Up Spotify Developer Account**: Create a Spotify Developer account and register a new application to obtain your client ID.

4. **Configure Environment Variables**: Set up environment variables for your Spotify client ID.

5. **Start the Application**: Run `npm start` to start the development server.

6. **Connect Spotify Account**: Open the application in your web browser and click on the "Connect your Spotify account" link to authorize the application to access your Spotify listening data.

7. **View Recent Tracks**: Once connected, you can view your recent tracks in real-time on the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
