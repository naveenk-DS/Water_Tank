# 💧 Water Tank Problem – Frontend Solution
### 📌 Overview

This project solves the Water Tank (Trapping Rain Water) problem, where the goal is to calculate how many units of water can be trapped between blocks of varying heights.

The application is built using Vanilla JavaScript, HTML, and CSS, and deployed as a web service on Render.
Users can input block heights and instantly receive the total units of trapped water.

## 🧠 Problem Statement

Given an array of non-negative integers where each integer represents the height of a block, compute how much water can be trapped between the blocks after raining.

## Example

## Input:

[0,4,0,0,0,6,0,6,4,0]


## Output:

Total Water Stored: 10 units

## 🚀 Features

Simple and clean user interface

Optimized O(n) time complexity

Uses two-pointer technique

No external frameworks

Production-ready deployment on Render

## 🛠️ Tech Stack

HTML5

CSS3

Vanilla JavaScript

Node.js (static serving)

Render (deployment)

## ⚙️ Algorithm Explanation

The solution uses a two-pointer approach:

Initialize two pointers (left, right) at the start and end of the array.

Track leftMax and rightMax heights.

Move the pointer with the smaller height inward.

At each step, calculate trapped water using:

water += maxHeight - currentHeight


Continue until both pointers meet.

Time & Space Complexity

Time: O(n)

Space: O(1)

## 🖥️ How to Run Locally
git clone https://github.com/naveenk-DS/Water_Tank.git
cd Water_Tank
npm install
npm start


## Open in browser:

http://localhost:3000

## 🌐 Live Deployment

The application is deployed on Render.

## 🔗 Live URL:

https://water-tank.onrender.com

## 📁 Project Structure
Water_Tank/
│── index.html
│── package.json
│── README.md

## 📸 Usage

Enter block heights separated by commas
Example:

0,4,0,0,0,6,0,6,4,0


Click Submit

View the total units of trapped water

## ✅ Assessment Highlights

Clean and readable code

Optimal algorithm

No third-party libraries

Live hosted solution

Clear problem explanation

## 👨‍💻 Author

Naveen K
GitHub: https://github.com/naveenk-DS
