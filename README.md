<img src="https://cdn.abdursoft.com/assets/radio/small.png" alt="abdursoft" />
<h1 align="center">Premium Radio Player</h1>
<h1 align="left">Hi 👋, I'm Abdur Rahim</h1>
<h3 align="left">I built this plugin to stream live radio and musics. It's built with javascript and jquery.Now you can stream your radio with my plugin/player. It's 100% responsive and cross browser copatibality. It will collect meta-data from radio station such as title,images,artist etc. It comes with 3 skin or UI such as large,small and fixed</h3>

<p>It supported all kind of audio format with HTML5, mpeg,mpd,aac,ogg,hls etc.So don't worry about your streaming.</p>
<img alt="Coding" width="100%" src="https://cdn.abdursoft.com/assets/radio/large.png">

<h4>You can use this plugin very easily. It's setup is so much easy. If your website built without wordpress you can use jquery Plugin, if your website built with wordpress so don't be worry I also have wordpress plugin. You can easily create your shortcode form wordpress dashboard for streaming.</h4>

- 📻 Visit the radio site to see a demo [premium-radio-player](https://premium.abdursoft.com) 
- 📻 To test the radio visit this site [premium-radio-test](https://premium.abdursoft.com/radio)

<h2>I'm putting the plugin configuration for javascript plugin</h2>

``
<script>
        $("#myPlayer").prRadio({
          src: "https://ais-edge106-live365-dal02.cdnstream.com/a06375",
          stream: "radio",
          autoplay: true,
          api_key:
            "NzJkOWUzZGFkNjg0MGJkNTY5ZDNmNTZkMzExZjZhMzZmMDk0YWU1NWQyNTJhNjYxZGMyZmZkYWIyYmMyMmNlYw==",
          backgroundImg: "", //player background image
          background: "#000", //backgorund opacity color for large and background for small and fixed player
          logo: "https://premium.abdursoft.com/public/resource/images/clasic_rock.png",
          station: "Clasic Rock Florida",
          loop: 0,
          layout: "large", //small,large,fixed
          width: "100", //with percent
          height: "100", //with px
          borderRadius: 19,
          visual: getRandom(), //visualizer 0-5
          opacity: 0.3, //backgroud opacity
          shoutCastId: "",
          radioNomyID: "",
          radioNomyApiKEY: "",
          radioJarID: "",
          radioCoID: "",
          itunesToken: "1000lIPN",
          metaTechnic: "stream-icy-meta",
          ownMetaURL: "",
          corsproxy: "",
          type: "shoutcast2",
          fontColor: "#fff", //change with color code or name
          hoverColor: "red", //change with color code or name
        });

        function getRandom(){
           return Math.floor(Math.random() * 5);
        }
      </script>
``