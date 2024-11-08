

# 📚 Blogy – Your Friendly Blogging Platform 🎉

> "Write, Read, Repeat." - Someone Very Wise

Welcome to **Blogy** – a delightful, simple, and no-nonsense blogging platform! Whether you're here to share your wisdom or just rant about your pet's new hairstyle, Blogy is here for you! 🌈 

## Features 🚀

Here’s why Blogy is the best thing since sliced bread 🍞:

- 📝 **Effortless Blog Posting**: Write your heart out! Add a catchy title, subtitle, and get that content flowing!
- 🕶️ **Cool & Clean Design**: Because we believe blogs should be easy on the eyes. No clutter, just content!
- 💻 **Built with Flask + PHP Magic 🧙‍♂️**: Mixing the power of Python and PHP for the ultimate blog experience.
- 🐬 **MySQL / SQLite Databases**: No need for filing cabinets; we got this!
- 🔒 **User Login & Password Reset**: Keep it safe and secure. No trolls allowed! (Unless they're funny. 😜)

## Screenshots 📸

Check out some snapshots of **Blogy** in action!

### Login Page
![image](https://github.com/user-attachments/assets/dee4b15e-9234-470c-9248-c41cf4f965f5)

### Homepage
![image](https://github.com/user-attachments/assets/68a673ee-70df-46c4-8c29-d08e49cf72ae)
![image](https://github.com/user-attachments/assets/5ac177dd-df90-49dd-98f2-b8012287b210)

### Featured Post
![image](https://github.com/user-attachments/assets/a246987b-493e-4333-a67b-a53ec799ad52)


## Installation 📥

1. **Clone the Awesomeness**:
   ```bash
   git clone https://github.com/mourvijoshi/blogy.git
   ```
   
2. **Step Into the Cool Zone**:
   ```bash
   cd blogy
   ```

3. **Activate the Python Powerhouse (Optional but Rad)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. **Get Flask Up and Running**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Set Up the Database**:
   - Create a MySQL database or let SQLite take over. 
   - If you’re cool with SQLite, initialize it with:
     ```bash
     python -c "from app import db; db.create_all()"
     ```

6. **Fire Up Blogy**:
   ```bash
   python app.py
   ```
   
7. 🚀 **Visit the Magic** at `http://localhost:5000`.

> **Tip**: Don’t forget to say "Hello, Blogy!" 👋

## Project Layout 📂

```plaintext
blogy/
├── .venv/                  # Virtual environment (optional)
├── assets/                 # Stuff like images, maybe a meme or two
├── static/                 # Home to CSS magic
│   └── first.css           # Our glorious styling
├── templates/              # HTML templates - where beauty happens
├── app.py                  # The mastermind Flask app
├── blog.db                 # SQLite database (if you're using it)
├── login.php               # PHP for that sweet login functionality
├── article1.html           # Sample article page (spoiler alert: it’s awesome)
├── homepage.html           # Main homepage for all the blogs
├── forgot password.html    # Because forgetting is human, right?
└── README.md               # This masterpiece
```

## Usage 💡

Here's how to take Blogy for a spin:

1. **Log In or Register**: `/login` is your gateway to blog paradise.
2. **Create a Masterpiece**: `/add` is where the magic starts.
3. **Browse the Awesomeness**: The homepage (`homepage.html`) shows all posts.
4. **Behold the Featured Ones**: Our celebrities of the blog world, at `/featuredpost`.

## Contributing ❤️

Wanna make Blogy even better? Fork it, clone it, do your magic, and open a PR. We’d love to see your unique touch!

### How to Contribute:

1. 🍴 **Fork the Project**  
2. 🌱 **Create a Branch** (`git checkout -b feature/AmazingFeature`)
3. 💥 **Make Some Changes!**
4. 📬 **Submit a Pull Request**

> We can’t wait to see what you bring to Blogy! 🌟

## License 📜

This project is licensed under the **MIT License**. (Because sharing is caring!)


