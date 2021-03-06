# Mobile Flash Cards

### React Developer Nanodegree Project

This is a mobile application (Android and iOS) that allows users to study collections of flashcards. 
The app will allow users to create different categories of flashcards called "DECKS", add "FLASHCARDS" to those decks, then take quizzes on those decks.

## Set up
This project has been developed and tested using [Expo Snack](https://snack.expo.io/). 
You can preview the changes directly on your phone or tablet by clicking the **Run** button or use the simulator by clicking **Tap to Play**.

## Project Installation
	* Install `yarn` using `yarn install` or `npm` using `npm install`.
	* Install `expo` using `npm install expo`.

## Project Requirements
	* Allow users to create a deck which can hold an unlimited number of cards.
	* Allow users to add a card to a specific deck.
	* The front of the card should display the question.
	* The back of the card should display the answer.	
	* Users should be able to quiz themselves on a specific deck and receive a score once they're done.
	* Users should receive a notification to remind themselves to study if they haven't already for that day.

## Dependencies
	* expo
	* expo-constants
	* expo-permissions
	* react
	* react-dom
	* react-native
	* react-native-gesture-handler
	* react-native-reanimated
	* react-native-safe-area-context
	* react-native-screens
	* react-native-web
	* react-redux
	* redux
	* redux-thunk
	* @react-native-community/masked-view
	* @react-navigation/bottom-tabs
	* @react-navigation/native
	* @react-navigation/stack

## Devdependencies
	* babel-preset-expo

## Data
AsyncStorage has been used to store our decks and flashcards. 
