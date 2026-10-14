1. ffmpeg and qrencode commands (14th October 2026)
2. ffmpeg : Tool used to convert video and audio to any other format and size
3. qrencode : Tool used to convert any website url into a qr code
4. ffmpeg commands : 
ffmpeg -i input.mov -frames:v 1 frame1.png
ffmpeg -i recording.mov recording.gif
ffmpeg -i recording.mov -t 5 recording2.mov
ffmpeg -i recording.mov -vf scale=640:-2,fps=30 recording4.gif
5. What broke ?
Using invalid file extension-It will raise error telling us to use a standard extension or specify format manually
Mispelling a filter name-It will rasie Invalid Argument Error
6. qrencode commands :
qrencode -o qr1.png www.youtube.com
7. The five steps that I followed :
Install the tool
Read the Documentation
Execute the commands
Experiment with the tool by breaking and fixing it
