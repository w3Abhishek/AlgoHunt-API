# AlgoHunt API

**AlgoHunt API** is a RESTful API that provides real-time information on the latest coding contests and hackathons happening across various platforms. Whether you're a competitive programmer or a hackathon enthusiast, AlgoHunt helps you stay updated with upcoming events.

![](https://i.imgur.com/2VPHMeo.jpeg)

Created by [Abhishek](https://github.com/w3Abhishek) and [Tanay](https://github.com/tanay-gupta)

## Features
- **Real-time Contests & Hackathons**: Get a list of the latest coding contests and hackathons.
- **Event Details**: Access information like event name, platform, start date, end date, and duration.
- **Filter Options**: Filter contests by date, platform, and more.

## Platforms Supported
- Codeforces
- LeetCode
- CodeChef
- AtCoder
- Hackerrank
- And more...

## API Endpoints

### Contests Endpoints

- **Get all contests/hackathons**:  
  `GET /api/contests`
  
  Returns a list of all upcoming contests and hackathons.

- **Get contests by platform**:  
  `GET /api/contests?platform=<platform_name>`
  
  Filter contests by platform (e.g., Codeforces, LeetCode).

---

### Hackathons Endpoints

- **Get all hackathons**:  
  `GET /api/hackathons`
  
  Returns a list of all upcoming hackathons.

- **Get contests by platform**:  
  `GET /api/hackathons?platform=<platform_name>`
  
  Filter contests by platform (e.g., Devpost, Unstop, HackerEarth).

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/username/AlgoHunt.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the app:
    ```bash
    python3 app.py
    ```

## Contributing
Contributions are welcome! Please create an issue or submit a pull request with your changes.

## License
This project is licensed under the MIT License.

---

Stay up to date with all the latest coding contests and hackathons with **AlgoHunt**!
