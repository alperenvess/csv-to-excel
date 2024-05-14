                                                            --- CSV to Excel Converter Web Application --- 

This is a simple web application built with Flask that allows users to convert CSV files to Excel files online. The converted Excel file can be downloaded directly from the browser.

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/alperenvess/csv-to-excel.git
    ```

2. Navigate to the project directory:

    ```bash
    cd csv-to-excel
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:

    ```bash
    python3 app.py
    ```

5. Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

6. Upload a CSV file using the file input field.

7. Click the "Upload" button to convert the CSV file to Excel.

8. Once the conversion is complete, you can download the converted Excel file.

## File Structure

finance_manager_app/
    ├── uploads/
    ├── static/
    │   └── style.css
    ├── templates/
    │   ├── index.html
    │   └── download.html
    └── app.py

## Libraries Used

- Flask: Python web framework.
- Pandas: Data manipulation library.
- Bootstrap: Frontend framework for styling.








