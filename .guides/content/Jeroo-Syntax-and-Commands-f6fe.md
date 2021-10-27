---
Jeroo is a text-based coding environment designed to help novices master the basic mechanics of object oriented programming. Solving problems in Jeroo helps one or more kangaroo-like objects (ie, Jeroos) hop around an island. Jeroos can pick flowers, avoid and disarm nets, and stay on dry land (Jeroos cannot swim!) 

![Jeroo Logo](.guides/img/logo.png)

* Limits syntax to emphasize basic computational thinking skills.
* Emphasizes the semantics of control structures like `loops` and `ifs`.
* Allows learners to program using a variety of syntax styles including Java/C#, Python, or Visual Basic style.

### Jeroo Syntax
---
The first step is to create a Jeroo. The following syntax creates and names a new Jeroo, sets it at (1,10) on the grid, facing south, holding 5 flowers:

```
method main(){

Jeroo jim = new Jeroo(1,10,SOUTH,5); 

}
```

**Sample Code #1:** Try this simple command below in the Jeroo code window. 

```
method main(){

Jeroo jim = new Jeroo(9,0,SOUTH,5); // Creates and names new Jeroo, sets Jeroo at (9,0) on grid, facing south, holding 5 flowers
jim.hop(5); // Tells Jeroo to move 5 spaces
jim.turn(LEFT); // Tells Jeroo to change direction

}
```

**Sample Code #2:** Try the following code. 
```
method main(){

Jeroo jim = new Jeroo(14,14,WEST,0); 
jim.hop(5); 
jim.pick();
jim.turn(RIGHT);
jim.hop(6);
jim.plant();
}
```

Run your program with the following buttons. You can **Run continuously** or **Run step-by-step**. Be sure to **Reset** your program between runs. 

![Run Keys](.guides/img/runkeys.png)


### Jeroo Commands
---
In order to view the Jeroo object, it is not enough just to create it. You must give instructions to the Jeroo object in order for it to "move" around the island. Here is a list of basic Jeroo commands that you can give to `Jim` the Jeroo object:

|Command|Parameter|
|:-----:|:-------:|
|`jim.hop(n);`|Where `n` represents the number of units the Jeroo will move forward| 
|`jim.pick();`|Pick a flower from the current location| 
|`jim.toss();`|Toss a flower one space ahead; this disables nets|
|`jim.plant();`|Plant a flower at the current location|
|`jim.turn(D);`|Where `D` represents a relative direction: LEFT or RIGHT|


||| 
**Want more commands?**
There is a complete list of Jeroo commands that can be accessed through the Jeroo environment. Simply select `Help` and then `Language Summary` from the window on the left. 
|||
