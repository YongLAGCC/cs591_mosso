<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Mosso logo"></a>
</p>

<h3 align="center">Mosso</h3>

<div align="center">
 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/YongLAGCC/cs591_mosso/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/YongLAGCC/cs591_mosso/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> A social media based healthy tracking app
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
A social media based healthy tracking app.

- An app that can track your steps and healthy status.
- An app that can make friends and see your friends’ steps.
- An app that can see your friends running and walking near you realtime!
- Because you could not find an app in the real world so far like Mosso; that could track your steps anywhere and anytime,
- that could track others steps anywhere and anytime,
- The app that could make competition with your friends by working steps!


## 🏁 Getting Started <a name = "getting_started"></a>
1. DownLoad our project file. 
2. Open Android Studio and click open an existing Android Studio Project
3. Select MossoApp, click open like the following picture 
![setup3](https://github.com/ZhuyuLICFC/Mosso/blob/master/android/MossoApp/ReadmePic/setup3.png)
### Prerequisites
4. Download our google-services.json file from the link: [downLoad](https://drive.google.com/file/d/1tjB2S6fWJta_bllzeqsN46hhzvpaY6aD/view?usp=sharing)

```
example as the image shows
```

### Installing
5. Drag this google-services.json which has been downloaded to the app folder in android studio
![setup5](https://github.com/ZhuyuLICFC/Mosso/blob/master/android/MossoApp/ReadmePic/setup5.png)
![setup5_2](https://github.com/ZhuyuLICFC/Mosso/blob/master/android/MossoApp/ReadmePic/setup5_2.png)
6. After building successfully, click the run button(suggest use real android device)
![setup6](https://github.com/ZhuyuLICFC/Mosso/blob/master/android/MossoApp/ReadmePic/setup6.png)

```
example as the image shows
```



## 🔧 Running the tests <a name = "tests"></a>

 Notice: The first or second running might crash, just try one more time



### Quick test
1. After running successfully, sign in with an account(suggest builder’s account: yesyong@bu.edu)
2. In steps and calories pattern, download Google fit first on your android device and sign in with the same account( yesyong@bu.edu ) to obtain today’s steps. Only in this way the steps would not be 0.
3. Click the run button, you can start running and see others who are running at the same time.(If not seen, it means no one is running right now)
4. After clicking the run button again to stop running, you can see your running track in the history fragment.
5. You can also chat with our members on our friend fragment.


### And coding style tests

## 🎈 Usage <a name="usage"></a>
- 1, The main page first shows the map, and the user will be shown by a blue dot -- identical to Google Map.
- 2, After the Run button is pressed, the app will go into the Running mode.
- 3, The purple button to the right of the screen controls layers of the map. We provide this button to users to toggle some display preferences, so that users can choose what to be presented on their screen.
- 4, the profile page showing the user’s basic information, and preferences.
- 5, The Stats page shows the user’s steps and calories today, data obtained from Google Fit API.
- 6, In the Friends page the user can view all his/her friends. Friends’ names, emails and their photos are shown in this page.
## 🚀 Deployment <a name = "deployment"></a>
Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>
- [Google Fit API](https://developers.google.com/fit) 
- [Firebase](https://firebase.google.com/) 
- [Material Design](https://material.io/develop) 
- [Redis](https://redis.io/)  

## ✍️ Authors <a name = "authors"></a>
- [@kylelobo](https://github.com/YongLAGCC) - Idea & Initial work

See also the list of [contributors] Please connect yesyong@Bu.edu

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- References
- Google Fit API
https://developers.google.com/fit
- Fit chat view from Github
https://github.com/txusballesteros/fit-chart
- Firebase
https://firebase.google.com/docs
- AWS Lambda
https://aws.amazon.com/lambda/
- Redis
https://redis.io/
- Material Design (inspired us the most)
https://material.io/design/
