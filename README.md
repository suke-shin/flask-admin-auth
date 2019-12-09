この例は、SQLAlchemyのバックエンドを使用して、Flask-AdminとFlask-Loginの認証を統合する方法を示しています。

## Example

1. Create and activate a virtual environment
    ```
    $ python -m venv env
    $ source env/bin/activate
    $ (windows) .\env\scripts\activate
    ```

2. Install requirements
    ```
    $ pip install -r 'requirements.txt'
    ```

3. Create database
    ```
    $ python
    >>> from app import db
    >>> db.create_all()
    >>> exit()
    ```

4. Run the application  
    ```
    $ python app.py
    ```
 
