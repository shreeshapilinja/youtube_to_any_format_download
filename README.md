# youtube_to_any_format_download
youtube video url to any format download

<vctube.pythonanywhere.com>

URL request
https://vctube.pythonanywhere.com/?url=https://youtube.com/somevideo&format=wav

POST request
curl -X POST -d "url=https://youtube.com/somevideo&format=wav" -o output.wav https://vctube.pythonanywhere.com/


GET request
curl -o output.wav https://vctube.pythonanywhere.com/?url=https://youtube.com/somevideo&format=wav 
