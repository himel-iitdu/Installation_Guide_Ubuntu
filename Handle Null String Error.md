#randomSpeech.getText().length()

####If the getText() method return a null string, then it'll end up with error
(As length() method don't work on null)

***So We can use***

#randomSpeech.getText()?.length()

####If we use '?' after getText() method, when getText() method return null String, it will just simply return null and don't call the length() method.

