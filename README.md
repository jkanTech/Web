# Android kotlin Mysql Library


[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-yellow.svg)](http://www.apache.org/licenses/LICENSE-2.0)

## Download and Import
### PHP API

Download from [here](https://github.com/jkanTech/crud/raw/master/api/api.zip).


### Android Studio/Gradle



 - Maven:
 
 ```groovy
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
	
	
	

	<dependency>
	    <groupId>com.github.jkanTech</groupId>
	    <artifactId>Crud</artifactId>
	    <version>1.0.1</version>
	</dependency>


 ```
 
 - JitPack.io, add `jitpack.io` repositiory and dependency to your `build.gradle`:
 
 ```groovy
    repositories {
        maven {
            url "https://jitpack.io"
        }
    }
	
    dependencies {
	        implementation 'com.github.jkantech:crud:1.0.2'
		}
 ```
 ## Usage
 
 1. Download the latest version of the API
 2. Unzip it in your server directory
 3. Go to the api/query/v1/database folder
 4. Open the config.php file
 5. Put the database username, password and database name
 
  ```groovy
  <?php
$DB_USER = "root";//Data base user
$DB_PASS = "root"; // Date base user pass
$DB_DATABASE = "crudexample"; //Data base name
   
  ```
   
### Android Studio

 ```groovy
    repositories {
        maven {
            url "https://jitpack.io"
        }
    }
	
    dependencies {
	        implementation 'com.github.jkantech:crud:1.0.2'
		}
 ```


<h2 id="examples">Examples :eyes:</h2>

Download the [Crud Example App]() or look at the [source code](https://github.com/jkanTech/crud/tree/master/CrudExample).

[![ScreenShot](https://github.com/PhilJay/MPAndroidChart/blob/master/design/video_thumbnail.png)](https://www.youtube.com/watch?v=ufaK_Hd6BpI)

<br/>
 
## Authors

* **Jonas Kaninda**  - [jkanTech](https://github.com/jkantech)


## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
