# Neomorph FrameLayout

Neomorphic Design related Android library which is a custom FrameLayout.
Basically, you just put your TextViews and Button inside this FrameLayout and you're good to go!
 
<img src="https://raw.githubusercontent.com/4inodev/Neomorphic-FrameLayout-Android/master/screenshots/light_main.jpg" height="500"> <img src="https://raw.githubusercontent.com/4inodev/Neomorphic-FrameLayout-Android/master/screenshots/light_cp.jpg" height="500"><img src="https://raw.githubusercontent.com/4inodev/Neomorphic-FrameLayout-Android/master/screenshots/dark_main.jpg" height="500">
 
## Gradle Dependency

Add this in your root build.gradle file at the end of repositories:
```java
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add the dependency : 
```java
dependencies {
	    implementation 'com.github.chetankoli1:NeoMorphByCodeWithSk:1.0'    
	}
```
Sync the gradle and that's it! :+1:


## Usage

### XML : 

```xml
<com.codewithsk.androidneomorphframelayout.NeomorphFrameLayout  
  android:layout_width="match_parent"  
  android:layout_height="wrap_content"  
  app:neomorph_view_type="rectangular"  
  app:neomorph_shadow_type="inner"  
  app:neomorph_elevation="8dp"  
  app:neomorph_corner_radius="16dp"  
  app:neomorph_background_color="@color/neomorph_background_color"  
  app:neomorph_shadow_color="@color/neomorph_shadow_color"  
  app:neomorph_highlight_color="@color/neomorph_highlight_color">
```
## Attributes: 
```"neomorph_view_type"``` -  shape type: rectangular or circular <br>
```"neomorph_shadow_type"``` - shadow type: inner or outer <br>
```"neomorph_elevation"``` - dimension value, determines shadow elevation and inner padding <br>
```"neomorph_corner_radius"``` - pretty self-explanatory =) <br>
```"neomorph_background_color"``` - view color <br>
```"neomorph_shadow_color"``` - right-bottom shadow color <br>
```"neomorph_highlight_color"``` - left-top highlight color <br>
```"neomorph_clickable"``` - not used yet <br>
