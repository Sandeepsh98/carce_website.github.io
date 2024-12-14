<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = $_POST['name'];
    $email = $_POST['email'];
    $message = $_POST['message'];

    // Here you can add code to send the form data to your email or store in a database

    echo "Thank you for contacting us, $name. We'll get back to you shortly!";
}
?>
