# 100 Days Of Code - Log

## Project: Paris respire app 
[https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 0: April 16, 2020

**Today's Progress**: Working on notifications, improving the message and I add an error notification. Starting to work on the logo with my designer.

**Thoughts**: Good communication is nice.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 1: April 17, 2020

**Today's Progress**: Small work on UI, and I added a link to Paypal donation.

**Thoughts**: Little by little the bird makes its nest.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 2: April 18, 2020

**Today's Progress**: Big chunk of work made on the module-mpp, moving the shared preferences on the common part without too much difficulties. The api key is not hardcoded anymore and retrieved from the web.

**Thoughts**: null

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 3: April 19, 2020

**Today's Progress**: Another big chunk, I redesigned the MVVM classes to use the Moko-MVVM lib.

**Thoughts**: 
- Moko-MVVM is pretty neat: lifecycle aware and very similar to what is already existing on Android.
- Coroutines exception handling : I think in most cases it's a best solution to use the usual try/catch exception handler instead of a CoroutineExceptionHandler. Indeed, once a coroutine terminates with an exception, the attached CoroutineScope cannot resume another coroutine. [Stackoverflow](https://stackoverflow.com/questions/41581548/kotlin-continue-coroutine-after-exception)

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 4: April 20, 2020

**Today's Progress**: No progress on the TODO list, but I worked on refactoring package names and file names, improving the architecture and fixing a regression on Unit Tests.

**Thoughts**: 
- Putting the Presenter part from the MVP design pattern into the mpp library is unfortunately not possible.
- Using an interface is a workaround to mock a class without an existing mocking library for Kotlin multipatform.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 5: April 21, 2020

**Today's Progress**: I improved exception handling related to the network part in module-mpp, and the forecast pollution notification message.

**Thoughts**: Think of every possible exception that can be thrown by your IO classes.

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)

### Day 6: April 22, 2020

**Today's Progress**: 

**Thoughts**: 

**Link to work**: [https://github.com/alan-camilo/paris-respire-app](https://github.com/alan-camilo/paris-respire-app)
