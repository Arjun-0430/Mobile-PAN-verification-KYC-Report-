# KYC Verification Report Generator

This is a web application that allows users to generate KYC (Know Your Customer) verification reports based on a user's name and mobile number. The application fetches data from a backend API, displays it in a user-friendly interface, and allows the user to download the report as a PDF.

## Features

*   **Mobile to PAN Prefill:** Enter a name and mobile number to fetch and prefill PAN card details.
*   **Tabbed Interface:** View detailed information organized into categories like Personal Info, Contact, Address, PAN Details, and Aadhaar Details.
*   **Search Functionality:** Filter the information within the report to quickly find specific details.
*   **PDF Export:** Download a professionally styled PDF of the verification report.
*   **Responsive Design:** The application is designed to work on various screen sizes.

## Technologies Used

*   **Frontend:**
    *   HTML
    *   [Tailwind CSS](https://tailwindcss.com/) for styling.
    *   JavaScript for interactivity and API communication.
    *   [jsPDF](https://github.com/parallax/jsPDF) for generating PDF documents.
    *   [html2canvas](https://html2canvas.hertzen.com/) to render HTML elements onto a canvas for PDF generation.
*   **Backend:**
    *   Python
    *   [Flask](https://flask.palletsprojects.com/) as the web framework.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Install Python dependencies:**
    It is recommended to use a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install Flask
    ```

3.  **Run the application:**
    ```bash
    flask run
    ```
    The application will be available at `http://127.0.0.1:5000`.

## Usage

1.  Open the web application in your browser.
2.  Click on the "Mobile to PAN" card.
3.  Enter the full name and mobile number in the form that appears.
4.  Click "Generate Report".
5.  The verification report will be displayed.
6.  Use the search bar to filter the report details.
7.  Click the "Download" button to save the report as a PDF.
