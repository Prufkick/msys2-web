MSYS2 Web Interface
===================

A simple web interface for browsing the MSYS2 repos.

Rebuild CSS/JS (optional)::

    cd frontend
    npm install
    npm run build

Run for Development::

    poetry shell
    poetry install
    python run.py --cache

Run for Production::

    # See the Dockerfile

Webhook Config Environment Variables::

    GITHUB_WEBHOOK_SECRET=
    APPVEYOR_ACCOUNT=
    APPVEYOR_PROJECT=
    APPVEYOR_TOKEN=
