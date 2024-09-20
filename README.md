// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCcszxzIuPXWDW0ppSZ-SRKbrUQgahW-ro",
  authDomain: "atomsoft-64b5f.firebaseapp.com",
  projectId: "atomsoft-64b5f",
  storageBucket: "atomsoft-64b5f.appspot.com",
  messagingSenderId: "863432500121",
  appId: "1:863432500121:web:c6904b45367df908f4a908",
  measurementId: "G-GBY3TT3V3C"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
