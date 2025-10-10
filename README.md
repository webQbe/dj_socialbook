# Simple social media app

A Django-based social media app that implements core social features.

## About
This repo is an adaptation of [Build a Social Media App with Django – Python Web Framework Tutorial](https://www.youtube.com/watch?v=xSUm6iMtREA) by CodeWithTomi. 

I followed the tutorial to learn followings:
Building a Django social media app focused on real-world social features and a polished user experience. Key functionality includes:
- User authentication (signup, signin, logout)
- User profiles with profile pages and profile-post display
- Create and upload posts (images supported) and download images
- Post feed with like functionality
- Follow / unfollow other users and personalized post feeds
- User search and suggestion features to discover people

The app demonstrates building user relationships, handling media uploads/downloads, and designing a feed-driven UI — suitable for portfolio demos and interview walkthroughs.


## How to run (dev)
1. `git clone https://github.com/webQbe/dj_socialbook.git`
2. `python -m venv .venv && source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. `python manage.py migrate && python manage.py createsuperuser`
5. `python manage.py runserver`
---
Then open your browser and go to:
👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**


## Credits
Original tutorial: [Build a Social Media App with Django – Python Web Framework Tutorial](https://www.youtube.com/watch?v=xSUm6iMtREA) — CodeWithTomi

## License
MIT License