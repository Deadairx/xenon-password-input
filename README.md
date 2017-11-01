# xenon-password-input
Complex password input


<!---
```
<custom-element-demo>
  <template>
    <script src="../../webcomponentsjs/webcomponents.min.js"></script>
    <link rel="import" href="xenon-password-input.html">
    <link rel="import" href="../iron-form/iron-form.html">
     <style>
      xenon-password-input {
        max-width: 400px;
        margin: auto;
      }
      iron-form, div[suffix] {
        margin-top: 8px;
      }
    </style><next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<form is="iron-form" id="form">
	<xenon-password-input label="Password"></xenon-password-input>
	<button onclick='document.getElementById("form").validate();'>test</button>
</form>
```
