# androidfaqs
Sumarization of Routine Trick/Configuration/Snippets


- How to avoid __ViewPager__ from destroy __Fragment__ views?
  - Change the offset (thresholder) of how many views he can hold instantiated __ViewPager.setOffscreenPageLimit(3)__
