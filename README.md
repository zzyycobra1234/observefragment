# ObserveFragment
A set of Fragment classes that implement the Observer pattern.

We believe that a large number of silly bugs occur on Android because of the unwieldy boilerplate that goes into Lifecycle callbacks. 

Simply adding Observer support to fragments enables us to cleanly compartmentalize our code into companion classes that can easily respond to Lifecycle events in the fragment without gumming up its code.

Expect to see these classes used and supported in numerous Level open source projects to come.

# Install
We have started using [Jitpack](http://jitpack.io) for all of our open source libraries, so add the following to your app's build.gradle file:

```groovy
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
  compile 'com.github.Levelmoney:ObserveFragment:1.0.01' // or whatever the latest version is.
}
```
