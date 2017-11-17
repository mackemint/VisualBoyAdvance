# VisualBoyAdvance 

(See the original document in README.)

I've forked the project while trying to fix sound stuttering issues happening on Pocket CHIP. I could only improve it a bit essentially making the audio buffer (and latency) larger, so it's not really a fix yet.

If you want to try it out, then build & install:

	./configure --disable-profiling --disable-dev --disable-sdltest
	sudo make install

---
