# YouTube_Scraper

Welcome to the **YouTube_Scraper** repository! This Python script is your gateway to efficiently collecting data from YouTube videos on a topic of your choice. The current script was tailored specifically to my interest in diets/nutrition, but the search terms can be changed, so this can be used to scrape the YT videos metadata on any other topic you're passionate about. This tool connects to YouTube's APIs to fetch video metadata across specified time frames.

## Features

- **Customizable Searches:** The script allows for flexible search terms, including lists of terms or specific channel names.
- **Time-bound Data Collection:** Set a starting date, and the script gathers data month by month, ensuring nmetadata on the maximum number of useful videos get harvested. This is helpful to ensure that there is a thorough search, with key videos captured for each month in the past.  
- **Metadata Retrieval:** Video IDs, channel names, video name, number of likes, number of views. You can add more metadata as needed by altering the script. 
- **Efficient API Key Rotation:** Maximizing your data collection efforts, the script smartly rotates through several API keys to work around daily quota limits.

## Usage

To use the YouTube_Scraper, follow these steps:

- Ensure you have valid YouTube API keys. in this script the API keys are hardcoded in a list, with one key per line.
- Modify the SEARCH_TERM and FILENAME to include the topics or channel names you're interested in and define the name of the output file.
- Run the script with a starting date parameter in the format, it is hardcoded YYYY, M (Year, Month). 

## Installation

Before diving in, ensure you have Python installed on your machine. Then, clone this repository to get started:

```bash
git clone https://github.com/yourusername/YouTube_Scraper.git
cd YouTube_Scraper


## License

This project is open-source and available under the MIT License.

## Credits

A big thank you to ChatGPT for assisting in the development of this script. Your contributions have been invaluable.

## Contact

Got questions or suggestions? Feel free to reach out to me directly through GitHub or leave an issue in the repository.


