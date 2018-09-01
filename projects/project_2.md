---
layout: project
type: project
image: images/M.jpg
title: Simple Circuit
permalink: projects/simple circuit
# All dates must be YYYY-MM-DD format!
date: 2017-4-12
labels:
  - C++
  - GitHub
  - Simple circuit 
summary: A simple circuit sovlver that my team developed in EE205.
---

<div class="ui small rounded images">
img class="ui image" src="../images/simple circuit.png"
</div>

This is a very simple electrical circuit solver create using C++. It used the reduced row echelon equation to analyze the circuit and solve for voltage and current in all possible location of the simple circuit. Since this is a very simple project, we limited the components of the circuit to be resistors and copper wires only. Further improvement such as capacitors and inductors could also be added into the code. The code work just fine, however, the user input was limited to only number.  

For this project, I was the leader and manager of the final product. Due to the limited time we are given, each member are assign we some part of the coding. The codes are shared in icloud9 where everyone can see the change and history when the codes are edit or change. Once the code are completed. I did all the debug and test run to be sure everything are doing what its intended. There are a lot of comments in the code that make it very simple to read and understand. We used around 2 week doing this project. 

Here is some code that illustrates how we read values from the line sensors:

```js
class Component{
    private:
        int value;
        int location;
    public:
        void setValue(int num); //Set value of component
        int getValue(); //Get value of component
        
        void setLocation(int x); //Set location of component
        int getLocation(); //Get location of component

        virtual float getValue();
        virtual int getLocation
};


class Resistor: public Component{
    public:
        virtual float getValue()          //virtual functions
};

class Voltage: public Component{
    public:
        virtual float getValue()          //virtual functions
};

```
