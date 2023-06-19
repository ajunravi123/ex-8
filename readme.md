
# Non-linear Video Streaming Prototype - AdyaCare

An express application to stream videos

## Author
Ajun Ravi

## Description
This is a prototype of a non-linear video streaming platform

## Features

- Identifying users for authentication and showing contents.
- Efficient streaming techniques to load GB sized videos within seconds.
- Tracking watched videos list against the users
- Last watched time-line also will be tracked
- On sign-in, the last wated video will be played by default.
- All the videos will streamed from the last watched location.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/ajunravi123/Non-linear-VideoStreaming-AdyaCare.git
   cd Non-linear-VideoStreaming-AdyaCare

2. Download the video files and add to /videos folder

    Download from https://drive.google.com/drive/folders/1-fcvJPMPacRT6oSc0RLTPGmDYRdnbeBW?usp=sharing

    Note: The video file names should be same.

3. Install the dependencies

    npm install

4. Run the server

    node server.js


Access the API documentation:

Open your web browser and navigate to http://localhost:3001.


```sh
127.0.0.1:3001
```

OR

```sh
http://localhost:3001
```

Usage
- To add more videos, modify /videos.json file and add the video file to /videos folder.

