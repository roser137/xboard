xBoard: A Recordable HTML5 Canvas Based Virtual Whiteboard
---------------

[Editor Demo] | [Embed Demo]

![xBoard Screenshot](https://github.com/eipark/xboard/raw/3bba4ce85ed6f8d731d73f1a252dc0798ec1795c/xboard_recording.png)

__Note__: I started to convert this project to use coffeescript and [brunch](brunch.io). You'll need brunch running locally to get this working now. You can however go back to [this commit](https://github.com/eipark/xboard/commit/bbd5ba4724ba13f296e1b7c5249ed28e973abede) and fork to get the version of the repo before brunch.

xBoard is an HTML5 canvas drawing app that can record your drawings, and play them back like a video. Saving drawings to a database is supported and it can also be embedded in other webpages a la YouTube.

xBoard was completed for my MIT [6.UAP] project (a small scale senior project). You can view the final paper under 6.UAPFinalReport.pdf which gives much more detail and context about the project and the code. It was forked off of [this project] developed at the Aalto University School of Science and Technology.

The original intent of xBoard was to have a transcript play along with the video to account for the lack of audio. Unfortunately, due to the scope of this project, I could not implement it in time. A transcript would greatly increase xBoard's utility. Users can then have context to accompany what they are watching being drawn. Although not in the current build, the code should be extensible enough that adding transcripts should be an endeavor taking only a few days.

xBoard is optimized for Chrome.

  [Editor Demo]: http://web.mit.edu/eipark/Public/xboard/index.html
  [Embed Demo]: http://web.mit.edu/eipark/Public/xboard/embed.html
  [6.UAP]: http://www.eecs.mit.edu/ug/uap.html
  [this project]: http://code.google.com/p/html-5-canvas-whiteboard/
