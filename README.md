## Red Dead Redemption 2 Vulkan API  
### Asus TUF FX505DY 30fps with best quality settings.

#### My Specs:  
* CPU: AMD Ryzen 3550h  
* GPU: AMD RX560X 4GB  
* RAM: 16GB  (Deafult 8GB)  
* Storage: 120GB SSD, 1TB HDD (Game on HDD)  

### Installation
* Copy the `system.xml`  file to "C:\Users\\{username}\Documents\Rockstar Games\Red Dead Redemption 2\Settings\" and replace the existing file.  

### AIM
* To get 30fps with the best visual quality possible with Ultra Textures.    

#### Note:  
* The Ingame Benchmark will still show drops in FPS to 25-28 at Saint Denis police chase part.
* Setting can also be used for systems with similar specs like Acer Nitro.  
* I would recommend to keep the Vsync to half. Reasons:  
  * Enabling Half Vsync gives a stable 30FPS which is pretty better than having a variable fps from 30-40.  
    Game will always look smoother when vsync is half.
  * It also saves power and also reduces GPU temprature. Which will give us head room for overclocking the GPU.

### What I Did?
* Went to Saint Denis (The Most GPU Hungry Location in RDR2).  
* Set all my setting to LOW.
* Increased the settings one at a time to find the sweet spot.   
* Some Settings Doesn't change anything visually but lowering them still provides performance still.  
  eg: Water Refraction, High only changes the Visuals very little that you won't even notice, is set to low. 
* The resolution is 1080p but the resolution scale is set to x0.916.  
  This doesn't create any visual quality drop that big. But I increased TAA Sharpening to 100% to compliment this.  
  You can turn off Resolution scale, will greatly impact performance for a very small visual quality.  
* Reflection Quality is LOW as it greatly impacts performance and you dont see any reflective surface ingame anyway other than building windows.
  This doesn't affect water quality. It is set to medium.
* Everything else that doesn't impact the games visual quality, but takes up GPU performance is set to low or OFF.  
* set Vsync Half to get a stable 30FPS.  

### What you can do?
* You can REDUCE the Following settings for better FPS with reduced quality.
	* Resolution or Resolution scale. (less than x0.800 is Visually BAD, but huge performance gain)  
	* Texture Quality to High. (Visually OK, very little performance gain)  
	* SSAO/Shadow (Visually BAD, Very little performance gain)    
* You can INCREASE the following settings for a little performance impact (Only do this if you are overclocking):
	* Water Reflection : High (5FPS lost, but doesn't matter in forrest as there is 40+ FPS and in city there is no huge water)
	* Anisotrphic Filtering : x16 (Min Fps lost, but doesn't have any big noticable visual change)
	* Soft Shadows : Medium/High (Personal preference, as it makes the shadows too blurry and low quality. Affect 3FPS.) 
	* Resolution Scale : Off (high FPS impact but for only good visual clarity)  
	  * Other best option is to set Radeon Sharpening to 100% in Radeon Settings (No Performance impact but visually good).

### Other Settings 
* In Radeon settings (update to the latest), change this following settings:
	* Radeon Anti-Lag : Off  
	* Radeon Enchanced Sync: Disabled
	* Wait for vertical refresh : Always Off
	* Anti-Aliasing : Use Application Settings
	* Anti-Aliasing Method : Multisampling
	* Morphological Anti-Aliasing : Disabled
	* Texture Filtering Quality : Performance
	* Tessellation Mode : AMD Optimized
	* Reset Shader Cache.
* Overclock GPU. Use [this](https://youtu.be/y_aTt1zKYLw) guide. Increases atleast 7FPS
* Increase CPU TDP (Optional) with [this](https://youtu.be/4ekZRwxFFGU) guide. Didn't see any huge change on my ryzen 3550h, as it is powerfull enough for RDR2 without any bottleneck.

### Additional FPS Boost  
* Turn OFF windows Game Bar and Game Mode and all video recording settings.  
* If using Discord or Spotify in the background, disable Hardware accelaration in their settings.
