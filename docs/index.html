<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2575.4">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; -webkit-text-stroke: #000000}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; -webkit-text-stroke: #000000; min-height: 14.0px}
    span.s1 {font-kerning: none}
    span.s2 {font: 12.0px 'Apple Color Emoji'; font-kerning: none}
  </style>
</head>
<body>
<p class="p1"><span class="s1">&lt;!DOCTYPE html&gt;</span></p>
<p class="p1"><span class="s1">&lt;html lang="en"&gt;</span></p>
<p class="p1"><span class="s1">&lt;head&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;meta charset="UTF-8"&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;title&gt;myAvatar&lt;/title&gt;</span></p>
<p class="p1"><span class="s1">&lt;/head&gt;</span></p>
<p class="p1"><span class="s1">&lt;body&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;h1&gt;Welcome to myAvatar&lt;/h1&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;button id="recordButton"&gt;</span><span class="s2">🎤</span><span class="s1"> Talk&lt;/button&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;audio id="audioPlayback" controls&gt;&lt;/audio&gt;</span></p>
<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;script&gt;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>let isRecording = false;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>let mediaRecorder;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>let audioChunks = [];</span></p>
<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>document.getElementById("recordButton").addEventListener("click", async () =&gt; {</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>if (!isRecording) {</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>audioChunks = [];</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>let stream = await navigator.mediaDevices.getUserMedia({ audio: true });</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>mediaRecorder = new MediaRecorder(stream);</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>mediaRecorder.ondataavailable = event =&gt; audioChunks.push(event.data);</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>mediaRecorder.onstop = sendAudio;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>mediaRecorder.start();</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>isRecording = true;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>document.getElementById("recordButton").textContent = "</span><span class="s2">🛑</span><span class="s1"> Stop";</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>} else {</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>mediaRecorder.stop();</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>isRecording = false;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>document.getElementById("recordButton").textContent = "</span><span class="s2">🎤</span><span class="s1"> Talk";</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>}</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>});</span></p>
<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>async function sendAudio() {</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>let audioBlob = new Blob(audioChunks, { type: 'audio/webm' });</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>let formData = new FormData();</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>formData.append("audio", audioBlob);</span></p>
<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>let response = await fetch("https://myavatar-backend.onrender.com/process_audio", {<span class="Apple-converted-space"> </span></span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>method: "POST",<span class="Apple-converted-space"> </span></span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">                </span>body: formData<span class="Apple-converted-space"> </span></span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>});</span></p>
<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>let audioResponse = await response.blob();</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>let audioURL = URL.createObjectURL(audioResponse);</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">            </span>document.getElementById("audioPlayback").src = audioURL;</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">        </span>}</span></p>
<p class="p1"><span class="s1"><span class="Apple-converted-space">    </span>&lt;/script&gt;</span></p>
<p class="p1"><span class="s1">&lt;/body&gt;</span></p>
<p class="p1"><span class="s1">&lt;/html&gt;</span></p>
</body>
</html>
