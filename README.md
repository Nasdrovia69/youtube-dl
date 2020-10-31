# youtube-dl
error  youtube-dl

youtube-dl --verbose  https://www.youtube.com/watch?v=eRrzt5HWBPA



[debug] System config: ['--prefer-free-formats']
[debug] User config: []
[debug] Custom config: []
[debug] Command-line args: ['--verbose', 'https://www.youtube.com/watch?v=eRrzt5HWBPA']
[debug] Encodings: locale UTF-8, fs utf-8, out utf-8, pref UTF-8
[debug] youtube-dl version 2020.09.20
[debug] Python version 3.9.0 (CPython) - Linux-5.8.16-300.fc33.x86_64-x86_64-with-glibc2.32
[debug] exe versions: ffmpeg 4.3.1, ffprobe 4.3.1
[debug] Proxy map: {}
[youtube] eRrzt5HWBPA: Downloading webpage
[youtube] eRrzt5HWBPA: Downloading embed webpage
ERROR: Unable to extract JS player URL; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; see  https://yt-dl.org/update  on how to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.
Traceback (most recent call last):
  File "/usr/lib/python3.9/site-packages/youtube_dl/YoutubeDL.py", line 796, in extract_info
    ie_result = ie.extract(url)
  File "/usr/lib/python3.9/site-packages/youtube_dl/extractor/common.py", line 532, in extract
    ie_result = self._real_extract(url)
  File "/usr/lib/python3.9/site-packages/youtube_dl/extractor/youtube.py", line 2100, in _real_extract
    jsplayer_url_json = self._search_regex(
  File "/usr/lib/python3.9/site-packages/youtube_dl/extractor/common.py", line 1010, in _search_regex
    raise RegexNotFoundError('Unable to extract %s' % _name)
youtube_dl.utils.RegexNotFoundError: Unable to extract JS player URL; please report this issue on https://yt-dl.org/bug . Make sure you are using the latest version; see  https://yt-dl.org/update  on how to update. Be sure to call youtube-dl with the --verbose flag and include its complete output.

