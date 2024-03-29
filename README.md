# Rust-Planet-Earth-Map
This is a Planet Earth map, that I created for a game called : Rust.
![image](https://user-images.githubusercontent.com/1374898/188306691-d1462c42-b0d6-4e59-9e65-0a96d0d20909.png)
![image](https://user-images.githubusercontent.com/1374898/188306714-fc8ec0ea-71fb-4874-9995-3314c269d267.png)



File in this Repo are ZIP, download it and extract it.


To add a custom Rust map:

1. Grab that custom map

2. Upload that .map file to Dropbox or another file sharing website.

3. Once uploaded, copy the download link for that custom map. 

4. Go on your server's control panel and click "FTP File Access".

5. In your FTP, click to edit the "rust.properties" file.

6. In this file, locate the "levelURL=" setting. Add your Dropbox custom map download link into this setting.

(ex: levelURL=https://www.dropbox.com/s/<randomcharacters>/<mapname>.map?dl=0 )

7. In the download link, ensure "dl=0" is changed to "dl=1".

8. Next, locate the "serverLevel=" setting. Set this to the serverLevel used when creating your custom map. 

This can be: Procedural Map, Barren, Hapis, Craggy Island, or Savas Island

9. Once done, click "Save File" to save those changes.

10. Finally, exit your FTP and then restart your server to load that custom map.

You have now successfully added a custom map to your Rust server !
