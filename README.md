# Spotify API Testing with Postman and Newman

This repository contains automated tests for the Spotify API, built using Postman and run via Newman (the command-line companion for Postman). It showcases testing various Spotify API endpoints such as retrieving artist details, top tracks, and managing playlists.

## Project Overview

The goal of this project is to perform API testing for Spotify using Postman and Newman. This includes GET, PUT, and POST requests to interact with the Spotify API and validate the responses using Postman’s built-in features.

## Features

- **GET Artist Information**: Retrieve details of specific artists by their ID.
- **GET Top Tracks**: Fetch top tracks for an artist in a specific market.
- **POST ADD Playlist**: Create a new playlist in the current user's Spotify account.
-**GET Playlist**: Retrieve details of a specific playlist, including its items.
-**POST ADD ITEM TO pLAYLIST**:Add a track or episode to the specified playlist.
- **DELETE Remove item from Playlist**: Remove a track or episode from a playlist.
-**PUT Update the cover photo**: Update the image for an existing playlist.

## Tools & Technologies

- **Postman**: API testing platform to send requests and verify responses.
- **Newman**: Command-line tool to run Postman collections.
- **Spotify API**: API used to access music data, artist info, and user libraries.
- **Node.js & npm**: For installing and running Newman.

## Prerequisites

1. **Spotify Developer Account**: To generate Client ID and Client Secret.
2. **Postman**: For managing API requests and running tests.
3. **Node.js**: Required for running Newman.
4. **Newman**: Installed globally using:
    ```bash
    npm install -g newman
    ```

## Running the Tests Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/spotify-api-testing.git
