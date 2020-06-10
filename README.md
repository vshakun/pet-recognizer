# Flask application with TensorFlow Serving

This basic Flask application predicts pet (cat vs dog) with uploaded image.

## Project Structure

#### Task 1:
 * Create a basic, functional web app with Flask.
 
#### Task 2: Index Template
 * Add a template for the index page.
 * Add a base template which extends a Bootstrap base template.

#### Task 3: TensorFlow Serving
   * Create a docker instance with TensorFlow Serving image.
   * Deploy and serve our binary classifier model in the docker instance.

#### Task 5: Getting Predictions
   * Write a module which sends post request to the model server with input image tensor.
   * The module should also post process the predictions obtained from the model server.

#### Task 6: Connecting the Model Server to the App
   * Create functionality in app to be able to upload an image files.
   * Import the inference module created previously in the app, and get predicted class for the uploaded image.

#### Task 7: Displaying the Results in the App
   * Create a show.html template, where the uploaded image should be displayed along with its predicted class.