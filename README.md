# youtube-to-excel
This is a Python script that allows you to scrape the titles and URLs of all the videos of a YouTube channel and save them to an Excel file.


## Requirements
    - Python 3.x
    - openpyxl library
    - requests library
    - YouTube Data API key

## Installation
    1. Clone or download the repository.
    2. Install the required libraries by running !pip install openpyxl requests on your command line
    3.  The script takes two inputs `channel-link` and `Youtube Data API`. You can obtain an API key by creating a project on the Google Developers Console.

    4. Run the script by running `python app.py` on your command line

## Usage
    The script takes one argument, which is the link of the YouTube channel you want to scrape. You can find the channel link by going to the channel's page on YouTube and copying the string of characters after "youtube.com/channel/".

    The script will create an Excel file named "channel_videos.xlsx" in the same directory as the script. The file will contain two columns: "Video Title" and "Video URL".

## Limitations

    The script is limited to the number of videos that the YouTube API allows you to retrieve. It is also limited by the number of requests you can make with your API key.