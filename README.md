# Footsies: Soccer Training

![](https://i.ibb.co/nMbL6DwM/Footsies-logo.png)

## What is Footsies?
With many an aspiring soccer enthusiast and young player out in the world, there isn't a unified app resource to train oneself in the art of soccer outside of joining a local team or hiring a professional trainer. Footsies aims to change that, bringing an easy to use, dynamic, and fun way to build your soccer skillset from scratch and grow consistently over time. Similarly to the popular tabletop game Dungeons and Dragons, Footsies gives its users a visual character sheet of their stats and the means to improve them through practice and challenges. The ideal user for this application is any new aspiring soccer player who wishes to begin establishing a good foundation for their skillset and build from there. However, future version of this application will allow for coach-to-team module customization as well as AI analytics. 


### Team Members
1. **Najee Douglas**
    + UI/UX Designer
    + Documentation Lead
2. **Etienne Laccruche**
    + Code Architect
    + Database Designer
3. **Jean Souverain**
    + Project Manager
    + Code Architect


### Tech Stack
+ React
+ Node.js
+ Firebase (Database and Authorization)
+ Cors
+ Express
+ React Router Dom
+ Recharts

### File Structure
![Image](https://github.com/user-attachments/assets/81efe53b-5e0f-4996-9c2b-f48a8ef93949)

### Instruction to run the app
1. Clone the repository using this link below
```
https://github.com/Suzenko97/Footsies_Soccer_Trainer_App.git
```
2. Open a command terminal and navigate to the project root folder
3. In the root, write or copy/paste this line  
```
npm i
```
then Enter
5. In frontend folder, write or copy/paste the following lines  
```
npm i recharts
```
then Enter  
``` 
npm i font-awesome
```
then Enter

6. In frontend folder create a .env to use for your firebase project authentication keys
```
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_bucket.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```
Be sure to include this file in the .gitignore to avoid security breaches

8. Navigate back to the root folder
9. Boot the application by writing the following line

``` 
npm run dev
```



