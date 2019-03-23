# sample-ws-audio-fork

Sample websocket server that receives audio and text stream from [mod_audio_fork](https://github.com/davehorton/drachtio-freeswitch-modules/tree/master/modules/mod_audio_fork).

## Installation
```
npm install
``

## Running
With no command-line arguments, the application listens on port 3001 and writes incoming raw audio packets to file at /tmp/audio.raw.  Any incoming text frames are logged to the console.

The listening port or file to write to can be changed as illustrated below:

```bash
node app.js --port 8080 outfile.raw
```