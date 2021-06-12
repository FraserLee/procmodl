# procmodl
My current testbed to mess about with some SDF based procedural modeling stuff
<br><br>
/prɔk m(ə)dɛl/ sounds kinda cool, so that'll be how I say it. Why not.
<br><br><br>
A note on the new model: This might not be possible in practice, but theoretically state should be 100% managed by Rust (and sent upwards in full with every update), JS should serve purely as a view to display state and to send user-interaction events back downwards to Rust. 
Right now I could easily pull off everything I wanted through Node without any Rust, but 
1. I have some future plans that involve a lot more intense work being done on the CPU. Sticking to this will make that transition easier
2. Rust seems kinda neat, and I've been looking for an excuse to learn it. Significantly less so with JS.
<br>

(Fair warning if anyone tries to look in here: I'm more concerned with experimenting with interesting techniques and languages than writing a good application. I'm really only keeping this public for some friends, do not expect high quality anything. Peace 👉😎👉 )
<br><br>

![readme-image-1](https://user-images.githubusercontent.com/30442265/121402402-d9357980-c927-11eb-9db7-61cd2624d9e9.png)
