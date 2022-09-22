# scotrail-beats-birthday-present

A birthday present for the loveliest Helen ❤️

With many thanks to:

- [ScotRail](https://www.scotrail.co.uk),
- [Alison McKay](https://www.alisonmckay.com) for her voice talent,
- [Lofi Girl](https://www.youtube.com/watch?v=jfKfPfyJRdk) for the beats,
- [all of the wonderful people](https://github.com/matteason/scotrail-announcements-june-2022) who crowdsourced the transcription, and
- Matt Eason's [Ambient ScotRail Beats](https://www.matteason.co.uk/scotbeats/) for the idea

# Setup

```
python3 -m venv venv
pip install -r requirements.txt
```

## Background music

Source an appropriately licensed music clip as an MP3 file and update the `background_music` file pointer in the last cell.

```
youtube-dl --list-formats 'https://www.youtube.com/watch?v=jfKfPfyJRdk'
youtube-dl --format 96 --extract-audio --audio-format mp3 'https://www.youtube.com/watch?v=jfKfPfyJRdk'
https://stackoverflow.com/questions/37040798/how-do-you-use-youtube-dl-to-download-live-streams-that-are-live
```

# Resources

## ScotRail automated announcements - Release, crowdsourcing, and tooling

- [ScotRail announcements 2022: GitHub](https://github.com/matteason/scotrail-announcements-june-2022)
- [ScotRail announcements 2022 MP3s: Google Drive](https://drive.google.com/drive/u/0/folders/172W6sXnvlr7UcNLipO8BTw417_KRz9c5)
- [ScotRail announcements 2022: Original crowdsourcing spreadsheet](https://docs.google.com/spreadsheets/d/1jAtNLBXLYwTraaC_IGAAs53jJWWEQUtFrocS5jW31JM/edit#gid=891105514)
- [Ambient ScotRail Beats](https://www.matteason.co.uk/scotbeats/)
- [ScotRail Soundboard](https://scotrail.fishcreek.dev)
- [Analysing ScotRail audio announcements with Datasette—from prototype to production](https://simonwillison.net/2022/Aug/21/scotrail/)
- [ScotRail random apology generator](https://scotrail.datasette.io/scotrail/random_apology)

## UK rail maps

- [ScotRail: Scotland route map](https://www.scotrail.co.uk/sites/default/files/assets/download_ct/20220623/d6jhgE7KTaqBw-G-Ycbp2vBVUEgBsL-gIDduFRUbDyk/n1_route_map_2022.pdf)
- [ScotRail: Glasgow and Edinburgh route map](https://www.scotrail.co.uk/sites/default/files/assets/download_ct/20220623/9PYe2pK9lUUIrSM5dKa9gnta_YG6fQfeJT4vbkBe9Vc/cs_route_map_2022.pdf)
- [ScotRail: Live network map](https://www.scotrail.co.uk/sites/all/modules/interactive_map/assets/index.html)
- [National Rail train operators route map](https://www.nationalrail.co.uk/TOCs%20v56c%20May%202022.pdf)
- [British Railways map - Merritt Cartographic](https://www.merrittcartographic.co.uk/british_railways.html)

## UK rail data (unused)

- [A database of UK train stations](https://github.com/davwheat/uk-railway-stations)

## Pydub

https://github.com/jiaaro/pydub/blob/master/API.markdown
https://www.thepythoncode.com/article/concatenate-audio-files-in-python
