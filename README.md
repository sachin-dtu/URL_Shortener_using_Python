# URL Shortener using Python :link:

This is a simple Python script that allows you to create a URL shortener using the pyshorteners library. It shortens the provided URL and prints the shortened link.

## Library Installation :books:

To run this project, you need to install the `pyshorteners` library. You can use the following command to install it using pip:

```
pip install pyshorteners
```

## Code :computer:

```python
import pyshorteners

link = input("Enter the Link:")
shortener = pyshorteners.Shortener()
shortened_link = shortener.tinyurl.short(link)
print(shortened_link)
```

## Explanation :memo:

1. First, we import the `pyshorteners` library to use its functions.
2. The user is prompted to enter a URL, which is stored in the `link` variable.
3. We create a `shortener` variable and assign it the `pyshorteners.Shortener()` function. This function is provided by the `pyshorteners` library.
4. The `shortened_link` variable stores the shortened URL by calling the `short` function on the `shortener` object. The `link` variable is passed as the argument to the `short` function.
5. Finally, the shortened link is printed.

## Output :rocket:

```
Enter the Link:https://www.youtube.com/channel/UCu5dKasi8jWQ8fNMIyQS05g

https://tinyurl.com/y9l3wkpo
```

By following these steps, you can create your own URL shortener using Python with just five lines of code. :sparkles:

