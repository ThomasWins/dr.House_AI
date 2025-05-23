# Dr. House - Local AI Assistant

**Dr. House** is a locally hosted AI assistant inspired by the diagnostician from the TV series *House M.D.*. This project runs entirely on your machine, ensuring privacy, speed, and control over your data.

![image](https://github.com/user-attachments/assets/c722b5f4-3925-4b39-b819-9e3592ce33e1)


## Getting Started

### Prerequisites

Make sure you have the following installed:

* Python 3.8+
* [virtualenv](https://pypi.org/project/virtualenv/) (optional but recommended)

### Installation

1. Clone this repository:

```bash
git clone https://github.com/ThomasWins/dr.house_ai.git
cd dr.house_ai
```

2. Set up and activate your virtual environment:

```bash
virtualenv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the AI:

```bash
python main.py
```

## Privacy

All interactions are processed locally. Dr. House does not send any data to external servers or APIs unless explicitly configured to do so.

## License

This project is licensed under the MIT License. See `LICENSE` for more information.
