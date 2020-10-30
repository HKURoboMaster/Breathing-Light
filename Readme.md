# Assignment 6 for Automation
## Breathing light
What you are asked to make is a breathing light.
![image](https://github.com/HKURoboMaster/Breathing-Light/blob/master/light.gif)

You should implement the tasks below one by one, and submit the change that achieve the most functions!
(Only fulfill the first task is good enough)
1. Use a switch(_output 0 when closed, 1 when open!!!!!_) to control the on/off of the light

     (About where you can find the labels:

   - The two pdf files and also the developing board itself.

     You should find the label of the switch and the LED yourself. If you cannot find them, you can ask me for help. Apologies that some materials are not in Chinese.)

2. Make the light that will be connected to `PB11` to breath periodically

   （The mechanism of breathing light is change the pulse of PWM periodically.）

3. Make the period to be 2s (1s to brighten and 1s to darken)

## How to hand in your assignment?
- ### 1. Please create a branch under this repository named after you storing your project code.
- ### 2. Please take a short video of you demonstrating the function of your model. Upload you video [here](https://connecthkuhk.sharepoint.com/sites/hkurobomaster2/Shared%20Documents/Training%20-%20Software). The video should also name after you.
### Some hints to help you:
1. use `HAL_Delay(time)` to keep the existing state of the developing board for `time`μs
2. Use ` HAL_GPIO_ReadPin(GPIO_port, GPIO_PIN_id) ` to read the pin.
3. There is no need to create any interrupt, just add your code in the while loop inside `main()`
4. All the techniques you need is taught in the training, so those who didn't come please refer to the slide and video.
5. You will never know what problems you will encounter if you don't practice those theories by yourself!
6. Ask google or me if there's any uncertainty, my email's u35lyc@connect.hku.hk
