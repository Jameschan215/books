# HTML & CSS Notes

## Learn HTML Forms by Building a Registration Form

### Input Element

- The first **input** element with a type of submit is automatically set to *submit its nearest parent* form element.
- Input with password type can have a ```minlength``` attribute, like ```minlength=8```.
- With ```type="password"``` you can use the pattern attribute to define a regular expression that the password must match to be considered valid. You can add a ```pattern``` attribute to the password input element to require the input match: ```[a-z0-5]{8,}```.
- To relate the radio inputs, give them the same ```name``` attribute.

### Form Element
- Each option of a select element needs to be given a value attribute. Without which, the text content of the option will be submitted to the server. Like this, ```<option value="">(select one)</option>```.
- With form submissions, it is useful, and good practice, to provide each submittable element with a name attribute. This attribute is used to identify the element in the form submission.
- ```css
  fieldset:last-of-type {
    border-bottom: none;
  }
- Select only the ```.inline``` elements, and give them width of ```unset```. This will remove the earlier rule which set all the input elements to width: 100%.
- The default padding value of an input element is ```padding: 1px 2px```.