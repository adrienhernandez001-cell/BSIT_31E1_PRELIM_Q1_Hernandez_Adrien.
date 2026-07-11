# Reflection

## Why did you use inheritance?

I used inheritance because Car, Airplane, Boat, and Helicopter are all types of Vehicle. They share a common base class while each has its own implementation of the Move() method.

## Why did you use interfaces?

I used interfaces to represent the abilities of each transport. For example, Car can drive, Airplane can fly, Boat can sail, and Helicopter can both fly and drive.

## Can Helicopter inherit from both Vehicle and Airplane? Why or why not?

No. C# only allows a class to inherit from one base class. Helicopter inherits from Vehicle and implements multiple interfaces instead.

## Why can Helicopter implement both IFlyable and IDriveable?

Because C# allows a class to implement multiple interfaces. This lets Helicopter have both flying and driving capabilities.

## If a Submarine can both sail and dive, how would you design it?

I would make Submarine inherit from Vehicle and implement both ISailable and a new IDiveable interface so it can sail and dive.