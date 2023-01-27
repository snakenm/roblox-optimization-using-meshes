# roblox-optimization-using-meshes

In this repostory I'm going to show you how using mesh objects can improve your game optimization.

This is a single car prop using bricks and unions,
![image](https://user-images.githubusercontent.com/46110589/215072194-576f8524-d119-4228-889a-ad346083902f.png)
For each of these cars your computer will have to load **131** parts,  

Now this is a single car prop using only meshes,
![image](https://user-images.githubusercontent.com/46110589/215074602-f8367daa-b8d4-404e-8c3c-59e7f459a495.png)

For each of these your computer will have to load **1** part (the image displays 2 because the baseplate is adding onto the part count),

These are 24 good detail cars which are being used just as scenary without serving any purpose,
![image](https://user-images.githubusercontent.com/46110589/215073011-02a834e6-5dff-4ef0-8020-de77e38e6626.png)
Your computer will have to load **3121** parts just to load 24 parked cars.

**Now**
This is the amount of parked cars you could have by using meshes for props instead of using good detail cars, 
![image](https://user-images.githubusercontent.com/46110589/215071170-7433d5e5-5450-4a95-89ec-90c1af33d7e7.png)
It's **3088** cars, you are never gonna need that many parked cars in a map, but I would personally say that 24 cars would also not be enough to fill the map enough to make it feel like an actual town.

These are **98** cars, we are using 12741 parts just for scenary parked cars, if we were to add a good detail map to this, the count would probably reach 
![image](https://user-images.githubusercontent.com/46110589/215074093-8ae8fa47-4314-40f0-b304-d94d5ba35ea5.png)

>The roblox engine is very CPU expensive and running games smoothly on high graphics requires a very good hardware most of the time, the average person games on computers made for office tasks that don't require high clock CPUs with a lot of cores, as developers our job should be to make our creation as accessible and enjoyable as possible and most of the time there are some optimization tricks that are very easy to implement but just take a bit of effort and they can come with a little sacrifice of detail, but when the game engine is already terribly optimized I would say that for good performance sacrificing detail could be worth it.
