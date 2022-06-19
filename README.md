# music-player

music-player is a MagicMirror module to play music, with touch screen support.

## Installation


```bash
cd ~/MagicMirror/modules
git clone https://github.com/CoderAryanAnand/music-player.git
cd music-player
npm install
```

## Usage
Add this to ```config.json```
```js

{
	module: "music-player",
	position: "top_right",
	config: {
	    shuffle: true,
        classes: "default"
	}
},
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Credits
I used [this](https://github.com/justjim1220/MMM-MP3Player) as a template, so thank you justjim1220.

## License
[MIT](https://choosealicense.com/licenses/mit/)
