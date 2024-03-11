# actlivitylifeCycle
In this application, we increment the thread counter whenever the Main Activity restarts. This demonstrates that when a new activity (Activity B, Activity C) is opened, and we subsequently return to the previous activity, the onRestart() method is invoked, resulting in an increment of the thread counter by 5.

Conversely, when a Dialog Activity is opened, and we navigate back to the preceding activity, the onRestart() method is not called. Consequently, the thread counter remains unchanged.

Main Activity:

![Screenshot 2024-03-10 230255](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/4c322ea5-baed-46c4-8fd2-f84e7b7d09bd)


Activity B: 

![Screenshot 2024-03-10 230312](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/f6f13817-b43c-4868-85cd-6f42f88e9410)


Thread Counter increased by 5.

![Screenshot 2024-03-10 230328](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/ad7b0178-6a2d-4d36-9167-00f812220f2a)


Activity C:

![Screenshot 2024-03-10 230341](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/54c1fb5a-2de4-43f7-a7df-0e8bb9117753)


Thread Counter increased by 10.

![Screenshot 2024-03-10 230356](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/242b155c-0947-4b3d-b2d9-fa798cb8d644)


Dialog popup:

![Screenshot 2024-03-10 230411](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/15b6f4f5-cdb9-4d45-b734-2004e63d056a)







