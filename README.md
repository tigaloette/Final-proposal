# water usage detector

I propose a vibration detecting device for water saving. It will take input of reading of weather vibration of water tap is detected. When water flow is detected, the device will start counting the time of water usage. This data will be presented visually for water usage.

## Summary

Water over-usage is happening very often in residences. I want to have a device that is able to be installed into a water tap, powered with battery. It will require a fluid detector as input. I will research different types and shapes of detector to find the most-fit detector. In order to visualize the data, I will use JavaScript to use the variable from detector’s length of analog read. The data would be sent via bluetooth to the computer in order to make it wireless.

The goal of this project is to prototype a device that can potentially make the use as a reminder of water usage and thus make an positive environmental impact.


## Component Parts

On the hardware part, I need a Feather board, a breadboard, some wires and alligator clips, a soft case to cover the detector, battery pack (button battery preferred because they are small) and a fluid detector that is bluetooth imbedded(INPUT). 

On the software part, I probably need a dynamic graphic system to visually show the data(OUTPUT). I would also probably need a database to store reported current usage data(DATA). 

### Block Diagram

![water usage detector diagram](file:///Users/zhaohanqing/Desktop/water%20usage%20detector.jpg)

## Challenges

The challenge might be finding the correct way to make connection and the way to read time spent when it’s on. How data is transferred is also another challenge. The combination of soft case and wiring shouldn’t be a big challenge but how batteries are integrated is another challenge too. Software wise, how to make a dynamic visual presentation might also be challenging. 

## Timeline

What parts of the project do you anticipate you will complete in each of the next 5 weeks?

- Week 1: Write proposal, prepare a bluetooth imbedded Adurino. Make sure the proposal is passed by JD.
- Week 2: Preparing (order or borrow from hybrid lab) a vibration detector, and research about other software requirement.
- Week 3: Wire everything up and test if the circuit is connected. Refine the circuit.
- Week 4: Debug and complete the interface.
- Week 5: Present complete project.
