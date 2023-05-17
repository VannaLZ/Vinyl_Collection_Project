<img align="left" width="230" src="https://github.com/VannaLZ/Vinyl_Collection_Project/blob/main/Pictures/Freddy_Vinyl.png" />

# Vinyl_Collection_Project 

<p align="justify">
:wave: Hi there! I recently completed a Data Analytics bootcamp where I gained a strong foundation in <i>Data Analysis</i> and related skills. During the course, we had the opportunity to discuss potential projects with a professor. Initially, I had a different idea in mind, but as I progressed, my interests evolved, and I decided to pursue something I am truly passionate about - <b>music</b> :musical_score: and <b>vinyl</b>🎵.
</p>


<p align='justify'>
Therefore, I started a project on GitHub :octocat: to keep track of my progress and to continue learning and exercising my skills in this field. While the project may not be what I had initially envisioned, the main objective is to use the knowledge I gained from the bootcamp and to dedicate my time to something I am truly interested in. By doing so, I hope to learn new things, refine my skills, and ultimately achieve personal growth. :muscle:.
</p>
<img align="right" width="500" src="https://github.com/VannaLZ/Vinyl_Collection_Project/blob/main/Pictures/Vinyl_Collection.png" />

<p align='justify'>
This project will focus on creating a catalog of my vinyl collection 🎶, which will include various attributes such as artist, album title, release year, and condition. 
</p>
<p align='justify'>
Additionally, I plan to explore different analytical techniques to gain insights into my collection, such as identifying the most popular artists or tracking the value of certain albums :moneybag:.
</p>
<p align='justify'>
I am excited to embark on this project and share my progress with the GitHub community. Stay tuned for updates! :rocket::notes:.
</p>

<details>
<summary>"Data Collection" </summary>
<ol>
  <li>Create lists in <i><a href="https://open.spotify.com/">Spotify</a></i> with all the albums in the collection.
    <ul>
      <li>Use these lists to collect information about tracks such as title, album, time, etc.</li>
    </ul>
  </li>
  <li>Create a list in <i><a href="https://www.discogs.com/">Discogs</a></i> to store information on the vinyl collection.
    <ul>
      <li>Include information on the vinyl's genre, style, recorded studio, recorded year, and more. It can be done directly from the webpage </li>
      <li>The <i><a href="https://www.discogs.com/">Discogs</a></i> gave the opportunity to create <i>ad hoc</i> columns with info that can be downloaded in a CSS format.</li>
    </ul>
  </li>
</ol>
</details>

<details>
<summary>"Discogs API" </summary>
<ol>
  <li>Install Python by downloading and running the installer from the official Python website: <i><a href=https://www.python.org/downloads/">Python</a></i>.</li>
  <li>Install the required libraries by running the following commands in your terminal or command prompt:</li>
  <pre><code>pip install requests
pip install python-dotenv</code></pre>
  <li>Import the necessary modules at the beginning of your Python script using the following code:</li>
  <pre><code>import os</code>
import requests</code></li>
import json</code></li>
from dotenv import load_dotenv</code></pre></li>
  <li>Store your Discogs API credentials in a .env file in the same directory as your Python script. The .env file should contain the following information:</li>
  <pre><code>username=&lt;Discogs_Username&gt;
api_token=&lt;Discogs_Api_Token&gt;</code></pre></li>
  <li>Refer to the Discogs Developer Documentation for information on how to use the Discogs API: <i><a href=https://www.discogs.com/developers/#page:home>Web API Documentation Discogs</a></i>.</li>
</ol>
</details>    
    
<details>
<summary>"Spotify API" </summary>
<ol>
  <li>Install Python by downloading and running the installer from the official Python website: <i><a href=https://www.python.org/downloads/">Python</a></i>.</li>
  <li>Install the required libraries by running the following commands in your terminal or command prompt:</li>
  <pre><code>pip install pandas
pip install spotipy
pip install python-dotenv</code></pre>
  <li>Import the necessary modules at the beginning of your Python script using the following code:</li>
  <pre><code>import sys</code>
import pandas as pd</code></li>
import spotipy</code></li>
from spotipy.oauth2 import SpotifyClientCredentials</code></li>
import os</code></li>
from dotenv import load_dotenv</code></pre></li>
  <li>Store your Spotify API credentials in a .env file in the same directory as your Python script. The .env file should contain the following information:</li>
  <pre><code>client_id=&lt;your_client_id&gt;
client_secret=&lt;your_client_secret&gt;</code></pre></li>
  <li>Refer to the Spotify Developer Documentation for information on how to use the Spotify API: <i><a href=https://developer.spotify.com/documentation/web-api>Web API Documentation Spotify</a></i>.</li>
</ol>
</details>    
    
<p align='justify'>
:construction::construction::construction_worker::hammer_and_wrench:"Work in Progress":hammer_and_wrench::construction_worker::construction::construction:
</p>  
    
<p>
    <img align="left" width="100" src="https://media.giphy.com/media/SkWgtdk744JGXwKrhV/giphy.gif" alt="Data exploration">
    <img align="left" width="100" src="https://media.giphy.com/media/SkWgtdk744JGXwKrhV/giphy.gif" alt="Data exploration">
    <img align="left" width="100" src="https://media.giphy.com/media/SkWgtdk744JGXwKrhV/giphy.gif" alt="Data exploration">
</p>

    

