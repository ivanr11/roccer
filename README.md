[Original repository](https://github.com/Fenshway/roccer)

# Roccer

A reddit-like web application that allows users to create an account and generate posts with text, image, video, or links. The application provides a way to rate, search, sort and comment on posts. Additionally, there is a bot that will automatically make posts for when there are periods of low user activity.

![Roccer home page](static/assets/roccer.png)

## Getting Started

### Prerequisites

- [Python (3.10 or higher)](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installation/) installed
- [pgAdmin 4](https://www.pgadmin.org/download/) and a **PostgresSQL database** set up
- **YouTube API credentials** (optional, for bot functionality)

### Setup

1. **Clone the repository:**

```bash
git clone https://github.com/ivanr11/roccer.git
cd roccer
```

2. **Create a virtual environment and activate it:**

```bash
python -m venv venv
```

```bash
source ./venv/Scripts/activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Configure environment variables in a** `.env` **file:**

```
DATABASE_URI=
BCRYPT_ROUNDS=10
YOUTUBE_API_KEY=
```

5. **Run the application**

```bash
flask run
```
