# androidfaqs
Sumarization of Routine Trick/Configuration/Snippets


- How to avoid __ViewPager__ from destroy __Fragment__ views?
  - Change the offset (thresholder) of how many views he can hold instantiated __ViewPager.setOffscreenPageLimit(3)__

- How can i make __MultiAutoCompleteTextView__ tokenize with other character than comma?
  - Write something like [this](https://github.com/vyscond/androidfaqs/blob/master/TheWayItShouldBeDoneTokenizer.java) so you can simply pass the desireable character for tokenization over the constructor.
