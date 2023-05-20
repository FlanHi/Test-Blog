Suggestions:

- Push your virtual environment folder to GitHub (for now, do not include it in .gitignore)
- Always add a README file, like this one
- Before pushing your project to GitHub, make sure your `requirements.txt` file is updated

```python
(venv)$ pip3 freeze > requirements.txt
```

Changes:

- I have modified the `index.html` page such that the table and its related data are not displayed to a user who is not logged in (you had this table outside the `if` statement)
- The table is now displayed only to the logged in user
- I have restructured the table so that it looks a bit different
- Feel free to add your modal

| Seen by anonymous user | Seen by authenticated user | A user's profile age |
| ---------------------- | -------------------------- | -------------------- |
| ![anoymous](/app/static/images/index.png)  | ![anoymous](/app/static/images/home.png) | ![anoymous](/app/static/images/profile.png) |

