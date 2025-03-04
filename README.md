# Church of the Highlands - Bing Bong Downloader

A simple tool for downloading YouTube videos for Church of the Highlands team members.

## How to Use

1. Visit the tool at: [https://yourusername.github.io/bing-bong-downloader](https://yourusername.github.io/bing-bong-downloader)
2. Paste a YouTube URL in the input field
3. Select your preferred format:
   - MP4 720p: Good quality, medium file size
   - MP4 1080p: High quality, larger file size
   - MP3 Audio: Audio only, smallest file size
4. Click "Generate Download Command"
5. Copy the generated command
6. Open Terminal (Mac) or Command Prompt (Windows)
7. Paste and run the command

## Installation Requirements

Before using this tool, you need to install yt-dlp on your computer:

### Mac Installation

1. Install Homebrew (if you don't already have it):
2. Install yt-dlp:
3. Verify installation:
### Windows Installation

1. Download the latest yt-dlp.exe file from [the official GitHub repository](https://github.com/yt-dlp/yt-dlp/releases)

2. Put the yt-dlp.exe file in a folder that's in your PATH:
- Option 1: Place it in `C:\Windows`
- Option 2: Create a new folder (like `C:\yt-dlp`), place it there, and add that folder to your PATH

3. To add a folder to your PATH:
- Search for "Environment Variables" in the Start menu
- Click "Edit the system environment variables"
- Click "Environment Variables"
- Under "System variables", find "Path" and click "Edit"
- Click "New" and add your folder path (e.g., `C:\yt-dlp`)
- Click OK on all dialogues

4. Verify installation by opening Command Prompt and typing:
## Troubleshooting

- **Command not found error**: Make sure yt-dlp is properly installed and in your PATH
- **Download errors**: YouTube occasionally changes its format IDs. If you encounter an error, try another format
- **Slow downloads**: Switch to a lower quality format or check your internet connection
- **File permissions**: If you can't save the file, make sure you have write permissions in your Downloads folder

## Important Notes

- This tool is for internal use by Church of the Highlands team members
- Please respect copyright and only download content you have permission to use
- Please do not share this tool outside of our organization

## Contact

For support or questions, please contact [Luke Mueller/Video Team/mueller@churchofthehighlands.com]
