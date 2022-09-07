**[DEMO LINK](https://care-full.netlify.app/)**

[<img src="./public/Banner.png" />](image.png)

<br/>

---

<br />

## List of Contents

1. [Introduction](#Care-Full)
2. [Demo](#App-Demo)
3. [Features](#features)
4. [Getting Started](#getting-started)
5. [Tech Stack](#tech-stack)
6. [Color Reference](#color-reference)
7. [Running Tests](#running-tests)
8. [The Team](#The-Team)
9. [Appendix](#appendix)

<br/>

---

<br />

# **_Care-Full App_** 🏥🐈🐶🐇

Welcome to Care-Full!

This app was created as part of the School of Code bootcamp, a team of 6 animal lovers came together and began brainstorming what real world problem we wanted to solve. Soon we realised a common issue experienced amongst pet owners - remembering when specific symptoms began and tracking how many times a symptom has been experienced. This then led us onto talking about the difficulty of remembering when you need to administer medication and attend appointments. After lots of ideation and grand ideas, we pulled ourselves back to reality and came up with a viable product that we could plan and produce in only 4 weeks, this is the result.

Problem statement:
Having a sick pet is a stressful situation, on top of our already busy lives, this additional stress can make it difficult to remember the specific details of your pet's illness and their needs.

Solution:
This app aims to alleviate some of the stress that comes with having a sick pet by providing the user with an easy way to track symptoms and medications and facilitate better and more accurate in person communication when visiting the vets.

**This README is for the front-end of the Care-Full app. If you would like to explore the back-end of the app please go to the [backend repository](https://github.com/SchoolOfCode/final-project_back-end-team-con-cat-enate-room-7)**

<br/>

---

<br />

# **_App-Demo_**

[<img src=".\public\demo-home.gif" width="250" height="480"/>](demo-home.gif)
[<img src="./public\demo-addPet.gif" width="250" height="480"/>](demo-addPet.gif)
[<img src="./public\demo-modal.gif" width="250" height="480"/>](demo-modal.gif)
[<img src="./public\demo-colour.gif" width="250" height="480"/>](demo-colour.gif)
<br/>

<br />

## **_Features_** 📱

- Secure login and authorisation provided by Auth0
- Add multiple pets
- Update pet information
- Symptom tracker:
  - Add different symptoms
  - Automatically stores instances of the same symptoms in one convenient location
  - Keep track of the time and date that symptoms occured
- Schedule Tracker & reminder system:
  - Keep track of medications/appointments for your pet
  - Schedule recurring reminders
  - Mark reminders as done - automatically moved into your history page, should you need to check dates
  - Delete reminders that you no longer want/need
- Useful links page directs you to cat/dog friendly resources depending on your pet species
- Toggle for colourblind users
- Modals on every page to provide instructions for the user every step of the way
  <br/>

---

<br />

## **_Getting Started_** ✅

### **Backend**

The backend is deployed on Heroku however if you would like to run locally you will need to follow the steps below.

1. Git clone the backend repository by pasting the following into your terminal:

```bash
  git clone https://github.com/SchoolOfCode/final-project_back-end-team-con-cat-enate-room-7
```

2. Install all required dependencies by running:

```bash
  npm i
```

3. Copy your database (e.g. Heroku) URL into the .env file, following the format:

```bash
 DATABASE_URL = <Database URL goes here>
```

4. Create all tables in your database by running the following scripts in the terminal:

```bash
npm run createSymptomsTable
npm run createRemindersTable
npm run createPetsTable
```

5. To populate the tables you can achieve this by interacting with the front-end, you can either run this locally or host on a hosting platform - we recommend Netlify but you are free to choose your own. For assistance deploying on Netlify please [click here](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/).

6. Finally, to run the server locally use the following script within your terminal:

```bash
  npm run dev
```

### **Front-end**

To run the front-end locally follow the steps below:

1. Git clone the front-end repository by pasting the following into your terminal:

```bash
  git clone https://github.com/SchoolOfCode/final-project_front-end-team-con-cat-enate-room-7
```

2. Remember to navigate to the correct folder: final-project_front-end-team-con-cat-enate-room-7

3. Install all necessary dependencies by running the following command in the terminal:

```bash
  npm i
```

4. Start the app using:

```bash
  npm run dev
```

<br/>

---

<br />

## **_Tech Stack⚙️_**

**Client:** Next.js, CSS, Chakra Component Library, Auth0
</br>
**Server:** Node.js, Express, PostgreSQL, Nanoid
</br>
**Client-side Testing:** React Testing Library, Cypress, Jest
</br>
**Server-side Testing:** Supertest, Jest

<br/>

---

<br />

## **_Colour Reference_** 🖌️

| Colour     | Hex                                                                    |
| ---------- | ---------------------------------------------------------------------- |
| Main       | ![#448FFF](https://via.placeholder.com/15/448FFF/448FFF.png) `#448FFF` |
| secondary  | ![#B2D1FF](https://via.placeholder.com/15/B2D1FF/B2D1FF.png)`#B2D1FF`  |
| Background | ![#fff](https://via.placeholder.com/15/fff/fff.png) `#fff`             |

<br/>

---

<br />

## **_Running Tests_**

To run unit tests, run the following command

```bash
  npm run test
```

<br/>

---

<br />

## **_The Team_**

We are Con-Cat-enate!

- [Christophe Charbonneau-Freeston](https://github.com/St0neofFr33dom)
- [HW Chong](https://github.com/LunaChong)
- [Jack Cherry ](https://github.com/JackC91)
- [Mohamed Ali](https://github.com/CodeNameMoe)
- [Miguel Lamas](https://github.com/MiguelLamas)
- [Rachel Alker](https://github.com/rachelalk)

<br/>

---

<br />

## **_Appendix📝_**

</br>

- [Next.js](https://nextjs.org/)
- [Auth0](https://auth0.com/docs/quickstart/webapp/nextjs/)
- [Chakra UI](https://chakra-ui.com/)
- [Heroku](https://www.heroku.com/)
- [Netlify](https://www.netlify.com/)
