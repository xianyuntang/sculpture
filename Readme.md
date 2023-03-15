# Sculpture

This is a template for a small model inference API.

# Usage

To use this template, follow these steps:

* Import the Sculpture class from the sculpture module:

```python
from sculpture import Sculpture
```

* Define an inference function that takes an input and produces an output:

```python
inference_function = lambda x: x
```

Replace lambda x: x with your actual inference function.

* Create a Sculpture instance by passing your inference function to the constructor:

```python
sculpture = Sculpture(inference_function=inference_function)
```

* Start the API server by calling the serve method on the Sculpture instance:

```python
sculpture.serve(debug=True)
```

You can set the debug argument to False if you don't want to see debug messages.

That's it! Your API should now be up and running, ready to receive requests and return predictions.



