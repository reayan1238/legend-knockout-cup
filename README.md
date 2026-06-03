<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Legend Knockout Cup</title>

<style>
body{
    font-family:Arial,sans-serif;
    background:#111;
    color:white;
    margin:0;
    padding:20px;
}
.container{
    max-width:600px;
    margin:auto;
    background:#1f1f1f;
    padding:25px;
    border-radius:15px;
}
h1{
    text-align:center;
    color:#ffb300;
}
h3{
    text-align:center;
}
input{
    width:100%;
    padding:12px;
    margin-top:10px;
    margin-bottom:15px;
    border:none;
    border-radius:8px;
}
.qr{
    width:280px;
    max-width:100%;
    display:block;
    margin:auto;
    border-radius:10px;
}
.payment{
    text-align:center;
    background:#2a2a2a;
    padding:15px;
    border-radius:10px;
}
button{
    width:100%;
    padding:15px;
    background:#ffb300;
    border:none;
    border-radius:8px;
    font-size:18px;
    font-weight:bold;
    margin-top:15px;
}
.whatsapp{
    color:#25D366;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="container">

<h1>LEGEND KNOCKOUT CUP</h1>
<h3>eFootball Tournament Registration</h3>

<form>

<label>Team Name</label>
<input type="text" required>

<label>Team Owner Name</label>
<input type="text" required>

<label>Mobile Number</label>
<input type="tel" required>

<div class="payment">

<h2>Registration Fee ₹100</h2>

<p>Scan QR Code and Complete Payment</p>

<img src="legend-payment-qr.jpg" class="qr" alt="Payment QR">

<p>Send Payment Screenshot On WhatsApp</p>

<p class="whatsapp">7501261333</p>

</div>

<h3>Agreement & Declaration</h3>

<p>
The organizer will not be responsible for network issues,
internet issues, phone hang, lag, crash, device malfunction,
or power outages.
</p>

<p>
Registration fees are strictly non-refundable after payment.
</p>

<label>
<input type="checkbox" required>
I Agree To The Terms & Conditions
</label>

<button type="submit">
Complete Registration
</button>

</form>

</div>

</body>
</html>
legend-payment-qr.jpg