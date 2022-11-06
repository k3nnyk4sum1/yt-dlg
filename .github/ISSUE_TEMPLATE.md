## Please follow the guide below

- You will be asked some questions and requested to provide some information, please read them **carefully** and answer **honestly**
- Put an `x` into all the boxes [ ] relevant to your issue (like that [x])
- Use *Preview* tab to see how your issue will actually look like

### WARNING
All invalid issues will be rejected!!

---

### Before going further

- If your problem is a bug with **youtube-dl** or a request for new site support please report it [here](https://github.com/ytdl-org/youtube-dl/issues)

- Make sure you are using the *latest* **yt-dlg** version (Click the `Settings` icon and then `About` to view the current version)

- Make sure you are using the *latest* **youtube-dl** version (Click the `Settings` icon and then `Update` to update to the latest **youtube-dl** version)

- Make sure you searched the bugtracker for similar issues **including closed ones**

- Make sure to read the [FAQs](https://github.com/oleksis/youtube-dl-gui/blob/master/docs/faqs.md) file

  - [ ] **I think** my problem is **NOT** with **youtube-dl**
  - [x] I've **verified** and **i assure** that I'm running yt-dlg **1.X.Y**
  - [x] **I assure** that i am using the latest version of **youtube-dl**
  - [x] [Searched](https://github.com/oleksis/youtube-dl-gui/issues) bugtracker
  - [x] I've read the FAQs file

---

### What is the purpose of your *issue*?

- [x] Bug report
- [ ] Feature request (request for a new functionality)
- [ ] Question
- [ ] Other

Please remove any sections between (---) if they are not related to your issue

---

### Bug report

#### If the problem occurs when downloading a URL please provide the full verbose output as follows:

1. Restart **yt-dlg**
1. Go to `Options > Extra` tab
2. Enable **Debug youtube-dl**
3. Go to `Options > Advanced` tab and **Clear** your log content
4. Try to download the URL
5. Copy the **whole** log content and insert it between the ``` part below

```
[11/06/22 14:59:12] [debug] exe versions: ffmpeg 3.3.2, ffprobe 3.3.2
[11/06/22 14:59:12] [debug] Proxy map: {}
[11/06/22 14:59:12] ERROR: unable to download video data: HTTP Error 403: Forbidden
[11/06/22 14:59:12] Traceback (most recent call last):
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1976, in process_info
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1915, in dl
[11/06/22 14:59:12] [debug] System config: []
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\common.py", line 366, in download
[11/06/22 14:59:12] [debug] User config: []
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 351, in real_download
[11/06/22 14:59:12] [debug] Custom config: []
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 116, in establish_connection
[11/06/22 14:59:12] [debug] Command-line args: ['--newline', '-i', '-o', 'C:\\Users\\kenny\\OneDrive\\Documenti\\ytdwnldz\\%(title)s.%(ext)s', '-x', '-v', '--ignore-config', '--hls-prefer-native', 'https://www.youtube.com/playlist?list=PL9wugcAO358wiRp187zS4gCrCaayoEcwj']
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 110, in establish_connection
[11/06/22 14:59:12] [debug] Encodings: locale cp1252, fs mbcs, out cp1252, pref cp1252
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 2288, in urlopen
[11/06/22 14:59:12] [debug] youtube-dl version 2021.12.17
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 470, in open
[11/06/22 14:59:12] [debug] Python version 3.4.4 (CPython) - Windows-10-10.0.22000
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 580, in http_response
[11/06/22 14:59:12] [debug] exe versions: ffmpeg 3.3.2, ffprobe 3.3.2
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 508, in error
[11/06/22 14:59:12] [debug] Proxy map: {}
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 442, in _call_chain
[11/06/22 14:59:12] WARNING: Unable to download webpage: HTTP Error 500: Internal Server Error
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 588, in http_error_default
[11/06/22 14:59:12] ERROR: unable to download video data: HTTP Error 403: Forbidden
[11/06/22 14:59:12] urllib.error.HTTPError: HTTP Error 403: Forbidden
[11/06/22 14:59:12] Traceback (most recent call last):
[11/06/22 14:59:12] 
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1976, in process_info
[11/06/22 14:59:12] ERROR: unable to download video data: HTTP Error 403: Forbidden
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1915, in dl
[11/06/22 14:59:12] Traceback (most recent call last):
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\common.py", line 366, in download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1976, in process_info
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 351, in real_download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1915, in dl
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 116, in establish_connection
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\common.py", line 366, in download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 110, in establish_connection
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 351, in real_download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 2288, in urlopen
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 116, in establish_connection
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 470, in open
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 110, in establish_connection
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 580, in http_response
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 2288, in urlopen
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 508, in error
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 470, in open
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 442, in _call_chain
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 580, in http_response
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 588, in http_error_default
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 508, in error
[11/06/22 14:59:12] urllib.error.HTTPError: HTTP Error 403: Forbidden
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 442, in _call_chain
[11/06/22 14:59:12] 
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 588, in http_error_default
[11/06/22 14:59:12] urllib.error.HTTPError: HTTP Error 403: Forbidden
[11/06/22 14:59:12] 
[11/06/22 14:59:12] ERROR: unable to download video data: HTTP Error 403: Forbidden
[11/06/22 14:59:12] Traceback (most recent call last):
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1976, in process_info
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 1915, in dl
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\common.py", line 366, in download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 351, in real_download
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 116, in establish_connection
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\downloader\http.py", line 110, in establish_connection
[11/06/22 14:59:12]   File "C:\Users\dst\AppData\Roaming\Build archive\youtube-dl\ytdl-org\tmpupik7c6w\build\youtube_dl\YoutubeDL.py", line 2288, in urlopen
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 470, in open
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 580, in http_response
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 508, in error
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 442, in _call_chain
[11/06/22 14:59:12]   File "C:\Python\Python34\lib\urllib\request.py", line 588, in http_error_default
[11/06/22 14:59:12] urllib.error.HTTPError: HTTP Error 403: Forbidden
[11/06/22 14:59:12] 

```

#### What operating system do you use ?

Windows 11

#### List of actions to perform to reproduce the problem:

  1. Copy YouTube playlist link
  2. Paste YouTube playlist onto the box with the text "Enter URLs below" above it
  3. Click Add and start (the cloud with an arrow pointing down inside of it)

#### What is the expected behaviour ?

All videos from the YouTube playlist are downloaded, preferably in a .mp3 format

#### What happens instead ?

Most videos from the YouTube playlist are downloaded but not all of them, the formats vary one from another (.mkv / .mp3 / .webm / .webp / .opus / .m4a)
