# playlist-dl
> 📹 Download YouTube playlists for safekeeping.

## Dependencies
- [jq](https://stedolan.github.io/jq)
- [youtube-dl](https://ytdl-org.github.io/youtube-dl)

## Installation
- macOS
```
brew tap strafe/tap
brew install playlist-dl
```

- Linux
	- You know what you're doing :penguin:.

## Configuration
Create a JSON file containing the playlists you'd like to download. An example of the format can be seen in [`playlists.json.example`](playlists.json.example). Playlists will be stored in the same directory as this file.
```
├── playlists.json
├── playlist1/
│   ├── video1.mp4
│   └── video2.mp4
└── playlist2/
    ├── video3.mp4
    └── video4.mp4
```

## Usage
```
Usage: playlist-dl [OPTIONS] <playlist_file>
Download YouTube playlists for safekeeping.

Options:
    -h, --help      Output this message.
    -v, --version   Output the current version.
```

## License
[MIT](LICENSE)
