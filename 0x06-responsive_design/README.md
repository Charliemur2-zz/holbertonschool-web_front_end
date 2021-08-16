# 0x06. Responsive design

Responsive web design
Web Stack programming

Overview
Before talking about media-queries, the backbone of responsive web design. Some basic elements are crucial and actually already implemented in our code. But it’s important to know about these in case you want to add responsive web design to an existing website.

Viewport
The viewport is a meta seen in our first HTML advanced module. The width=device-width forces mobile browsers to adopt their real viewport width.

Code example

```
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
</head>
```

Box-sizing
Code example

```
*, *:before, *:after {
  box-sizing: border-box;
}
```

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Mobile-first design
Media-queries
Sizes to use for responsive web design
How to make a website responsive
The differences between responsive and adaptive design
CSS units that are used to make elements flexible
