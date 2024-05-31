# AIAir server setup

This guide will walk you through setting up a Flask application by installing dependencies listed in the `requirements.txt` file and running the Flask server. 

## Installation

1. Install dependencies using pip:

    ```
    py -m pip install -r requirements.txt // for pip error "pip" is not recognized then add (py -m )
                                          // move to the current "aiair-server folder"  by (cd aiair-server) then install requirements.txt            
    ```

## Running the Application

1. Ensure you are in the project directory on tmp\aiair-server

2. Run the Flask application:

    ```
    py -m flask run

    ```

3. Open your web browser and visit [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to view the application.
