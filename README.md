# androidfaqs
Sumarization of Routine Trick/Configuration/Snippets


- How to avoid __ViewPager__ from destroy __Fragment__ views?
  - Change the offset (thresholder) of how many views he can hold instantiated __ViewPager.setOffscreenPageLimit(3)__

- How can i make __MultiAutoCompleteTextView__ tokenize with other character than comma?
  - Write something like [this](https://github.com/vyscond/androidfaqs/blob/master/TheWayItShouldBeDoneTokenizer.java) so you can simply pass the desireable character for tokenization over the constructor.

- How can i make my Activity do not lose the widget's state on the orientation event?
  - include on your __AndroidManifest__ file lookup for the respective __activity__ tag and add ```android:configChanges="orientation|screenSize"``` to it. Now you __activity__ tag willbe like ```<activity name= ".YourActivity" android:configChanges="orientation|screenSize"/>```, and your widgets will not lose state on orientation changes.
