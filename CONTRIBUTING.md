# Contributing to the Mergington High Activities Practice Project

Thanks for helping improve this GitHub Skills repository! Mergington High is the tutorial's fictional school; use sample data only.

## Development Setup

1. Clone this repository and work from its root directory.
2. Create and activate a Python virtual environment, then install dependencies with `python -m pip install -r requirements.txt`.
3. Start a local MongoDB instance at `mongodb://localhost:27017/`, as expected by `src/backend/database.py`. The app initializes sample data when the database is empty.
4. Start the development server with `python -m uvicorn src.app:app --reload`.
5. Open http://localhost:8000; API documentation is at http://localhost:8000/docs.

## Making Changes

1. Check existing issues, then create a descriptive branch such as `fix-activity-signup`.
2. Keep each change focused. Test affected pages and API behavior locally using fictional data, and describe what you checked.
3. Commit source code and intentional project configuration. Use `.gitignore` only for non-source files such as caches, virtual environments, local secrets, and generated output; never use it to hide source changes. Never commit credentials or real student information.
4. Push your branch and open a pull request describing the change, related issue, and checks performed.
5. Address review feedback before merging.

## Code Style

- Follow PEP 8 for Python and the existing JavaScript, HTML, and CSS style.
- Use descriptive names and explain non-obvious logic with comments.
- Avoid unrelated formatting changes.

## Need Help or Have Ideas?

Search this repository's issues first. Add context to a matching issue or open a new one with reproduction steps or a clear proposal. For suspected vulnerabilities, do not post details publicly; use the repository's private vulnerability reporting feature when available.

## AI Assistance

These contribution guidelines were prepared with AI assistance and adapted to this practice repository. Disclose significant AI assistance in your pull request and verify generated changes before submitting them.
