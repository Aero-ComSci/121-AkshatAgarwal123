[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/QKp42A0s)
# 121CAT

1.Follow all of the steps on the [Book](https://pltw.read.inkling.com/a/b/5310c007377c46e28d745961310f0c2e/p/93f2c351e3c34598b8b71bf2ebc40abe)

2. Complete the addigional features:
   ![image](https://github.com/user-attachments/assets/f99d7777-6fea-47e5-bf9a-fc452f835952)

3. Create a video of the app working with all of the additional features. Make the video small enough to render here or upload to a video service witha aviawable link.

5. Choose two snapshots of code that demonstrate the algorithm(s) used to implement the additional features. Explain the code in the screenshots.


## Videos

https://github.com/user-attachments/assets/358eb948-352b-40c1-ad27-5fa56acf91ee
https://github.com/user-attachments/assets/125789ba-0497-451e-8521-8f4e634b6498

## Algorithms

<img width="333" alt="Screenshot 2024-10-30 at 5 15 18 AM" src="https://github.com/user-attachments/assets/470e5980-5dbc-4c5a-ae99-21a6353694e9">

add_color_stamp: This function picks a random color from a list of colors, changes the turtle’s color to that random color, and then stamps it on the screen. Stamping means it leaves a mark at that spot, like a little colored footprint. Right after stamping, it resets the turtle’s color back to the original and clears the previous stamp so only one mark is left at a time.

random_color = rand.choice(colors): This line uses Python’s random module to pick a random color from a list called colors. The rand.choice(colors) method selects one item from the list each time this function is called. So, if colors contains items like ["red", "blue", "green"], this line will choose one of them randomly and store it in random_color.

spot.fillcolor(random_color): This line sets the turtle's color to random_color, which we just picked randomly from the list. The fillcolor method changes the turtle's color, so whenever it moves or stamps, it will use this color.

spot.stamp(): This command makes the turtle leave an imprint, or "stamp," of its current shape and color at its current position on the screen. Think of it like stamping a piece of paper with a stamp pad—it leaves a mark behind. Here, the stamp is in the random_color chosen in the previous step.

spot.fillcolor(spot_color): After stamping with a random color, this line changes the turtle’s color back to its original color (spot_color). This keeps the turtle looking consistent and prevents it from permanently changing to a random color.

spot.clear(): Finally, this command removes the last stamp the turtle left on the screen. It ensures that only the most recent stamp remains, so the screen doesn’t get cluttered with multiple marks. In programming terms, this "clears" or "refreshes" the previous marks so the game looks neat.



<img width="308" alt="Screenshot 2024-10-30 at 5 15 35 AM" src="https://github.com/user-attachments/assets/fb808242-fada-44ae-9402-c4d9dcccbaef">

change_size: This function picks a random size from a list of sizes and sets the turtle to that size. Each time you click on the turtle, it might be a different size.

new_size = rand.choice(sizes): This line is similar to how we chose a random color before, but here, it selects a random size from a list called sizes. The sizes list might contain numbers like [2, 1.5, 1, 0.5], which represent different sizes for the turtle. The rand.choice(sizes) method picks one of these numbers at random and stores it in new_size.

spot.shapesize(new_size): This line changes the turtle’s size to the randomly selected new_size. The shapesize method sets the turtle’s width and height based on the value of new_size. For example, if new_size is 2, the turtle will be twice its normal size. If it’s 0.5, the turtle will be half its normal size.








