#!/bin/bash

# Update apt cache.
sudo apt-get update

# Install Nginx.
sudo apt-get install -y nginx

# Set the home page.
echo "<html><body><h2>Hello and welcome to my web page! I'm Michael.<br>
I'm currently taking CS135 at CBC and also work in corporate IT.<br>
Before going back to school for computer science I worked in law enforcement for a decade. In my free time, I like to backpack and mountain climb.<br>
You're reading this from a website I created on an Azure Virtual Machine named $(hostname).</h2></body></html>" | sudo tee -a /var/www/html/index.html
