---
layout: home
title: Home
landing-title: 'Welcome!'
description: null
image: null
author: Zanna
show_tile: false
---
<svg viewbox=0,-35,100,40 height=90vh width=90vw>

  <text stroke=red stroke-dasharray=9,31>hello</text>
  <text stroke=green stroke-dasharray=0,10,9,21>hello</text>
  <text stroke=blue stroke-dasharray=0,20,9,11>hello</text>
  <text stroke=black stroke-dasharray=0,30,9,1>hello</text>
  
  <style>
    text {
      stroke-linejoin:round;
      animation: 5s do linear infinite;
      font-size: 50px;
      fill: none;
    }
    
    @keyframes do {
      from {stroke-dashoffset:0}
      to {stroke-dashoffset:40}
    }
  </style>
</svg>