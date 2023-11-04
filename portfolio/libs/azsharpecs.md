---
layout: imagepage
pagetype: "portfoliopage"
portfoliotype: "libs"
title: "AzSharp.ECS"
thumburl: "/assets/portfolio/azsharpecs/thumb.png"
images:
  - url: "/assets/portfolio/azsharpecs/1.png"
    desc: "Components are any class, commonly registered with just an attribute that specifies the array class to contain the components."
  - url: "/assets/portfolio/azsharpecs/2.png"
    desc: "Event logic is seperated into singleton systems which are also registered through an attribute."
  - url: "/assets/portfolio/azsharpecs/3.png"
    desc: "Update logic is also seperated into singleton systems which get called every tick."
  - url: "/assets/portfolio/azsharpecs/4.png"
    desc: "Functions related to data of components are C# extensions, which allows flexibility of only including them in the nessecary assemblies, which is relevant for tooling or online games with dedicated servers"
    
---
Part of my .NET library collection, <a href="/portfolio/libs/azsharp.html">AzSharp</a><br>
<br>An implementation of an ECS architecture for the .NET platform.
<br>It seperates data, event logic, update logic and even component functions.
<br>It promotes great encapsulation of about everything, granting easy maintenance to large scale projects, such as video games.
<br>
<br>This library has an extension to wrap around the Unity engine, and has been used to create the <a href="/portfolio/gamedev/gemknight.html">Gem Knight</a> project.