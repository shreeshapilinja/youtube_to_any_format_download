# youtube_to_any_format_download
youtube video url to any format download

<https://vctube.onrender.com/>

URL request <br>
https://vctube.onrender.com/?url=https://youtube.com/somevideo&format=wav

POST request<br>
curl -X POST -d "url=https://youtube.com/somevideo&format=wav" -o output.wav https://vctube.onrender.com/


GET request<br>
curl -o output.wav https://vctube.onrender.com/?url=https://youtube.com/somevideo&format=wav 
