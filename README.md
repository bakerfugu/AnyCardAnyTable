# AnyCardAnyTable

*name still tbd, I think I like TCART for "trading card augmented reality table" a bit better*

**Play on a real table, with "real" cards, with all the conveniences of a digital card library.**

The idea is to project card images onto pieces of white cardstock on a table, using a webcam above the table to track each card. Because the cards are managed digitally, it's easy to change decklists and use alternate card arts. In the future, features like computer-aided shuffling and searching can improve gameplay too!

This repo is just the code, in order to make everything work you'll also need a projector, webcam, blank cardstock, and some way to mount the webcam and projector so they're pointed down at your table. The "cards" also need to have special marks added to them (Aruco codes, similar to QR codes), which is what the software uses to identify each card so it doesn't mix them up.

This project started because I wanted to be able to play with proxied mtg cards but printing out and sleeving the proxies was a pain. Proxying a 100 card singleton deck took hours, and I wanted to make proxies for a 360 card cube too! So of course I threw dozens of hours at a crazy hardware-software project. Let's see how far we can get.
