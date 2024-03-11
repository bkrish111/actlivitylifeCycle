# actlivitylifeCycle
In this application, we increment the thread counter whenever the Main Activity restarts. This demonstrates that when a new activity (Activity B, Activity C) is opened, and we subsequently return to the previous activity, the onRestart() method is invoked, resulting in an increment of the thread counter by 5.

Conversely, when a Dialog Activity is opened, and we navigate back to the preceding activity, the onRestart() method is not called. Consequently, the thread counter remains unchanged.

Main Activity:

![WhatsApp Image 2024-03-10 at 21 48 08_704e8b0b](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/450aefda-95c8-4fcc-aaed-1dd682729744)

Activity B: 

![WhatsApp Image 2024-03-10 at 21 48 47_d6588d03](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/2090df71-f165-4caf-92b7-892ec017ed15)

Thread Counter increased by 5.

![WhatsApp Image 2024-03-10 at 21 49 10_48bf5367](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/66edac95-c397-4064-be9c-d936faf4c1d4)

Activity C:

![WhatsApp Image 2024-03-10 at 21 49 31_5ce8a481](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/3e91595f-1c08-41e0-83d4-9a71a1a29b8e)

Dialog popup:

![WhatsApp Image 2024-03-10 at 21 51 23_da992f72](https://github.com/bkrish111/actlivitylifeCycle/assets/147780244/e91cfff7-4cfb-44d9-9bf5-0adec10e40f2)






