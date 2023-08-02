# PHP form one

If the form in the white section below gets submitted, how can you, in welcome.php, output the value from the "first name" field?.

```html
<form action="welcome.php" method="post">
First name: <input type="text" name="fname">
</form>
```

Awnser:

```html
<html>
<body>

Welcome <?php echo $_POST["fname"]; ?>

</body>
</html>
```
