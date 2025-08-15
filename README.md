# YouTube Channel Video Data Collector

This tool collects detailed information about all videos on a YouTube channel, including:

*   Thumbnail URL
*   Title
*   Number of Likes
*   Number of Views
*   Upload Date
*   Video Length

## Setup

Before running this tool, you'll need to configure your environment with the necessary API key and channel ID.

1.  **Enable the YouTube Data API v3:**  Go to the [Google Cloud Console](https://console.cloud.google.com/) and enable the YouTube Data API v3.

2.  **Create an API Key:**  In the Google Cloud Console, create an API key.  Make sure to restrict the key to only the YouTube Data API v3 for security.

3.  **Create a `.env` file:**  In the root directory of this project, create a file named `.env` and add the following lines, replacing the placeholders with your actual values:

    ```
    YOUTUBE_API_KEY=YOUR_YOUTUBE_API_KEY
    CHANNEL_ID=YOUR_YOUTUBE_CHANNEL_ID
    ```

    *   `YOUTUBE_API_KEY`:  Your YouTube Data API v3 key.
    *   `CHANNEL_ID`: The ID of the YouTube channel you want to collect data from.  You can find this in the channel's URL (e.g., `https://www.youtube.com/channel/UCxxxxxxxxxxxxxxxx`).
