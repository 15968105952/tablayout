# tablayout
step1: Add the JitPack repository to your build file

gradle maven sbt leiningen Add it in your root build.gradle at the end of repositories

allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}

step2: Add the dependency

dependencies {
       implementation 'com.github.15968105952:tablayout:v1.0.0'
}
