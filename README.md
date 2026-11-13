# Game Development – Lesson 2: JavaScript Game Development

Let's learn this lesson step by step, just like we did with your C++ lesson. I'll follow your lecturer's PDF and explain every important concept, including the code, in beginner-friendly language.

Our goal: By the end, you should understand JavaScript game development, the game engines, HTML Canvas, and how the example game works.

Your PDF covers four main areas:

1. Is JavaScript good for game development?
2. Popular games that use JavaScript.
3. JavaScript game engines.
4. How to code a game using JavaScript and HTML Canvas.

# TOPIC 1: IS JAVASCRIPT GOOD FOR GAME DEVELOPMENT?

## 1. First, what is JavaScript?

JavaScript is a programming language used to make websites interactive and to create games.

Imagine visiting a website.

You click a button, and something happens.

For example:

- A menu opens.
- A character moves.
- A score increases.
- An animation starts.

JavaScript makes these interactions possible.

In game development, JavaScript can control:

- Player movement.
- Game rules.
- Scoring.
- Animations.
- Collision detection.
- Player interaction.

## 2. Is JavaScript good for game development?

Your lecturer's answer is YES!

However, it depends on the type of game you want to develop.

JavaScript is particularly suitable for:

- Web-based games.
- Mobile games.
- 2D games.
- Browser-based 3D games.

[Simple js Arkanoid game | Devpost](https://images.openai.com/static-rsc-4/sJHifBongBKH_U8ij-GUZZFYx6o_2ZFscRDvDjjshTTts5Xgq_-MVwucLXAmUGl0pefFNAgTocU1SExbkjzmavkAa3gSGUc1DkYs7sVPXI5fx6H0xwK0M41yeWnxHpOILH0qvellz80JyAZY74amStSeeaxdJkeR2q4t5Y0FGhA?purpose=inline)

[Codex の「playwright-interactive」スキルを使ってみた — ブラウザを見ながら AI がゲームを作る新体験（📒プロンプト付）｜Maki@Sunwood.ai.labs](https://images.openai.com/static-rsc-4/XhKXop3AMMxS_nBpnveqEOSgtkxEF1etOkWRxDKhUKFWM2STppYmEr4vr1-QhjQFP_u-LFsBpEGh3LPeAs1p0ckbdOfbvj0KbpS4yBCIf2k_nN4f1Z_EpRrzJxKAg0eiarj9kCjSoYPD0EJPtRAOknEJZomhqO6XCsY4peDFYl8?purpose=inline)

[I built a game with React Native in one week | by Vincent Bocquet | Medium](https://images.openai.com/static-rsc-4/fuSxriM0LB5JwlicQcb6dcWpSTJNZWNNS3ag_ZYnCVJHnMORuxYAD-ZGPnlpHILM9sGBqxu2zWVcnUeT2_6scCI-Lr7s-RyNPwETXdV0v1MCjdfOzpCSrkbyLD92GJo-EvhC7c5V9fcOHJPdShGWJOyqWDtcwlsVJ_3kzzR1Axw?purpose=inline)

10

For example, imagine creating a game that people can play directly in Chrome without installing a separate computer program.

JavaScript is useful for that.

## 3. What are AAA games?

Your PDF mentions games such as Call of Duty and FIFA.

These are examples of AAA games.

AAA games are generally large-scale games that require significant development resources, advanced graphics and complex systems.

Why does your lecturer say JavaScript may struggle with these games?

There are three main reasons.

A. JavaScript is slower than C++ in the comparison made by your notes.

C++ is often preferred for performance-intensive game systems.

B. JavaScript consumes more memory.

Memory is the space a computer uses to store information while programs are running.

C. Advanced games require heavy GPU calculations.

Let's understand GPU first.

## 4. What is a GPU?

GPU stands for Graphics Processing Unit.

It is a processor designed to handle many graphics-related calculations.

Imagine a 3D football game.

The computer must calculate:

- Player appearances.
- Stadium lighting.
- Shadows.
- Textures.
- Ball movement.
- Different objects on the screen.

The GPU helps process graphics efficiently.

[Video Graphics card with powerful GPU on white background. Professional video card for computer.](https://images.openai.com/static-rsc-4/akarDMJiJvinI2CL1itBiUOJbc7lrmUWoOhThnWoqBRlveHdNdbu8IbCHF9U2dTN5ybKumsNcSvTnssU6-yeQiEo52wcTp8MQ1lMwZ_SIYlQDPJCg93shNjfm5awDuMeI0Yq2fbU6lbMQlNkdj32B1FnmD8hiWk-9aFPpehDHJjC-aGBthRwFlryPjy72aTL?purpose=inline)

Your PDF explains that GPUs are powerful because they use parallel computing.

## 5. What is parallel computing?

This is an important concept.

Parallel computing means dividing a large problem into smaller tasks that can be processed at the same time.

Imagine you have 100 calculations to complete.

You have two approaches:

Approach A: One worker

One worker completes all 100 calculations, one after another.

Approach B: Multiple workers

Several workers share the work and complete different calculations simultaneously.

The second approach represents the basic idea of parallel computing.

[Why GPUs? — Introduction to GPU Programming  documentation](https://images.openai.com/static-rsc-4/APRlmIxHrZDitB6Z8NKJajZReB8aVAH8sqT6zgK6ilrPwWtLJ1BHQTi8JD0ELypq5o5mhg_ZmHocT91gQ7OlFn9-wfBGzv8N_ugGAp2CkMdDRz3atqOldelLm3jzZQBg7wTNFtG5UQ0QkVlYGbOhdra0ISpPsb1IkRPoCKBUj0I?purpose=inline)

[enccs.github.io](https://enccs.github.io/intro-gpu-programming/1-gpu-history/?utm_source=chatgpt.com)

Your PDF compares CPUs and GPUs.

| CPU                                       | GPU                                         |
| ----------------------------------------- | ------------------------------------------- |
| Central Processing Unit                   | Graphics Processing Unit                    |
| Handles a wide variety of tasks           | Specializes in parallel processing          |
| Good at sequential and interactive tasks  | Handles many calculations simultaneously    |
| Essential for general computer operations | Particularly useful for graphics processing |

Example:

A CPU can handle a sequence of instructions such as responding to your keyboard.

A GPU can process many graphics operations at once, such as calculating lighting and rendering shapes.

CAT POINT

- GPU = Graphics Processing Unit.
- CPU = Central Processing Unit.
- Parallel computing = Processing multiple tasks simultaneously.
- JavaScript is particularly suitable for web-based and mobile games.

# TOPIC 2: POPULAR GAMES THAT USE JAVASCRIPT

Your lecturer gives three examples.

## 1. Tower Building

[Tower Block - Casual game - Play Free Online | MyMoneyRain](https://images.openai.com/static-rsc-4/jHonX6yyUMpzu_bKivzhS7SB4pZtvYTBvWaSBsx7rZbd1HPPcp1N75ZNpQWJVI360Dmzsb5ottbTBLc6OBgLLkVqrDiZKlG6Sh91okB67wXPqQZHSXN25lTYPuGBy9Pd7tMQ6IFYyoKMqoT39LRSUdHMxBFxATWl4MzdjIV3t6A?purpose=inline)

[mymoneyrain.com](https://mymoneyrain.com/games/tower-block-casual-game?utm_source=chatgpt.com)

This is a game where players stack blocks to create a tall tower.

Why is it important?

It demonstrates how JavaScript can be used to create interactive games.

Your PDF also mentions that developers can browse, fork and clone its GitHub repository.

Let's understand these terms:

- Browse: View the project's code.
- Fork: Create your own copy of someone else's GitHub repository.
- Clone: Download a repository to your computer.

## 2. Polycraft

[Html Canvas Games Examples at Carolyn Pless blog](https://images.openai.com/static-rsc-4/1ITJnGxSRdbyuXCdc3W8rFmi11OXVbR4pavW0mmnyL8m-gX45IEwS3xW0RsrhYy4wV4CAkgXHXlD35uXkDjneVQ6otCMDX1_jB5LT3DZ9ni8SGRUY16drVKZoqzMDsW97USZljkrRrABHDQqg_UWiuRfPzzLJlzQpeO95VS7Po4?purpose=inline)

[storage.googleapis.com](https://storage.googleapis.com/dgvjbxxdtnskye/html-canvas-games-examples.html?utm_source=chatgpt.com)

Polycraft is a 3D browser game.

Your notes describe features such as:

- Adventure.
- Exploration.
- Base-building.
- Gathering.
- Crafting.
- Fighting.

Why is this example important?

It shows that JavaScript can be used for more than simple 2D games. It can also be used to create 3D browser games.

## 3. Words With Friends 2

[Words with Friends 2 🎮 Download Game Search Engine](https://images.openai.com/static-rsc-4/VA8pZyIIcc3x-RUdTcSqXQ7o-K4LFj0bK--fQDTjJAR0L0RaNhJ56wXDgpzAdu2xVTjCKzX3aITcdJsfHx_u2PPOCl6Mhju8tcJWGIEU2a9rtNs2DY6PHV7jN8vnYpyZzjZzvKRdwier9hCH2aGlrmxxQlyMQjCQ0QsTCjADvCE?purpose=inline)

[beamngdrive.net](https://beamngdrive.net/words-with-friends-2-links-search?utm_source=chatgpt.com)

This is a mobile word game.

Your lecturer explains that it uses React Native.

What is React Native?

React Native is a framework that uses JavaScript to develop mobile applications.

The advantage mentioned in your PDF is that developers can build applications for multiple platforms using one codebase.

Remember these three examples:

| Game                 | Important feature              |
| -------------------- | ------------------------------ |
| Tower Building       | Stacking blocks                |
| Polycraft            | 3D browser adventure           |
| Words With Friends 2 | Mobile game using React Native |

# TOPIC 3: JAVASCRIPT GAME ENGINES

## 1. What is a game engine?

A game engine is software that provides tools for developing video games.

Imagine you want to build a house.

You need tools such as:

- A hammer.
- A saw.
- A measuring tape.

Similarly, when creating a game, developers need tools for:

- Graphics.
- Sound.
- Animations.
- Physics.

A game engine helps provide these tools.

[NeoAxis Engine | NeoAxis – Versatile Real-Time 3D and 2D Platform](https://images.openai.com/static-rsc-4/IJTcs05w4SchPSzm5pY57EvihJPtUaUBm9wP-YxV3BCuEj1bPW_r8dGU__LMB2BKx_vxmakONCPjzPdZ20Pq-u46yt5iw3Ly8ZwvXKq6vqhQEvMtjwPlnKi-kVAZ0JfBSvtrIR5VRr008-ouoS3IILFJjsAnhSzyL6SGbhYESN8?purpose=inline)

[neoaxis.com](https://www.neoaxis.com/neoaxis/overview/?utm_source=chatgpt.com)

Your lecturer identifies four JavaScript game engines or rendering libraries.

## 2. PixiJS

[Poki for Developers - Reach the world on web](https://images.openai.com/static-rsc-4/9ArPFsUcy3bX0SEi89rhCBuFe9WkB3Vho5r3CJc4DGEgwJ-MdPiC9tt8d3xkv7UG0LDhe9Ow1hlZKVOHTLMIXAUoB1Qj60LDZpndPLYsHuSnZr3M_wU1_Bb2rWit8fUAqlQHyycz_khgDjCjPAz3sPSvhS86Dngdlub9DL9T9SE?purpose=inline)

PixiJS

An open-source 2D rendering engine/library known for speed and a simple API.

Your notes highlight:

- Speed.
- Beautiful API.
- Cross-platform support.
- Open-source development.
- Community support.

What does open-source mean?

It means the source code is available for people to inspect, use and contribute to, under its licence.

## 3. BabylonJS

[Babylon.js Logo PNG Vector (SVG) Free Download](https://images.openai.com/static-rsc-4/7yG5eDApLJKbgdVXIpbYTv6Qzp2Ol_28EnnCPAVubC0RrAthxClcH-pjzUP-ovzAIZCFWJYPXidOmA_C3um5CqLVj2T9qvww3qtdNKjoIVtn1-Td_sInVT-5Yie-dOiL_BgCdq1NtDi3HHSsfaU4YmD6M_6NR4qzBBuFngc4NI0?purpose=inline)

Babylon.js

A rendering library used to create animations and 3D games.

Your notes highlight:

- Powerful tools.
- 3D game development.
- Simple animations.
- Open-source.
- Large developer community.

## 4. Phaser

[Phaser](https://images.openai.com/static-rsc-4/Hyuz9mPpnHpXQ1KlwQoXW8otqpTRGXR364jlUHYKeFVQvV8R_wvoLjsHBcG17cbUn22PhCPmzZML4m5dCXNXrtM9s5XFhcl4Nbif-QBlURoiipqAnsoKkDQaK2bSDo7VJuMcc7IRA5JHIXnbmjpWdlDotT-24h4JeAm3luR3QTw?purpose=inline)

Phaser

A framework used to develop 2D HTML5 games for desktop and mobile.

Your lecturer highlights:

- Desktop support.
- Mobile support.
- 2D game development.
- Plugins.

A plugin is an additional component that provides extra functionality.

## 5. Three.js

[File:Three.js Icon.svg - Wikimedia Commons](https://images.openai.com/static-rsc-4/3IQ7cPoSs10rkMSCB3er-YlNWWbl3LzvXfkGX6c4ZDarZ335jEMbAON39Hnr6x0vW-6VZHQ_esvzvDjcDI8f17iipgDSluY3-EeahXYnSydnVv3gF4f8Z-ZVDvqF0mq1qafNP1eljVkuJVYGxiBXSqCqfCH803tHVG8ChnIW57M?purpose=inline)

Three.js

A JavaScript library used for rendering 3D graphics in web browsers.

Your notes mention:

- It is relatively easy to learn.
- It is popular.
- It has many examples available.
- Its default renderer is WebGL.
- It also supports SVG, Canvas 2D and CSS3D renderers.

## 6. Comparing all four

This table is especially useful for examinations.

| Engine/library | Main purpose            |
| -------------- | ----------------------- |
| PixiJS         | Fast 2D rendering       |
| BabylonJS      | 3D graphics and games   |
| Phaser         | 2D HTML5 games          |
| Three.js       | 3D graphics in browsers |

A simple memory trick:

- PixiJS = 2D.
- BabylonJS = 3D.
- Phaser = 2D games.
- Three.js = 3D graphics.

# TOPIC 4: HOW TO CODE A GAME USING JAVASCRIPT AND HTML CANVAS

MOST IMPORTANT PRACTICAL SECTION

This is the longest part of your PDF. Let's take it slowly because understanding this code will help you with practical programming and examination questions.

## 1. What is HTML Canvas?

Your lecturer introduces something called the Canvas element.

Canvas is an HTML element that allows developers to draw graphics using JavaScript.

Think of it as a blank drawing board.

You can use JavaScript to draw:

- Rectangles.
- Circles.
- Lines.
- Images.
- Game characters.
- Animations.

[How to create shapes with HTML canvas - DEV Community](https://images.openai.com/static-rsc-4/-gnBEMHYbcG0l5WLTfH_m_x8-T3qDVzKSA1P6lOpNOs7YY6-fSHgifARl7Hn2-MPcRywZ1alrBscmA_aZkEPjkgBzLm_cW_sgmqCKtm4hMx0j2TrgBzJRy2xYX690dB7PVNOv2iYLOhEZTtvzBR17SdIHAqTo6JnW5aJ1rEGRls?purpose=inline)

[dev.to](https://dev.to/motuncoded/how-to-create-shapes-with-html-canvas-46k7?utm_source=chatgpt.com)

The HTML element looks like this:

```
<canvas></canvas>
```

This creates a drawing area.

But how do we control what appears inside it?

We use JavaScript.

## 2. Understanding the structure of the game

Your lecturer's program uses three technologies:

| Technology | Responsibility                      |
| ---------- | ----------------------------------- |
| HTML       | Creates the webpage and canvas      |
| CSS        | Styles the canvas                   |
| JavaScript | Controls the game and its behaviour |

Let's look at the first part.

### A. HTML document

```
<!DOCTYPE html>

<html>

<head>

</head>

<body>

</body>

</html>
```

What do these mean?

- `<!DOCTYPE html>` tells the browser that this is an HTML5 document.
- `<html>` contains the entire webpage.
- `<head>` contains information about the webpage.
- `<body>` contains the visible webpage content.

### B. Viewport

Your PDF contains:

```
<meta name="viewport"
content="width=device-width, initial-scale=1.0"/>
```

The viewport is the visible area of a webpage.

This code helps the webpage adjust to the screen width of the device.

For example, a phone and a computer have different screen sizes.

### C. Styling the canvas

Your PDF:

```
canvas {
    border: 1px solid #d3d3d3;
    background-color: #f1f1f1;
}
```

Let's break this down.

`canvas`

Selects the canvas element.

`border`

Adds a boundary around the canvas.

`background-color`

Changes the background colour.

The result is a drawing area with a light-grey background and a border.

## 3. Starting the game

Your PDF contains:

```
<body onload="startGame()">
```

This is important.

What does `onload` mean?

It tells the browser to execute a function after the webpage has finished loading.

In this case, it executes:

```
startGame()
```

That means the game starts when the page loads.

## 4. Declaring game variables

Your lecturer writes:

```
var myGamePiece;

var myObstacles = [];

var myScore;
```

Let's understand each one.

A. `myGamePiece`

This represents the main game object.

In the example, it is a red rectangle.

B. `myObstacles = []`

This creates an empty array.

What is an array?

An array stores multiple values in one variable.

For example:

```
var numbers = [1, 2, 3, 4];
```

In this game, the array stores the obstacles that appear.

C. `myScore`

This variable represents the game's score display.

Remember:

- `var` declares a variable.
- creates an array.
- `=` assigns a value.

## 5. The startGame() function

Your PDF:

```
function startGame() {

    myGamePiece =
        new component(30, 30, "red", 10, 120);

    myGamePiece.gravity = 0.05;

    myScore =
        new component(
            "30px",
            "Consolas",
            "black",
            280,
            40,
            "text"
        );

    myGameArea.start();
}
```

Let's break it into pieces.

### First instruction

```
myGamePiece =
    new component(30, 30, "red", 10, 120);
```

This creates the main game object.

The values represent:

| Value   | Meaning    |
| ------- | ---------- |
| 30      | Width      |
| 30      | Height     |
| `"red"` | Colour     |
| 10      | X position |
| 120     | Y position |

[Canvas Drawing Mdn at Donald Stoltenberg blog](https://images.openai.com/static-rsc-4/t891G_ZW-cU1KA3ndxsu9flgXVzJnPjDAR97tOSQ8t6MMrlKAm8iSWbePsocPlPvJFELUf09-WP1BjYhzGS9h6lh4kYcPBX9yIgN1Zj3E4CzKdvXNzulMKhNwkYoT6P6kjgm5TC0BgQsEh5YSU2_BWzcidpJwjyE92DSgOXvrC0?purpose=inline)

[storage.googleapis.com](https://storage.googleapis.com/dbkldtgzoueeke/canvas-drawing-mdn.html?utm_source=chatgpt.com)

So the program creates a red rectangle measuring 30 by 30 pixels at position X = 10 and Y = 120.

### Second instruction

```
myGamePiece.gravity = 0.05;
```

This gives the game piece gravity.

Gravity is the effect that makes the object move downwards.

Think about dropping a ball. It falls towards the ground.

This line gives the red rectangle similar behaviour.

### Third instruction

```
myScore = new component(
    "30px",
    "Consolas",
    "black",
    280,
    40,
    "text"
);
```

This creates the score display.

Notice the difference:

The first component is a rectangle.

The second component is text.

The `"text"` argument tells the component function to display text rather than a rectangle.

### Final instruction

```
myGameArea.start();
```

This starts the game area.

## 6. Understanding myGameArea

Your lecturer creates an object:

```
var myGameArea = {

    canvas: document.createElement("canvas"),

    start: function() {

        this.canvas.width = 480;

        this.canvas.height = 270;

        this.context =
            this.canvas.getContext("2d");

        document.body.insertBefore(
            this.canvas,
            document.body.childNodes[0]
        );

        this.frameNo = 0;

        this.interval =
            setInterval(updateGameArea, 20);

    }
};
```

This is an important programming concept.

An object is a collection of related properties and functions.

Here, `myGameArea` stores information and operations related to the game area.

Let's understand each instruction.

### A. Creating the canvas

```
canvas: document.createElement("canvas")
```

This creates a canvas element using JavaScript.

The browser creates the canvas without us having to write it directly inside the HTML body.

### B. Setting the width

```
this.canvas.width = 480;
```

The canvas width is 480 pixels.

### C. Setting the height

```
this.canvas.height = 270;
```

The canvas height is 270 pixels.

Your game area

Illustration of the canvas dimensions and initial game objects.

### D. Getting the drawing context

```
this.context = this.canvas.getContext("2d");
```

This is one of the most important lines.

What is a context?

A context provides the tools used to draw on the canvas.

`"2d"` tells the browser that we want a two-dimensional drawing environment.

### E. Inserting the canvas into the webpage

```
document.body.insertBefore(
    this.canvas,
    document.body.childNodes[0]
);
```

This inserts the canvas into the webpage.

Without inserting it into the document, the canvas created in JavaScript would not appear on the page.

### F. Frame number

```
this.frameNo = 0;
```

This initializes the frame counter at zero.

The frame counter helps the program keep track of how many game updates have happened.

### G. setInterval()

```
this.interval =
    setInterval(updateGameArea, 20);
```

This is extremely important.

`setInterval()` repeatedly executes a function after a specified time interval.

Here:

- `updateGameArea` is the function being executed.
- `20` means 20 milliseconds between scheduled executions.

The game therefore attempts approximately 50 updates per second.

Why?

\\[ \frac{1000}{20}=50 \\]

Because one second contains 1,000 milliseconds.

Remember: `setInterval()` repeatedly calls a function after a specified time interval.

## 7. The clear() function

Your PDF:

```
clear: function() {

    this.context.clearRect(
        0,
        0,
        this.canvas.width,
        this.canvas.height
    );

}
```

What does this do?

It clears the previous drawing from the canvas.

Why is that necessary?

Imagine moving a rectangle.

If the computer draws the rectangle at a new position without clearing the old position, you would see many copies of the rectangle.

The screen might look like a trail.

So the game:

1. Clears the previous frame.
2. Calculates new positions.
3. Draws the objects again.

This is part of animation.

# TOPIC 5: THE COMPONENT FUNCTION

This is one of the most important parts of the code.

Your PDF:

```
function component(width, height, color, x, y, type) {

    this.type = type;

    this.score = 0;

    this.width = width;

    this.height = height;

    this.speedX = 0;

    this.speedY = 0;

    this.x = x;

    this.y = y;

    this.gravity = 0;

    this.gravitySpeed = 0;

}
```

## 1. What is a component?

A component represents an object in the game.

For example:

- A red player.
- A green obstacle.
- A score display.

The function is used to create these objects.

## 2. Understanding the parameters

Parameters are the values a function receives.

| Parameter | Meaning             |
| --------- | ------------------- |
| `width`   | Object width        |
| `height`  | Object height       |
| `color`   | Object colour       |
| `x`       | Horizontal position |
| `y`       | Vertical position   |
| `type`    | Type of component   |

For example:

```
new component(30, 30, "red", 10, 120);
```

Creates a red rectangle.

## 3. Understanding `this`

Your PDF uses the keyword:

```
this
```

What does `this` mean?

In this example, `this` refers to the current component object being created.

For example:

```
this.width = width;
```

Means:

Store the supplied width in this component's width property.

Similarly:

```
this.x = x;
this.y = y;
```

Stores the component's position.

## 4. Understanding speedX and speedY

```
this.speedX = 0;

this.speedY = 0;
```

These represent the object's movement speed along two axes.

- `speedX` controls horizontal movement.
- `speedY` controls vertical movement.

For example:

If:

```
this.speedX = 2;
```

The object moves horizontally by 2 units per update.

If:

```
this.speedY = 3;
```

The object moves vertically by 3 units per update.

## 5. Understanding gravity

```
this.gravity = 0;

this.gravitySpeed = 0;
```

These variables help simulate falling.

- `gravity` represents the amount added to the falling speed per update.
- `gravitySpeed` stores the accumulated falling speed.

Imagine a ball falling.

Gravity increases its downward speed over time.

# TOPIC 6: THE UPDATE FUNCTION

Your PDF:

```
this.update = function() {

    ctx = myGameArea.context;

    if (this.type == "text") {

        ctx.font = this.width + " " + this.height;

        ctx.fillStyle = color;

        ctx.fillText(
            this.text,
            this.x,
            this.y
        );

    } else {

        ctx.fillStyle = color;

        ctx.fillRect(
            this.x,
            this.y,
            this.width,
            this.height
        );

    }

};
```

Let's understand this.

The `update()` function draws the component on the canvas.

First:

```
ctx = myGameArea.context;
```

This accesses the canvas drawing context.

`ctx` is simply a common name for context.

### A. Checking whether the component is text

```
if (this.type == "text")
```

This checks whether the component is a text component.

If it is text, the program executes:

```
ctx.font = this.width + " " + this.height;
```

This sets the font information.

In this program, the width and height arguments are being reused to hold the font size and font family.

Then:

```
ctx.fillStyle = color;
```

This sets the drawing colour.

Finally:

```
ctx.fillText(
    this.text,
    this.x,
    this.y
);
```

This displays the text on the canvas.

### B. Drawing a rectangle

If the component is not text, the program executes:

```
ctx.fillStyle = color;
```

This sets the colour.

Then:

```
ctx.fillRect(
    this.x,
    this.y,
    this.width,
    this.height
);
```

This draws a filled rectangle.

The four arguments mean:

1. X position.
2. Y position.
3. Width.
4. Height.

Understanding fillRect()

[canvas draw](https://images.openai.com/static-rsc-4/vuc55e7-QrUcR0Ww0aLTU6CYSSpvJh__j9uADGZ1_YiXmUirTiaaDXFh0qwTR5WA3P1RO881Z5b-o8rdgxXNKARIVTWJLl1Otyl21xOZeuHBYcK97VCTSsdHYnf3gx4_6EwsC25diQfA6zFjeW97jkI130q7TOuElQHmqVOq0zoFBKF5dIKHi2yQNahCwsTQ?purpose=inline)

fillRect(x, y, width, height)

CAT POINT: The `update()` function draws game components. It uses `fillText()` for text and `fillRect()` for rectangles.

# TOPIC 7: MOVING THE OBJECT – newPos()

Your PDF:

```
this.newPos = function() {

    this.gravitySpeed += this.gravity;

    this.x += this.speedX;

    this.y += this.speedY + this.gravitySpeed;

    this.hitBottom();

};
```

This function updates the position of the object.

Let's understand each line.

Line 1:

```
this.gravitySpeed += this.gravity;
```

This increases the falling speed using gravity.

Line 2:

```
this.x += this.speedX;
```

This changes the horizontal position.

Line 3:

```
this.y += this.speedY + this.gravitySpeed;
```

This changes the vertical position.

Line 4:

```
this.hitBottom();
```

This checks whether the object has reached the bottom of the canvas.

Remember:

- X = horizontal movement.
- Y = vertical movement.
- Gravity = downward acceleration in this example.

## TOPIC 8: HITBOTTOM() FUNCTION

Your PDF:

```
this.hitBottom = function() {

    var rockbottom =
        myGameArea.canvas.height - this.height;

    if (this.y > rockbottom) {

        this.y = rockbottom;

        this.gravitySpeed = 0;

    }

};
```

This function prevents the object from falling below the bottom of the game area.

Let's understand.

The canvas height is 270 pixels.

The object height is 30 pixels.

Therefore:

\\[ 270-30=240 \\]

The bottom position of the object must be 240 pixels.

Why?

Because the object itself is 30 pixels tall.

If its top position were 270, the entire object would be below the canvas.

So the program checks:

```
if (this.y > rockbottom)
```

If the object has gone too far down, it sets:

```
this.y = rockbottom;
```

And:

```
this.gravitySpeed = 0;
```

This stops the accumulated downward speed.

Remember: `hitBottom()` prevents the game object from moving beyond the bottom of the canvas.

# TOPIC 9: COLLISION DETECTION – crashWith()

This is another very important concept in game development.

## 1. What is collision detection?

Collision detection means checking whether two objects have touched or overlapped.

Imagine playing a game where:

- You control a red character.
- Green obstacles appear.
- You must avoid hitting them.

The game needs to detect when the red character touches a green obstacle.

[Use object layers of tilemap for collision detection - Phaser 3 - Phaser](https://images.openai.com/static-rsc-4/Ln0IVNDLtw0Zz7mnP4mqwsAPD9eBZJ8wrLpLBI4TbuH-3HUbYsD-PqxzRg6cA20TTsTrJ9ybNn1uIa4zUaiKaLpR3XvyDUsZkibhSKGmn9bNxORGFP-0KOsgYwarTJ1XyMwRkBo_CIO-Dx8Rni2GBZ-bWB9fUWvSPGr6xHPqiVg?purpose=inline)

[phaser.discourse.group](https://phaser.discourse.group/t/use-object-layers-of-tilemap-for-collision-detection/14007?utm_source=chatgpt.com)

Your PDF uses a function called:

```
this.crashWith = function(otherobj) {
```

This function checks whether the current object collides with another object.

## 2. Understanding the code

First:

```
var myleft = this.x;
var myright = this.x + (this.width);

var mytop = this.y;
var mybottom = this.y + (this.height);
```

These lines calculate the boundaries of the current object.

Let's use a rectangle:

- X = 10
- Y = 20
- Width = 30
- Height = 30

The boundaries are:

| Boundary | Calculation | Result |
| -------- | ----------- | ------ |
| Left     | X           | 10     |
| Right    | X + width   | 40     |
| Top      | Y           | 20     |
| Bottom   | Y + height  | 50     |

The program then calculates the boundaries of the other object:

```
var otherleft = otherobj.x;
var otherright = otherobj.x + (otherobj.width);

var othertop = otherobj.y;
var otherbottom = otherobj.y + (otherobj.height);
```

It also creates:

```
var crash = true;
```

This initially assumes that a collision has happened.

But the program checks whether the objects are actually separated.

```
if (
    (mybottom < othertop) ||
    (mytop > otherbottom) ||
    (myright < otherleft) ||
    (myleft > otherright)
) {
    crash = false;
}
```

Let's understand these four conditions.

| Condition             | Meaning                            |
| --------------------- | ---------------------------------- |
| `mybottom < othertop` | First object is above the other    |
| `mytop > otherbottom` | First object is below the other    |
| `myright < otherleft` | First object is left of the other  |
| `myleft > otherright` | First object is right of the other |

If any of these conditions is true, the objects are not overlapping.

Therefore:

```
crash = false;
```

Finally:

```
return crash;
```

The function returns:

- `true` if the rectangles overlap.
- `false` if they do not overlap.

[docs.flatredball.com](https://docs.flatredball.com/flatredball/tutorials/math/rectangle-collision?utm_source=chatgpt.com)

CAT POINT: The `crashWith()` function is used for collision detection between game objects.

# TOPIC 10: updateGameArea() FUNCTION

Now we are getting to the function that brings many parts of the game together.

Your PDF:

```
function updateGameArea() {

    var x, height, gap,
        minHeight, maxHeight,
        minGap, maxGap;
```

This declares variables used to create obstacles.

Let's break down the function.

## 1. Checking collisions

```
for (i = 0; i < myObstacles.length; i += 1) {

    if (myGamePiece.crashWith(myObstacles[i])) {

        return;

    }

}
```

What does this do?

It checks whether the player has collided with any obstacle.

Remember:

- `myObstacles` is an array.
- `myObstacles.length` gives the number of obstacles.
- `for` repeats instructions.
- `crashWith()` checks for collision.
- `return` exits the function.

For example, if there are five obstacles, the program checks each one.

If the player collides with one, the function stops its current update.

## 2. Clearing the game area

```
myGameArea.clear();
```

This clears the previous frame.

The new frame can now be drawn.

## 3. Increasing the frame number

```
myGameArea.frameNo += 1;
```

This increases the frame number by one.

For example:

- First update: 1
- Second update: 2
- Third update: 3

## 4. Creating obstacles

Your lecturer writes:

```
if (
    myGameArea.frameNo == 1 ||
    everyinterval(150)
) {
```

This means obstacles are created:

- During the first frame.
- Whenever the frame counter reaches another interval of 150 frames.

Next:

```
x = myGameArea.canvas.width;
```

This sets the obstacle's starting horizontal position at the right edge of the canvas.

Remember the canvas width is 480 pixels.

Then:

```
minHeight = 20;

maxHeight = 200;
```

This sets the minimum and maximum obstacle heights.

## 5. Generating random heights

Your PDF:

```
height = Math.floor(
    Math.random() *
    (maxHeight - minHeight + 1)
    + minHeight
);
```

This generates a random height between 20 and 200.

Let's understand the functions.

- `Math.random()` generates a random decimal from 0 up to, but not including, 1.
- `Math.floor()` rounds a number down to the nearest integer.

Why is this useful?

Because we don't want every obstacle to have exactly the same height.

Random heights make the game more challenging.

## 6. Creating gaps

Your PDF:

```
minGap = 50;

maxGap = 200;
```

This defines the minimum and maximum gap between obstacles.

Then:

```
gap = Math.floor(
    Math.random() *
    (maxGap - minGap + 1)
    + minGap
);
```

This generates a random gap between 50 and 200.

The game uses these gaps to leave spaces between the upper and lower obstacles.

[Flappy Bird by Ben](https://images.openai.com/static-rsc-4/28yYu4MxdH76nUwbslHB_grUmPa9pi0OF6GHu1kGVx8ZTgeCyluygsFWDeSPlSPgBSY06ND_tViTuF4iyFGyCaW0zZFPsyFSOEOS58I9lDPwLx6ysvg8xy-LcnNZJqWglZNGsfj7-4FqE3_QNcq236-DtSWlinMy9HtS7Nlnr5g?purpose=inline)

[benscr.itch.io](https://benscr.itch.io/flappy-bird?utm_source=chatgpt.com)

## 7. Adding obstacles to the array

Your PDF:

```
myObstacles.push(
    new component(10, height, "green", x, 0)
);
```

This creates the upper green obstacle.

Then:

```
myObstacles.push(
    new component(
        10,
        x - height - gap,
        "green",
        x,
        height + gap
    )
);
```

This creates the lower green obstacle.

What does `push()` mean?

`push()` adds a new element to an array.

Therefore, the game stores the obstacles in `myObstacles`.

Important note about the second obstacle: The expression in your PDF uses `x - height - gap` as the height of the lower obstacle. Since `x` is initially 480, this makes the lower obstacle's height depend on the horizontal canvas position. The intended logic appears to be creating an obstacle below a gap, but the code as printed may need correction to use the canvas height instead.

## 8. Moving the obstacles

Your lecturer writes:

```
for (
    i = 0;
    i < myObstacles.length;
    i += 1
) {

    myObstacles[i].x += -1;

    myObstacles[i].update();

}
```

This code does two things.

First:

```
myObstacles[i].x += -1;
```

Moves each obstacle one pixel to the left per update.

Second:

```
myObstacles[i].update();
```

Draws the obstacle on the canvas.

## 9. Updating the score

Your PDF:

```
myScore.text =
    "SCORE: " + myGameArea.frameNo;

myScore.update();
```

This displays the current frame number as the score.

For example:

```
SCORE: 100
```

Note that this particular example uses the frame count as its score, rather than counting collected objects.

## 10. Updating the player

Finally:

```
myGamePiece.newPos();

myGamePiece.update();
```

These two lines are important.

The first calculates the new position.

The second draws the object in its updated position.

The overall process is:

1. Check collisions.
2. Clear the previous frame.
3. Increase the frame number.
4. Generate obstacles.
5. Move and draw obstacles.
6. Update the score.
7. Calculate the player's position.
8. Draw the player.

# TOPIC 11: THE EVERYINTERVAL() FUNCTION

Your PDF:

```
function everyinterval(n) {

    if ((myGameArea.frameNo / n) % 1 == 0) {
        return true;
    }

    return false;

}
```

This function checks whether the current frame number is divisible by a specified interval.

For example:

```
everyinterval(150)
```

It checks whether the current frame is a multiple of 150.

Examples:

| Frame number | Result |
| ------------ | ------ |
| 100          | False  |
| 150          | True   |
| 200          | False  |
| 300          | True   |
| 450          | True   |

Why is this useful?

It allows the game to generate obstacles at regular intervals.

# TOPIC 12: THE ACCELERATE() FUNCTION

Your PDF:

```
function accelerate(n) {

    myGamePiece.gravity = n;

}
```

This function changes the gravity value of the game piece.

The parameter `n` is the value passed to the function.

For example:

```
accelerate(-0.2);
```

Sets gravity to a negative value.

This makes the player move upwards as the gravity speed changes.

If we use:

```
accelerate(0.05);
```

Gravity becomes positive, making the player fall downwards.

This is how the game allows the player to control upward movement.

# TOPIC 13: THE ACCELERATE BUTTON

At the end of your PDF, we have:

```
<button
    onmousedown="accelerate(-0.2)"
    onmouseup="accelerate(0.05)"
>
    ACCELERATE
</button>
```

Let's understand this carefully.

`button`

Creates a button on the webpage.

`onmousedown`

Runs a function when the mouse button is pressed down.

```
accelerate(-0.2)
```

This makes the game piece move upwards.

`onmouseup`

Runs a function when the mouse button is released.

```
accelerate(0.05)
```

This restores positive gravity, causing the game piece to fall.

The idea is:

[How I Built Flappy Bird in minutes Using AI — With Just 2 Prompts | by Aaleen Mirza | Medium](https://images.openai.com/static-rsc-4/KfN-Kzr_Iok9b59rko9wXfhS4sG82HtRNftLHNtYRuZvp5oEEzrh94YtCnrr_HriSIxygwbYiFcgnhDWwQB-fQz509Hx0XLnyPwLsqLd7OavN4GG4SN2Q193LEx2AG0nBEgBSqnkU0I7RxFwxobagIH5j4YPFDSAQ3O2_JTuClw?purpose=inline)

[aaleenmirza110.medium.com](https://aaleenmirza110.medium.com/how-i-built-flappy-bird-in-minutes-using-ai-in-just-2-prompts-dc481092cad0?utm_source=chatgpt.com)

- Hold the button to move upwards.
- Release the button to allow the object to fall.
- Avoid the obstacles.
- Stay alive as long as possible.

Your lecturer also includes these messages:

```
<p>Use the ACCELERATE button to stay in the air</p>

<p>How long can you stay alive?</p>
```

These provide instructions to the player.

# TOPIC 14: CODE ANALYSIS – IMPORTANT TERMS

Your lecturer concludes the lesson with two definitions.

## 1. Viewport

The viewport is the visible area of a webpage.

For example, when you open a website on your laptop, the area you can see on the screen is your viewport.

The viewport changes depending on the device and screen size.

## 2. Canvas

Canvas is an HTML element used to draw graphics through scripting, usually JavaScript.

It can be used to create:

- Graphs.
- Images.
- Shapes.
- Animations.
- Games.

These are the two definitions your lecturer specifically highlights in the PDF.

# PUTTING THE KNOWLEDGE INTO PRACTICE

Since you're learning game development, let's actually run a small version of the game.

You can use Visual Studio Code and Google Chrome.

## Step 1: Create a project

1. Open Visual Studio Code.
2. Create a folder called `javascript-game`.
3. Inside it, create a file called `index.html`.
4. Open that file.

## Step 2: Write this beginner-friendly game

This is a simplified working example based on your lecturer's game. It demonstrates Canvas, components, gravity, obstacles, collision detection and acceleration.

```

<!DOCTYPE html>
<html>
<head>
    <title>My First JavaScript Game</title>

    <style>
        canvas {
            border: 1px solid black;
            background-color: lightgray;
        }
    </style>
</head>

<body>

<h2>My First Game</h2>

<canvas id="gameCanvas"
        width="480"
        height="270">
</canvas>

<br><br>

<button
    onmousedown="accelerate(-0.2)"
    onmouseup="accelerate(0.05)"
    onmouseleave="accelerate(0.05)"
    ontouchstart="accelerate(-0.2)"
    ontouchend="accelerate(0.05)">
    ACCELERATE
</button>

<script>

const canvas = document.getElementById("gameCanvas");
const ctx = canvas.getContext("2d");

let player = {
    x: 30,
    y: 100,
    width: 30,
    height: 30,
    gravity: 0.05,
    gravitySpeed: 0
};

let obstacles = [
    { x: 200, y: 0, width: 20, height: 100 },
    { x: 200, y: 160, width: 20, height: 110 }
];

let score = 0;
let gameOver = false;

function accelerate(n) {
    player.gravity = n;
}

function crashWith(a, b) {
    return !(
        a.y + a.height < b.y ||
        a.y > b.y + b.height ||
        a.x + a.width < b.x ||
        a.x > b.x + b.width
    );
}

function updateGameArea() {

    if (gameOver) return;

    ctx.clearRect(0, 0, canvas.width, canvas.height);

    player.gravitySpeed += player.gravity;
    player.y += player.gravitySpeed;

    if (player.y < 0) {
        player.y = 0;
        player.gravitySpeed = 0;
    }

    if (player.y + player.height > canvas.height) {
        gameOver = true;
    }

    // Draw player
    ctx.fillStyle = "red";
    ctx.fillRect(
        player.x,
        player.y,
        player.width,
        player.height
    );

    // Draw and move obstacles
    ctx.fillStyle = "green";

    for (let obstacle of obstacles) {

        obstacle.x -= 1;

        ctx.fillRect(
            obstacle.x,
            obstacle.y,
            obstacle.width,
            obstacle.height
        );

        if (crashWith(player, obstacle)) {
            gameOver = true;
        }
    }

    // Display score
    score++;

    ctx.fillStyle = "black";
    ctx.font = "20px Arial";
    ctx.fillText("Score: " + score, 300, 30);

    if (gameOver) {
        ctx.fillText("GAME OVER", 180, 140);
    }
}

setInterval(updateGameArea, 20);

</script>

</body>
</html>

```

## Step 3: Run the game

1. Save your file using `Ctrl + S`.
2. Open the folder containing `index.html`.
3. Double-click `index.html`.
4. Chrome should open the game.
5. Hold the ACCELERATE button to move upwards.

This is a simplified demonstration, not the complete game in your lecturer's PDF.

# FINAL REVISION NOTES

These are the concepts I want you to remember.

| Question                      | Answer                                                                    |
| ----------------------------- | ------------------------------------------------------------------------- |
| What is JavaScript?           | A programming language used to create interactive applications and games. |
| Is JavaScript good for games? | Yes, especially web-based and mobile games.                               |
| What is GPU?                  | Graphics Processing Unit.                                                 |
| What is CPU?                  | Central Processing Unit.                                                  |
| What is parallel computing?   | Processing multiple tasks simultaneously.                                 |
| What is a game engine?        | Software providing tools for game development.                            |
| What is PixiJS?               | A 2D rendering library.                                                   |
| What is BabylonJS?            | A library for 3D graphics and games.                                      |
| What is Phaser?               | A framework for 2D HTML5 games.                                           |
| What is Three.js?             | A library for 3D browser graphics.                                        |
| What is Canvas?               | An HTML element for drawing graphics using scripting.                     |
| What is `getContext("2d")`?   | Gets the 2D drawing context.                                              |
| What is `fillRect()`?         | Draws a filled rectangle.                                                 |
| What is `fillText()`?         | Draws text.                                                               |
| What is `setInterval()`?      | Repeatedly executes a function at specified intervals.                    |
| What is `Math.random()`?      | Generates a random decimal.                                               |
| What is `Math.floor()`?       | Rounds a number down.                                                     |
| What is collision detection?  | Checking whether objects overlap or touch.                                |
| What is `push()`?             | Adds an element to an array.                                              |
| What is `accelerate()`?       | Changes the player's gravity value in this example.                       |

# LET'S TEST YOUR UNDERSTANDING

We'll use the same learning method as your previous lessons: you answer, I mark your answers, explain mistakes and then we continue.

Lesson 2 CAT practice

0/15 answered

1\. Which language is particularly suitable for browser-based games?

A. C++ only

B. JavaScript

C. SQL

D. CSS

2\. What does GPU stand for?

A. General Processing Unit

B. Graphics Processing Unit

C. Game Programming Unit

D. Graphical Personal Utility

3\. What is parallel computing?

A. Processing tasks one at a time only

B. Deleting multiple files

C. Processing multiple tasks simultaneously

D. Running without a CPU

4\. Which library is mainly associated with 3D browser graphics?

A. Three.js

B. Phaser

C. PixiJS

D. React

5\. What is the purpose of HTML Canvas?

A. Store passwords

B. Draw graphics using scripting

C. Create databases

D. Compile C++

6\. What does getContext('2d') do?

A. Creates a database

B. Gets the 2D drawing context

C. Starts the internet

D. Deletes the canvas

7\. What does fillRect() do?

A. Draws a rectangle

B. Draws text

C. Creates an array

D. Checks collision

8\. What is the purpose of setInterval()?

A. Stop all functions

B. Repeatedly execute a function after a time interval

C. Create a new variable

D. Draw a triangle

9\. What does this.x += this.speedX do?

A. Changes horizontal position

B. Changes the colour

C. Changes the height

D. Stops gravity

10\. What is the purpose of crashWith()?

A. Display score

B. Create a canvas

C. Check whether objects collide

D. Generate random numbers

11\. What does Math.random() do?

A. Rounds numbers

B. Generates a random decimal

C. Checks collision

D. Draws graphics

12\. What does push() do in JavaScript?

A. Removes all elements

B. Adds an element to an array

C. Stops a game

D. Changes the screen

13\. What does gravity do in the example game?

A. Makes the object fall

B. Changes its colour

C. Displays the score

D. Creates obstacles

14\. What does onmousedown mean?

A. When the mouse is moved

B. When the mouse button is pressed down

C. When the webpage closes

D. When the keyboard is pressed

15\. What is the viewport?

A. The visible area of a webpage

B. A game character

C. A programming language

D. A graphics card

Submit answers

My recommendation: Don't rush into the next lesson yet. Make sure you understand the `component()`, `update()`, `newPos()`, `crashWith()` and `updateGameArea()` functions. These are the heart of the practical programming section.

We can then build the complete game together, line by line.
This is my first java script game live at https://stephiewahome-hue.github.io/game-project/
