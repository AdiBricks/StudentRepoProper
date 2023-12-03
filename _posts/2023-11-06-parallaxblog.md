---
toc: true
comments: true
title: Parallax Blog
layout: post
description: parallax blog, how I did the parallaax
courses: { csp: {week: 10}}
type: tangibles
---


function changeBackground() {  
    This code defines the function change abckground to change the background in order ot create the proper parallex affect
sections.forEach((section) => { 
    This code iterates through parallax backgrounds
if (rect.top <= window.innerHeight * 0.5 && rect.bottom >= window.innerHeight * 0.5) { 
    Check if the top is halfway visible
                       const bg = section.getAttribute('data-bg'); // gets images for the background
                       section.style.backgroundImage = `url(${bg})`; // switches when required
                   }
               });
           }
