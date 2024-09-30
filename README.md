# ffmpeg-mosh

Datamoshing with ffmpeg audio filters in Google Collab

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/whatmakeart/ffmpeg-audio-mosh/blob/main/ffmpeg_audio_filter_datamosh.ipynb)

Inspired and adapted from. [ffmosher](https://github.com/davFaithid/ffmosher) by [davFaithid](https://github.com/davFaithid) which was inspired by [this example](https://www.reddit.com/r/datamoshing/comments/9s0los/datamoshd_a_screenshot_with_audacity_came_out/). Thank you to davFaithid for the original code and concept. This code is shared under the same open license as the origina.

Created using plain language inputs into the ChatGPT o1-preview as an experiment to see if a useable result could be produced. It works better with lower resolution videos but can be run in Google Colab. As LLM's continue to advance, hopefully more software tools can be created by users with plain language instructions so people can create and make the things that they want.

Pulls a frame from the video and applies audio filter effects and then displays a grid of thumbnail examples of the effects. Click the boxes of the effects to apply and they will be combined in the final video output.

![Creates thumbnails of audio filter datamosh effects](https://github.com/whatmakeart/ffmpeg-audio-mosh/blob/main/img/pick-audio-filter-thumbnails.jpg)

Allows for each selected filter to have a custom start and stop duration.

![Select Duration of Filter Effects](https://github.com/whatmakeart/ffmpeg-audio-mosh/blob/main/img/select-filter-duration.jpg)

## Example

![Select Duration of Filter Effects](https://github.com/whatmakeart/ffmpeg-audio-mosh/blob/main/img/input-output.gif)
