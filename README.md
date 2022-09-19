# Hack Technology / Project Attempted
1. AR Application using Unity
2. React-Native Application using Expo and Youtube API
## What you built? 
- We built an AR application mirroring the IKEA Place application by using Unity. The goal of this application was to provide users with various furniture options to place digitally in the space provided. Although this application did not run as expected for us, we were introduced to Unity and C#, along with its various functionalities. Given that this app did not run, we decided to pivot to an React-Native application using Expo and the Youtube API. Although both of us have built web-apps using React, neither of us had worked with React-Native and Expo, so we decided to give it a try. We followed multi-step tutorials for both of these applications

### IKEA AR Unity App
<img width="800" alt="Phone Simulator" src="https://user-images.githubusercontent.com/72226780/191085119-39df8157-f595-4460-8dd6-364ed6ea7d49.png">
<img width="800" alt="Unity" src="https://user-images.githubusercontent.com/72226780/191085207-110c4d8d-c104-412c-8aa1-303329a605b9.png">

### React-Native App
![Search Tab](https://user-images.githubusercontent.com/72226780/191083025-c4077911-8d65-4053-af2c-05013a1e776a.jpeg)
![About Tab](https://user-images.githubusercontent.com/72226780/191083043-839d6530-5db8-4fd9-bff8-e4c4c4a56623.jpeg)
![Detail Tab](https://user-images.githubusercontent.com/72226780/191083059-06f61e6f-1e82-4626-bb4d-5bd10f48f5b4.jpeg)

## Who Did What?
- We both followed the Unity foundations tutorial to ensure we set up the program correctly on each of our workspaces. We then both played around with the LEGO microgame system to get an idea as to what the various parts of Unity are. We pair programmed the first tutorial for the IKEA AR application, then Melissa worked on the second tutorial. We both attempted testing our Unity project and conducted further research on it. For the React-Native application, we first pair programmed, but as we were running into various bugs and issues with dependencies, we decided to each work on our own branches, in constant communication about what progress we were making. Both of us were able to create a fully functional React-Native application that emulated the YouTube search capacities. We decided to use William's application as Melissa's required additional configurations that were causing issues during build time. 

## What you learned
- We first attempted to build an AR application mirroring the IKEA Place application by using Unity. To do so, we followed a multi-step tutorial cited below. Prior to starting the specific tutorial for the IKEA AR app, we completed a general Unity foundations tutorial to ensure we downloaded the necessary installations, including the Unity package and additional modules, such as the iOS and ARFoundations kit. In this foundations tutorial, we were able to learn more about the functionalities of Unity Hub, Unity Editor, and the Package Manager. We were also able to explore using the Unity Editor and built-in LEGO tools to build a custom LEGO microgame. This introduced us to the overall structure of a Unity3D project. Once we had a general understanding of how to create a new project, we began following the IKEA AR app tutorial. In the first tutorial, we applied our knowledge of starting a Unity project from scratch, that is installing all the necessary modules and setting up the scene/hierarchy correctly. We also placed our first AR object, a futon, from SketchFab. Then, in the second tutorial, we added buttons to the screen which required writing additional C# scripts. Neither of us had prior experience with writing in C#, so we learned a bit about coding in this specific programming language. These buttons, chair, futon, and table, served as a type of navigation menu prompting options for the user to place the specific types of furniture in the digital space they were in. At this point, we had attempted to test our project using UnityRemote5, however it did not work as the iOS configurations do not allow for the usage of this application. The furthest point we achieved was a black screen rendering the buttons which signaled that we did have the correct scene set-up, however it was the camera that was not functioning as expected. We conducted further research on how to test a Unity project, as it was not explained in the tutorials we followed, and tried to build and run the project through XCode which also did not work. 

- Following this, we built an React-Native application using Expo and the Youtube API. In this project, we learned how to build a simple react-native application that allows for searching YouTube videos. We worked with new react packages such as vector-icons, stack navigation, and webview, followed by their implementation to improve the app's ui which resulted in us learning about more styling points. We had previously used the Youtube API for a web-application, so this implementation served as a refresher. We were running into issues with installing packages and decided to use yarn instead of npm as our installation tool. Since we had different node versions, we installed a node version manager to facilitate the installations. We were also running into issues with the eslint file, so we decided to omit it for the time being. This project was an introduction to react-native and expo for us and also served as a refresher for working with React and the Youtube API. We also realized that yarn was better to use than npm when we working with Expo, as it resulted in less dependency issues. This app did fully function as expected, allowing us to search Youtube. 

## Authors
- Melissa Valencia
- William Perez


## Acknowledgments
- Unity Essentials: https://learn.unity.com/pathway/unity-essentials, https://learn.unity.com/tutorial/creating-with-lego-tools#
- IKEA AR Tutorials: https://www.youtube.com/watch?v=Ilajw3BR9Bc, https://www.youtube.com/watch?v=-Ad_jfl4Wjk, https://www.youtube.com/watch?v=A7woL0oZCnA&t=83s
- React-Native Tutorial: CS52 Short Assignments https://brunchlabs.notion.site/Schedule-7457e761c83f4b37bbbdca10e045b1d9?p=349ef23e53ac4f74963657c3ffdd2224&pm=s, https://cs52.me/assignments/sa/react-videos/#youtube-api
