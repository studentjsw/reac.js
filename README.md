# task-app-appwrite

This is a task app that uses Appwrite as a backend.
Live URL: [https://taskwrite.netlify.app/]
Features - MVE(xample)

 User can create, read, update and delete a task

 User can mark a task as completed

 User can set task due date

 Add a simple UI
 Features - Nice to haves

 User can set task priority

 User can sort tasks

 Support Dark Mode

 AI can generate task descriptions based on task title

 Tasks are searchable

 User can add tasks via voice commands
steps to follow

What is Appwrite?
Appwrite is an open source Backend-as-a-Service (BaaS) platform. A BaaS is a cloud service that packages backend tasks that are typically needed for most applications.

Appwrite offers both a managed database, authentication, functions and storage services and the ability to self-host the entire platform on your own.

Appwrite recently announced a host of new features that makes developers building on their platform lives more straightforward. You can read on that here.https://appwrite.io/init

step 2:How to Set up the React Frontend

npm create vite@latest taskwrite

step3:Run the following command in the same terminal window to add Tailwind to the application:

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

step4:How to Connect to the Appwrite Project

npm i appwrite.
Now, create a .env file at the root of the React application and paste the following variables in it:

VITE_APPWRITE_URL=YOUR-APPWRITE-API-ENDPOINT
VITE_APPWRITE_PROJ_ID=YOUR-APPWRITE-PROJECT-ID

step5:How to Set Up Routing with React Router V6
npm i react-router-do

step6:How to Auto Generate Descriptions with Vercel's AI SDK
To get started, open an integrated terminal and run the following command: npm i ai. This adds the Vercel AI SDK to the React application.

Next, run this command in the terminal: npm i @huggingface/inference to add Hugging Face support. The application will use Hugging Face because you need to pay to get programmatic access to OpenAI.
Once you have token, open the env file and add to it the following line


//replace with your actual token
VITE_HUGGINGFACE_KEY=YOUR-HF-ACCESS-TOKEN

step7:Voice-enable the Application with the React Speech Recognition Package

First, you need to add the dependency and its Typescript helper by running the following commands in an integrated terminal window: npm i react-speech-recognition and npm i @types/react-speech-recognition.

Additionally, run the following command to get the dependency to work properly: npm i regenerator-runtime.
