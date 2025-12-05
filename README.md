## Pages You Might Like Recommendation System

This project recommends pages to users based on their existing interests and liked categories. It uses simple rule based matching to identify and suggest relevant pages for each user.

## Table of Contents

1. Introduction  
2. Objective  
3. How Pages You Might Like Works  
4. Tech Stack  
5. Dataset Description  
6. Core Logic  
7. Code Overview  
8. How To Run  
9. Example Output  
10. Author  

## Introduction

Platforms often show personalized page suggestions to users to improve engagement. This notebook implements a straightforward recommendation system based on user interests and page categories.

## Objective

To compute page suggestions by  
• Reading user interest data  
• Matching users with pages that contain similar categories  
• Filtering out pages they already like  
• Producing a list of recommended pages for each user  

## How Pages You Might Like Works

The logic follows this flow  

• The system loads a JSON dataset containing users and pages  
• Each user has a list of liked categories and pages  
• Each page belongs to one or more categories  
• If a page matches a user’s liked categories and is not already liked by them it becomes a recommended page  

## Tech Stack

• Python  
• Jupyter Notebook  
• json library  

## Dataset Description

The dataset includes  
• Users with liked categories  
• Users with pages they have already liked  
• Pages with assigned categories  

The model filters and matches based on category overlap.

## Core Logic

The system applies  
• Category matching  
• Duplicate filtering  
• Page exclusion if already liked  
• Returning a list of page recommendations  

## Code Overview

Main functions in the notebook  

