'use strict';

const e = React.createElement;
var wavesurfer;
var setup = false; //Toggles setup script 

//List of music URL
var music = ["https://ia800108.us.archive.org/14/items/78_when-a-woman-loves-a-man_billie-holiday-and-her-orchestra-billie-holiday-buck-clayt_gbia0031202/03%20-%20I%20Can%27t%20Get%20Started%20-%20Billie%20Holiday%20and%20her%20Orchestra.mp3",
	"https://ia800100.us.archive.org/1/items/78_i-fall-in-love-too-easily_chet-baker-kahn-styne_gbia0029331a/I%20Fall%20In%20Love%20Too%20Easily%20-%20Chet%20Baker%20-%20Kahn.mp3",
	"https://ia800801.us.archive.org/35/items/78_sixteen-tons_tennessee-ernie-ford-jack-fascinato-merle-travis_gbia0012328a/Sixteen%20Tons%20-%20%22Tennessee%22%20Ernie%20Ford%20-%20Jack%20Fascinato.mp3",
	"https://ia800802.us.archive.org/22/items/78_cry-me-a-river_julie-london-arthur-hamilton-barney-kessell-ray-leatherwood_gbia0010105a/Cry%20Me%20a%20River%20-%20Julie%20London%20-%20Arthur%20Hamilton.mp3",
	"https://ia800108.us.archive.org/13/items/78_west-end-blues_louis-armstrong-and-his-orchestra-spencer-williams_gbia0031327/01%20-%20Mahogany%20Hall%20Stomp%20-%20Louis%20Armstrong%20And%20His%20Orchestra.mp3",
	"https://ia800704.us.archive.org/0/items/78_hark-the-herald-angels-sing_warren-averel-william-ashley-tappin_gbia0072877b/Hark%20the%20Herald%20Angels%20Sing%20-%20Warren%20Averel.mp3",
	"https://ia600103.us.archive.org/5/items/78_in-the-mood_glenn-miller-and-his-orchestra-johnson-dash-hawkins_gbia0020402/04%20-%20In%20the%20Mood%20-%20Glenn%20Miller%20and%20his%20Orchestra.mp3",
	"https://ia802804.us.archive.org/29/items/78_a-hand-fulla-gimme_dizzy-gillespie-sextet-dizzy-gillespie_gbia0039391/01%20-%20Groovin%27%20High%20-%20Dizzy%20Gillespie%20Sextet%20-%20Dizzy%20Gillespie.mp3",
	"https://ia600607.us.archive.org/21/items/78_a-duke-ellington-panorama_duke-ellington-and-his-famous-orchestra-ellington-miley-d_gbia0003362/East%20St.%20Louis%20Toodle-oo%20-%20Duke%20Ellington%20and%20his%20Famous%20Orchestra.mp3",
	"https://ia800803.us.archive.org/21/items/78_i-concentrate-on-you_frank-sinatra-clesi-axel-stordahl_gbia0020026/03%20-%20How%20Deep%20is%20the%20Ocean%20-%20Frank%20Sinatra%20-%20Berlin.mp3"
];

document.addEventListener('DOMContentLoaded', function () {
	var wavesurfer = WaveSurfer.create({ //Create instance of Wavesurfer
		container: '#waveform'
	});

	if (!setup) { //Inital setup, load music and display URL
		setup = true; //Only happens once
		document.getElementById("musicURL").innerHTML = music[0];
		wavesurfer.load(music[0]);
	}

	document.getElementById("selectMusicMenu").addEventListener("change", function () { //Load selected music and change URL name when select menu item is changed
		document.getElementById("musicURL").innerHTML = music[selectMusicMenu.selectedIndex];
		wavesurfer.load(music[selectMusicMenu.selectedIndex]);
	});

	class playPauseButton extends React.Component { //Toggle music playback
		constructor(props) {
			super(props);
			this.state = { //Inital state
				playback: false
			}; 
		}

		render() {
			if (this.state.playback) { //Render pause button
				return e(
					'button', {
						onClick: () => this.setState({ //Switch state on button click
							playback: false
						})
					}, 
					'|>',
					wavesurfer.pause(), //Pause music
				)
			}

			return e( //Render play button
				'button', {
					onClick: () => this.setState({
						playback: true
					})
				},
				'||',
				wavesurfer.play() //Play music
			);
		}
	}

	ReactDOM.render(e(playPauseButton), document.querySelector('#playPauseButton_container')); //Display React playPauseButton

});
