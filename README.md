# tut7ardunino
(Turning Bits into Atoms..... not literally.....)
Title: Automated coffee dispenser

Purpose: To automatically detect and fill a cup with coffee when placed onto a sensor.

Sensors required:
1. Weight Sensor
2. Touch Sensor (2 of them)

Output: Coffee dispenser + Mini conveyor belt

Procedure:
1. Once a cup is placed around the area designated by the 1st touch sensor on one side of the conveyor belt,
   The belt will move the cup under the coffee dispenser, stopping when it hits a 2nd touch sensor around that area.
   
2. Then the coffee will be dispensed into the cup.

3. The weight sensor will note the weight of the cup and will stop the dispenser when the cup
   hits a certain weight corresponding to a certain volume of coffee dispensed.
   
4. After that, the conveyor belt will move the cup back into the original position,
   stopping around the detection area of the 1st touch sensor.
   This step is to avoid possible spillage if the cup is taken away from the coffee dispenser.
