<b>CubEd</b> <br />
<br/>
<b>Inspiration</b><br/>
A recent research published showed that a large majority of the world's population is not tech savvy enough to use<br/> 
do simple things like search online. This can prove to be a major hindrance to learning as it inhibits a persons ability <br/>
to search for information to clarify doubts and expand their current knowledge base. We sought to somehow plug this gap <br/>
by coming up with a suitable solution<br/>
<br/>
<b>What it does</b><br/>
Our software uses an image of what you are reading to detect key concepts and based on which concept is most relevant to<br/>
you it gives suitable video suggestions. It also provides a call feature to connect you to people exploring similar areas to help<br/>
you share and learn more.<br/>
<br/>
<b>How we built it</b><br/>
We used technologies like AR.js, Three.js, AgoraRTC SDK, javascript , HTML and CSS to build a fluid, attractive<br/>
and efficient front end to interact with user. Our backend comprises of a flask server written in python which runs an OCR<br/> 
on the image taken on the user's phone and then does text analysis followed by some web-scrapping to serve relevant information to the user.<br/>
<br/>
<b>Link to project and demo video</b><br/>
https://devpost.com/software/cubed <br/>
<br/>
<b>Instructions to run: </b><br />
1.Download the agorabackend.py file present in examples.<br />
2.Run the python code to launch the flask server.<br />
3.Open l102.html from the examples folder and replace the word `localhost` in the URL with the IP address of the computer running the flask server.<br />
  All the URL's to be changed will be highlighted by a comment above it : <br />
  #####################REPLACE localhost with server IP###########################<br />
4.Now you can run l102.html on the browser or host it on a server to access it from your phone.<br />
