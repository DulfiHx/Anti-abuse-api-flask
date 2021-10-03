# Anti-abuse-api-flask
API which returns cusswords , can be used to check cusswords in bots etc.

## Run

```pip install -r requirements.txt```

```py app.py```

## API Endpoints

```/api/v1``` returns all the cusswords.

```/api/v1/check?q={string}``` returns `True` or `False` if the query matches the cusswords in api.

## How to Contribute ?

Fork the repository , open **cuss_words.txt** and enter the words in new lines.

Make a **Pull Request**.

You can enter any number of variations but please don't repeat them.

## Note

```app.py``` needs to be restarted whenver there's a change in **cuss_words.txt** for it to update the api.

If you have a solution , Open a Pull Request.