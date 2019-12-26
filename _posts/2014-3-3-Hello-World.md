---
layout: post
title: Preparation and resources for CKAD exam
published: true
---

Recently I have successfully passed exam for Certified Kubernetes Application Developer (CKAD) and I would like to share learning tips and tricks as well as resources that helped me prepare and pass the exam.
Resources
Let’s start by looking at resources. I used 3 resource to learn:

- Kubernetes Certified Application Developer (CKAD) with Tests. The course is on Udemy and is designed and delivered by Mumshad Mannambeth. Very well done with lots of hands on exercises that prepare very well for real exam
- Exercises available on GitHub designed by Dimitris-Ilias Gkanatsios.
- Katakoda with ready environments to spin and play around.
- Justmeandopensource youtube channel of with very informative short videos all things kubernetes, including basics.

As always, google around and see what you can find for yourself, but I can definitely recommend those as good starting points. Ok, let’s look at some tips that I found especially useful.
Tip #1: Kubectl alias and bash/zsh completion
During the exam you are required to demonstrate practical knowledge of kubernetes and all this under time pressure. Each second counts, so one of the most important tips that helped me were those about speed.
Make sure to setup alias for kubeclt and bash/zsh completion. This information is available on the kubernetes documentation page. It will help you be much faster with commands and most importantly completion sources pod and other kubernetes objects names that you don’t need to copy or type.

Tip #2: Take advantage of kubernetes documentation
During the exam you can have one additional chrome tab open with kubernetes documentation page, kubernetes blog and GitHub artifacts for the page. It helped me to prepare bookmarks to quickly locate part of YAML to copy and paste to terminal.

Tip #3: Know vim (or nano) editors well
A lot of exam tasks required editing existing YAML files and ability to use vim (in my case) or nano text editors quickly and efficiently is very important. There are plenty of pages with keyboard shortcuts.
‍Tip #4: Questions priority
Each question is “weighted” and for CKAD you have on average 6 minutes per question. If you find yourself stuck, it’s better to note question number in notepad available within the environment and come back to it later
‍Tip #5: My personal “dang it, why didn’t I learn it more?!” moments.
It’s not as much a tip, but rather a reflection on the exam content that made me realize that I should have put more emphasis on certain topics. For me those were:
Network policies, I got stuck on this one.
Different ways of mounting config maps and secrets to pods. I think during the exam I saw all possible ways of mounting those objects to pods, volume mounts with hostPath, using environmental variables, mounts of whole objects, just values etc. It was pretty confusing and I spent a lot on the documentation page to look things up.
‍Tip #6: Stay calm
I’m not sure about you, but performance based exams always make me nervous and stress often gets best of me. It is helpful to remember that CKAD gives you one free retry, so even if you don’t pass first time, don’t worry.
‍I wish you best of luck in getting your CKAD certification!
