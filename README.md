Youtube Subtitle Downloader
===========================

    Youtube Subtitle Downloader downloads subtitle from a Youtube video if it's present and convert to SRT format.

    Usage: youtubesub.py [-h] [-l] [--language LANGUAGE] [--filename FILENAME]
                         [--filetype {srt,xml}]
                         url

    positional arguments:
      url                   URL of the Youtube video

    optional arguments:
      -h, --help            show this help message and exit
      -l, --list            list all available languages
      --language LANGUAGE   the ISO language code
      --filename FILENAME   specify the name of subtitle
      --filetype {srt,xml}  specify the output type of subtitle

    Example:
    python youtubesub.py --filename subtitle --language en http://www.youtube.com/watch?v=5MgBikgcWnY

    :copyright: (c) 2014 by Nguyen Dang Minh (www.minhnd.com)
    :license: BSD, see LICENSE for more details.
