# Problem Solving with Python — Code Repositories

This GitHub organization (`pswp`) hosts all the code in the chapters and active learning exercises (ALEs) found in the book:

> *Problem Solving with Python: Using Computational Thinking in Everyday Life* \
> by Michael D. Smith (MIT Press, 2026)

Each chapter has its own repository. Use the table below to find the code for a specific chapter.

If you've come across this organization without access to the book, you can purchase it directly from [MIT Press](https://mitpress.mit.edu/9780262383677/problem-solving-with-python/) or through [Amazon](https://www.amazon.com/Problem-Solving-Python-Computational-Thinking/dp/0262552841/).

## Chapter repositories

| Chapter | Title                          | Repository |
|--------:|--------------------------------|-----------|
| 1       | Read a Children's book         | [`chap01`](https://github.com/pswp-book/chap01) |
| 2       | Grab the Dialogue              | [`chap02`](https://github.com/pswp-book/chap02) |
| 3       | Replace Text with Emoji        | [`chap03`](https://github.com/pswp-book/chap03) |
| 4       | Query a Web Resource           | [`chap04`](https://github.com/pswp-book/chap04) |
| 5       | Play Guess-a-number            | [`chap05`](https://github.com/pswp-book/chap05) |
| 6       | Do You See My Dog?             | [`chap06`](https://github.com/pswp-book/chap06) |
| 7       | Many But Not Any Number        | [`chap07`](https://github.com/pswp-book/chap07) |
| 8       | What Is My Problem?            | [`chap08`](https://github.com/pswp-book/chap08) |
| 9       | Find a Phrase                  | [`chap09`](https://github.com/pswp-book/chap09) |
| 10      | Build an Index                 | [`chap10`](https://github.com/pswp-book/chap10) |
| 11      | Discover Driving Directions    | [`chap11`](https://github.com/pswp-book/chap11) |
| 12      | Divide and Conquer             | [`chap12`](https://github.com/pswp-book/chap12) |
| 13      | Rewrite the Error Message      | [`chap13`](https://github.com/pswp-book/chap13) |
| 14      | The Dream of Bug Fixing        | [`chap14`](https://github.com/pswp-book/chap14) |
| 15      | Embrace Runtime Debugging      | [`chap15`](https://github.com/pswp-book/chap15) |
| 16      | Catch Them Early               | [`chap16`](https://github.com/pswp-book/chap16) |
| 17      | Build Prediction Models        | [`chap17`](https://github.com/pswp-book/chap17) |
| 18      | Use Generative AI              | [`chap18`](https://github.com/pswp-book/chap18) |

## How to use this code

You can either:

- **Browse online** on GitHub.
- **Clone a chapter locally** using `git clone https://github.com/pswp/<chapter-repo-name>.git`, then install dependencies (if any) with `pip`.
- **Use GitHub Codespaces** by clicking the green "Code" button on a chapter's repo page, selecting the tab "Codespaces," and clicking the "Create codespace on main."

If you're cloning the code into directory on your personal machine (i.e., not using Codespaces), it's recommended but not required to activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows
   .\.venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
   ```

To install dependencies (if `requirements.txt` exists in a chapter's repo):

   ```bash
   pip install -r requirements.txt
   ```

## To modify and run the code

You will need:

- an integrated development environment (IDE)
- Python 3.10 or newer
- `pip` (usually included with Python)

If you need help getting started with an IDE, please read [my short introduction to "Understanding and Selecting an IDE"](https://ctps.io/select_ide.html).

## Issues and errata

I'm happy to hear about any problems that you find, including typos, bugs, and mismatches between a code repository and the book's text. Before reporting any of these issues, please check to see if your issue is already reported in this repo or the repo for a specific chapter. If not, please open an issue as follows:

- If the problem is clearly **about code in a specific chapter**, please open an issue in that chapter’s repository.
- If the issue spans multiple chapters or is more general, open an issue here in `pswp-index`.

When reporting, please include:

- The **printing/edition** of your book
- The chapter number and section title (e.g., “Chapter 5, The game loop”)
- The filename, line number(s), and a short description of the problem.
- If something's wrong with a program's execution, please describe how you ran the program and the exeuction result (e.g., error message).
