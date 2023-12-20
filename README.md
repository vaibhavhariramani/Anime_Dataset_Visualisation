# [Anime Dataset](https://vaibhavhariramani.github.io/Anime_Dataset_Visualisation/)

This dataset comes from [Tam Nguyen](https://github.com/tamdrashtri) and [MyAnimeList.net via Kaggle](https://www.kaggle.com/aludosan/myanimelist-anime-dataset-as-20190204). [According to Wikipedia](https://en.wikipedia.org/wiki/MyAnimeList) - "MyAnimeList, often abbreviated as MAL, is an anime and manga social networking and social cataloging application website. The site provides its users with a list-like system to organize and score anime and manga. It facilitates finding users who share similar tastes and provides a large database on anime and manga. The site claims to have 4.4 million anime and 775,000 manga entries. In 2015, the site received 120 million visitors a month."

Anime without rankings or popularity scores were excluded. Producers, genre, and studio were converted from lists to tidy observations, so there will be repetitions of shows with multiple producers, genres, etc. The raw data is also uploaded.

Lots of interesting ways to explore the data this week!

# Get the Data

```
tidy_anime <- readr::read_csv("https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-04-23/tidy_anime.csv")

```

# Data Dictionary

Heads up the dataset is about 97 mb - if you want to free up some space, drop the synopsis and background, they are long strings, or broadcast, premiered, related as they are redundant or less useful.

|variable       |class     |description |
|:--------------|:---------|:-----------|
|animeID        |double    | Anime ID (as in https://myanimelist.net/anime/animeID)          |
|name           |character |anime title - extracted from the site.           |
|title_english  |character | title in English (sometimes is different, sometimes is missing)          |
|title_japanese |character | title in Japanese (if Anime is Chinese or Korean, the title, if available, in the respective language)          |
|title_synonyms |character | other variants of the title         |
|type           |character | anime type (e.g. TV, Movie, OVA)          |
|source         |character | source of anime (i.e original, manga, game, music, visual novel etc.)         |
|producers      |character | producers          |
|genre          |character | genre         |
|studio         |character | studio           |
|episodes       |double    | number of episodes           |
|status         |character | Aired or not aired      |
|airing         |logical   | True/False is still airing          |
|start_date     |double    | Start date (ymd)        |
|end_date       |double    | End date (ymd)        |
|duration       |character | Per episode duration or entire duration, text string        |
|rating         |character | Age rating         |
|score          |double    | Score (higher = better)       |
|scored_by      |double    | Number of users that scored          |
|rank           |double    | Rank - weight according to MyAnimeList formula          |
|popularity     |double    |  based on how many members/users have the respective anime in their list          |
|members        |double    | number members that added this anime in their list         |
|favorites      |double    | number members that favorites these in their list          |
|synopsis       |character | long string with anime synopsis          |
|background     |character | long string with production background and other things          |
|premiered      |character | anime premiered on season/year          |
|broadcast      |character | when is (regularly) broadcasted         |
|related        |character | dictionary: related animes, series, games etc.         |

# Resources 

To learn more about these Resources you can Refer to some of these articles written by Me:-

[https://vaibhavji.medium.com/deep-learning-in-android-using-tensorflow-lite-with-flutter-f6e18994748](https://vaibhavji.medium.com/deep-learning-in-android-using-tensorflow-lite-with-flutter-f6e18994748)


- [Medium](https://medium.com/geeky-bawa)
- [geeky Traveller](https://sites.google.com/view/geeky-traveller/)
- [Blogs](https://github.com/vaibhavhariaramani/blogs)
- [Youtube](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)[![Youtube Badge](https://img.shields.io/badge/-Geeky_Bawa-1ca0f1?style=flat-circle&labelColor=d54b3d&logo=youtube&logoColor=white&link=https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)

### Don't forget to tag us

if you use this repo in  your project don't forget to mention us as Contributer in it . And Don't forget to tag us [Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/),[ instagram](https://www.instagram.com/geeky_baba_/?hl=en),[ facebook](https://www.facebook.com/jayesh.hariramani.3) ,[ twitter](https://www.linkedin.com/in/vaibhav-hariramani-087488186/), [ Github](https://github.com/vaibhavhariaramani) 

============================================================================
# Made with ❤️by Vaibhav Hariramani
#### About me

I am a Machine Learning enthusiast, an Actions on Google Developer, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

[My PortFolio](https://vaibhavhariaramani.github.io/)
You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Email: [vaibhav.hariramani01@gmail.com](mailto:vaibhav.hariramani01@gmail.com)


# Download [THE VAIBHAV HARIRAMANI APP](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk)

# [<img src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/gh-bannner-light.png">](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk) 
<p align='center'>
<a href="https://www.linkedin.com/in/vaibhav-hariramani-087488186/"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/linkedin.png"></a>&nbsp;&nbsp;
<a href="https://twitter.com/vaibhavhariram2"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/twitter.png"></a>&nbsp;&nbsp;
<a href="https://www.instagram.com/vaibhav.hariramani/?hl=en"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/instagram.jpg"></a>&nbsp;&nbsp;
<a href="https://www.buymeacoffee.com/vaibhavJii"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/by-me-a-coffee.png"></a>
<a href="https://wa.me/+917790991077"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/whatsapp.png"></a>&nbsp;&nbsp;
<a href="mailto:vaibhav.hariramani01@gmail.com"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/email.png"></a>&nbsp;&nbsp;
</p>


[<img width="150" align='center' src="https://archive.org/download/download-button-png/download-button-png.png">The Vaibhav Hariramani App (Latest Version) ](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk)

Download [THE VAIBHAV HARIRAMANI APP](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk) consist of Tutorials,Projects,Blogs and Vlogs of our Site developed Using Android Studio with Web View try installing it in your android device.

Happy coding ❤️ .

### Follow me
  
[![Linkedin Badge](https://img.shields.io/badge/-VaibhavHariramani-blue?style=flat-circle&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vaibhav-hariramani-087488186/)](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) [![Instagram Badge](https://img.shields.io/badge/-VaibhavHariramani-e02c73?style=flat-circle&labelColor=e02c73&logo=Instagram&logoColor=white&link=https://www.instagram.com/vaibhav.hariramani/?hl=en)](https://www.instagram.com/vaibhav.hariramani/?hl=en) [![Twitter Badge](https://img.shields.io/badge/-VaibhavHariramani-1ca0f1?style=flat-circle&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/vaibhavhariram2)](https://twitter.com/vaibhavhariram2) [![GitHub Badge]
