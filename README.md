# Lurni - by Team Echo

## Codenection Track

Track 1: Student Lifestyle

## Codenection Problem Statement

Tutoring for Students -- Website

## Tech Stack

- Django (Python)

- HTML & CSS

## Introduction

In this digital age, university students often struggle to find reliable academic support outside the classroom or to understand difficult subjects. Most of the online tutoring services are paid platforms, and the fees are not affordable for students. Other than that, motivation is also an important factor in supporting students to study. Without the support from friends or peers, they may easily lose focus and fall behind in their studies.

This is why Lurni is introduced. Lurni is a homophone for “Learn-e”, indicating that students gain knowledge more conveniently online. Through Lurni, university students can access a free and interactive forum to discuss chosen subjects with tutors or even seniors. By having the support from tutors or seniors, students feel less stressed in their studies. Not just that, tutoring sessions are also available on the website to provide a one-to-one learning experience. By signing up for the premium version, students can gain access to the resources uploaded by the tutor. The platform also introduces gamification features like streaks, reward systems and quizzes to help students consolidate their knowledge in a fun and engaging way without feeling bored.

# Developement Guide

## Virtual Environment and Dependancies

### Initialising virtual environment

`py -m venv .venv`

### Activating virtual environment

Git bash/Linux:

`source .venv/Scripts/activate`

Powershell:

`.venv\Scripts\activate`

### Installing dependancies

`pip install requirements.txt`

### Rewriting dependancies

`pip freeze > requirements.txt`

(warning: use with caution. When possible, add dependacies manually to requirements.txt)

## Run the Django App

`python manage.py runserver`
