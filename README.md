# OneLineMessage

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


Step 2. Add the dependency

dependencies {
		dependencies {
	        implementation 'com.github.anuj0612:OneLineMessage:0.1’
	}
}