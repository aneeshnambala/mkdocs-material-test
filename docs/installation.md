# Installation

This section provides instructions on how to install and run the project.

## Prerequisites

*   Python 3.6+
*   pip

## Steps

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  Create a virtual environment:

    ```bash
    python -m venv venv
    ```

3.  Activate the virtual environment:

    *   On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

    *   On Windows:

        ```bash
        venv\Scripts\activate
        ```

4.  Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5.  Run the documentation locally:

    ```bash
    mkdocs serve
    ```

    This will start a local server at <http://localhost:8000>.
