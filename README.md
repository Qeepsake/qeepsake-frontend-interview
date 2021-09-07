# Qeepsake Frontend Interview

Welcome to the Qeepsake frontend engineering interview 💻 At Qeepsake we care about critical problem solving skills above all else. You will be given a maximum of one (1) hour to complete the task to the best of your ability, the further you proceed through the task, the harder the requirements become. If you have any questions during the project, feel free to communicate with a Qeepsake tech team member through the pre-established communication channels.

## Key Points

- In the project below you will be given a design specification with product requirements.
- You can complete the tasks in any of the following lanaguges: React, React Native, Swift, Objective-C, Java, Kotolin. If your langauge of choice isn't mentioned here, then please ask a Qeepsake tech team member to pre-approve your choice., then please ask a Qeepsake tech team member to pre-approve your choice.
- Once complete you must upload the project to your Github account, set it to private (!IMPORTANT), and share it with both [NMPHalpern](https://github.com/NMPHalpern) and [lukebrandonfarrell](https://github.com/lukebrandonfarrell).

## Project Details

The aim of the project is to build the following selection and list interface in the langauge / framework of your choice.

<img width="375" alt="Screenshot 2021-09-06 at 14 47 21" src="https://user-images.githubusercontent.com/18139277/132219807-0f780b13-f8e6-417d-bc52-625eadfcf1c5.png">

Figma: https://www.figma.com/file/flr1dosD8GJ2xxCTy7K5Wc/Qeepsake-Frontend-Interview?node-id=0%3A1

#### Essential Requirements 

- There will be four journals: Sadie, Isabella, Peter and Jonathan. The data for these journals can be found in `journals.json`.
- There will be five milestones which can be found in `milestones.json`.
- Clicking a milestone will allow you to input text (this can be achived by a native Alert or web modal, implementation is up to you).
- After inputting text the milestone will receive a purple ribbon with the month and year it was answered:<img width="86" alt="Screenshot 2021-09-06 at 14 25 42" src="https://user-images.githubusercontent.com/18139277/132217245-6442634f-706b-4ad1-a43b-fe45ed87d3db.png">. Don't worry, you don't need to display the text anywhere.
- Each list of milestones is seperate per journal. For example, if you answer the first milestone in the journal of Isabella, then the purple ribbon should not be present on the first milestone of any other journal.
- If a milestone has a property of `locked: true` then the description text should say "Upgrade to unlock milestone" and when clicked an Alert should appear to let you know it is locked.

#### Bonus Reequirements (only if you have extra time)

- Are you able to animate the list when switching between journals?
- We have had a new user request for support to re-order milestones. Are you able to implement drag to re-order on the list? And maintain the order after a refresh of the application?

The requirements of the project are intentially vauge as we want to allow space for creativity, building better solutions instead of following the instructions verbatim. Use the requirements as a guideline, but don't be afraid to provide out of the box solutions, and to go further than the requiremets in your project.

## Getting Started

You have one hour to complete this exercise.

- If you are using React Native then you just want to init a fresh react native application and go from there: `npx react-native init AwesomeProject` (https://reactnative.dev/docs/environment-setup).
- If you are using React then feel free to use the toolset you are most confortable with: [create-react-app](https://github.com/facebook/create-react-app), [next.js](https://nextjs.org/) etc.

Once you have completed your project, as stated above, upload to your Github, set to private, and add both [NMPHalpern](https://github.com/NMPHalpern) and [lukebrandonfarrell](https://github.com/lukebrandonfarrell). Please also include instructions on how to run your project, if you didn't use React Native or create-react-app.
