# Keyhas
get keyhas for facebook developers

## How to 
**Step 1.** Add the JitPack repository to your build file
```gradle
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  **Step 2.** Add the dependency
```gradle
dependencies {
	        implementation 'com.github.congfandi:Keyhas:fix'
	}
  ```
  **Step 3.** implementation code
```java
 Keyhas.getKey(this);
 ```
  **Step 4.** find keyhas in logcat with keyword *"keyhas"* like image below
![](https://github.com/congfandi/Keyhas/blob/master/Capture.PNG?raw=true)
