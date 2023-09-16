# Portfolio-Project-flascards

+ The app has three slices: Topics Slice, Quizzes Slice, and Cards Slice.
+ Each slice’s state has an object storing all the topics/quizzes/cards keyed by their id.
+ This allows for quick retrieval of an object’s information whenever you need to look it up.
+ Each individual quiz has a topicId value corresponding to an individual topic in state.
+ Each topic has a quizIds array corresponding to the associated quizzes in state.
