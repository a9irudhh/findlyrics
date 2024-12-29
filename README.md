# FindLyrics

A simple CLI tool to fetch song lyrics using the Genius API.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/a9irudhh/findlyrics.git
   cd findlyrics
   ```

2. **Copy the Script to `/usr/local/bin`:**
   ```bash
   sudo cp findlyrics /usr/local/bin
   ```

3. **Make the Script Executable:**
   ```bash
   sudo chmod +x /usr/local/bin/findlyrics
   ```

4. **Restart Your Terminal.**

5. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the command:
```bash
findlyrics "song_name" "artist"
```

### Example:
```bash
findlyrics "Shape of You" "Ed Sheeran"
```

## API Key
Replace `API_HERE` in the script with your Genius API token.

Feel free to open issues or submit pull requests!

## Author
[Anirudh](https://github.com/a9irudhh)