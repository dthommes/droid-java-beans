## droid-java-beans
Droid Java Beans are enabling you to port Java code to the Android platform that makes use of the classes in the package **java.beans** that contains a lot of code for reflection.
Don't be afraid - reflection is not so slow on Android as you might think. So read on and get started!

### Check out the Sources
`git clone git://github.com/dthommes/droid-java-beans.git`

### License
droid-java-beans is released under version 2.0 of the
[Apache License](http://www.apache.org/licenses/LICENSE-2.0).

## Getting Started
### Prerequisites
You might have a library or other existing code that makes use of the **java.beans** classes. Set it up in an Android Project.

### Link to droid-java-beans
Download **droid-java-beans.jar** (later on will be published in maven central repository) and link it to your project.

### Refactor your existing code
As it is not allowed on Android to introduce new classes in the **java.beans** package, droid-java-beans use the package **org.droid.java.beans** but the same class names. So it should be easy just to replace 'java.beans' imports with 'org.droid.java.beans' imports. Or just let Eclipse organize your imports. Hopefully it will find all required classes under the org.droid package names.

**HAPPY BEANING!**

Daniel