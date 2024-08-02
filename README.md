# Social Media Application for Computer Scientists

This project is a social media application specifically designed for computer scientists. Users can create profiles, share posts, follow each other, and interact with posts through likes and comments.

## Project Features

1. **Sign Up/Sign In System**
   - Users can create an account with a unique username and password.
   - Users can log in using their username and password.

2. **Profile Management**
   - Users can create profiles, enter bio information, and upload profile pictures.
   - Users can edit their profile information and update their profile pictures.

3. **Search Functionality**
   - Users can search and find other accounts using a search feature.
   - The search results include user profiles that match the search criteria.

4. **Follow System**
   - Users can send follow requests to other users.
   - Users can accept or decline follow requests.

5. **Posting**
   - Users can share posts that can include text, images, and videos.
   - Posts are visible to the followers of the user who posted them.

6. **Interactions**
   - Followers can like posts.
   - Followers can comment on posts.
   - The number of likes and comments is visible on each post.

## Project Structure

- `app.py`
- `config.py`
- `create_db.py`
- `db_setup.py`
- `extensions.py`
- `forms.py`
- `models.py`
- `requirements.txt`
- `templates/`
  - `base.html`
  - `comment.html`
  - `create_post.html`
  - `edit_profile.html`
  - `followers.html`
  - `index.html`
  - `like.html`
  - `login.html`
  - `profile.html`
  - `register.html`
  - `search_results.html`
  - `thank_you.html`
- `static/`
  - `css/`
  - `uploads/`

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. **Create a virtual environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt

4. **Initialize the database:**
   ```bash
   python create_db.py

5. **Run the Flask Application**
   ```bash
   python app.py
