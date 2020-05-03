# 100 Days Of Code - Log

## Project: Paris respire app 
[https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 0: April 16, 2020

**Today's Progress**: Worked on notifications, improving the message and I added an error notification. Starting to work on the logo with my designer.

**Thoughts**: Good communication is nice to have.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 1: April 17, 2020

**Today's Progress**: Small work on UI, and I added a link to Paypal for donation.

**Thoughts**: Little by little the bird makes its nest.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 2: April 18, 2020

**Today's Progress**: Big chunk of work made on the module-mpp, moving the shared preferences into the common part without too much difficulties. The api key is not hardcoded anymore and retrieved from the web.

**Thoughts**: null

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 3: April 19, 2020

**Today's Progress**: Another big chunk, I redesigned the MVVM classes to use the Moko-MVVM lib.

**Thoughts**: 
- Moko-MVVM is pretty neat: lifecycle aware and very similar to what is already existing on Android.
- Coroutines exception handling : I think in most cases it's a best solution to use the usual try/catch exception handler instead of a CoroutineExceptionHandler. Indeed, once a coroutine terminates with an exception, the attached CoroutineScope cannot resume another coroutine. [Stackoverflow](https://stackoverflow.com/questions/41581548/kotlin-continue-coroutine-after-exception)

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 4: April 20, 2020

**Today's Progress**: No progress on the TODO list, but I worked on refactoring package names and file names, improving the architecture and fixing a regression in Unit Tests.

**Thoughts**: 
- Putting the Presenter part from the MVP design pattern into the mpp library is unfortunately not possible (due to a reference to MainActivity::class).
- Using an interface is a workaround to mock a class without an existing mocking library for Kotlin multipatform.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 5: April 21, 2020

**Today's Progress**: I improved exception handling related to the network part in the module-mpp, and also the forecast pollution notification message.

**Thoughts**: Think of every possible exception that can be thrown by your IO classes.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 6: April 22, 2020

**Today's Progress**: I fixed some bugs, improved the MVP implementation using data binding, and attached to the pending intent of the alert message the 'tomorrow' tab index. No much progress on what really matters in my TODO list.

**Thoughts**: Intent flags are not that obvious.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 7: April 23, 2020

**Today's Progress**: I did not really write code today, I was more into gathering tutorials about Material design and looking for a library to nicely display the global air quality value (found it! it's [SlimChart](https://github.com/mancj/SlimChart)).

**Thoughts**: Half-day dedicated to tutorials about Android Material design will be necessary.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 8: April 24, 2020

**Today's Progress**: Learning more about material design, built my own Material theme. The content I used for learning:
- [Setting up a Material Components theme for Android](https://medium.com/over-engineering/setting-up-a-material-components-theme-for-android-fbf7774da739): explains the basics and gives useful resources
- [MaterialThemeBuilder](https://github.com/material-components/material-components-android-examples/tree/develop/MaterialThemeBuilder): official project example to help you build your Material theme
- [MDC-101 Android: Material Components (MDC) Basics (Kotlin)](https://codelabs.developers.google.com/codelabs/mdc-101-kotlin/#0): first part of an easy codelab about Android Material Components (buttons and textfields in the first part)

**Thoughts**: Today's acquired knwoledge confirms me that the Android Material Components permit to build a modern UI with much less efforts.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 9: April 25, 2020

**Today's Progress**: I really made progress today on the improved UI, using the SlimChart to display the global index and having ideas for what to do next.

**Thoughts**: SlimChart is a good lib, but because of the lacking quality of the documentation, it was a pain in the a** to make it work.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 10: April 26, 2020

**Today's Progress**: Working on the main fragment style (margins, colors, text)

**Thoughts**: null

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 11: April 27, 2020

**Today's Progress**: I've made a new display for the pollution details, using a two-color circle shape to represent the index of each pollutant.

**Thoughts**: Shape API is kind of weird, I am grateful to stackoverflow to help me make my shape idea possible ;)

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 12: April 28, 2020

**Today's Progress**: I struggled to have an UI which really satisfies me, but after some back and forth the app starts to look like something. I trashed the two-color circle shape I've made yesterday to only use SlimCharts.

**Thoughts**: Sometimes I struggle to have a layout as I want because I don't know the right tools (I discovered today chainstyle constraint and group, the latter is very useful). Need to dig into the subject.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### 1 day break

### Day 13: April 30, 2020

**Today's Progress**: I've been tidying up the pile of ideas I had yesterday, I searched the UI components I'll need to achieve this ideas, and coded a little bit to display a drawable error icon when having any kind of error.

**Thoughts**: Big day tomorrow, I am hunger to implements all the ideas I have!

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 14: May 1, 2020

**Today's Progress**: I implemented a RecyclerView to display the 3 different pollutants. This allows me to add two new features: information on the pollutant thanks to a collapsing textview and the display of the map for the particular pollutant.

**Thoughts**: Feeling a little rusty today. Fist time using ConstraintLayout barrier, it's useful.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 15: May 2, 2020

**Today's Progress**: Ile-de-France global index is now in the RecyclerView. The app displays the map for each 4 indexes inside a DialogFragment.

**Thoughts**: null

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 16: May 3, 2020

**Today's Progress**: Implemented the location permission, with a dialog explaining that the user's privacy is fully respected and the geolocation is not saved or shared. Made small work on the UI and the HTTP request package, fixing bugs and regression, adding a request.

**Thoughts**: null

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 17: May 4, 2020

**Today's Progress**: 

**Thoughts**:

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)
