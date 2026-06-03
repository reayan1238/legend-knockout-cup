
# legend-knockout-cup
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Legend Knockout Cup Registration</title>

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
    background:#1e1e1e;
    padding:25px;
    border-radius:15px;
}

h1{
    text-align:center;
    color:#ffb300;
}

h3{
    text-align:center;
    color:#ddd;
}

label{
    display:block;
    margin-top:15px;
    font-weight:bold;
}

input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    margin-top:5px;
}

.fee-box{
    margin-top:20px;
    text-align:center;
    background:#2c2c2c;
    padding:15px;
    border-radius:10px;
}

.qr{
    width:250px;
    max-width:100%;
    border-radius:10px;
    margin:15px auto;
    display:block;
}

.agreement{
    margin-top:20px;
    background:#2c2c2c;
    padding:15px;
    border-radius:10px;
}

button{
    width:100%;
    padding:15px;
    margin-top:20px;
    background:#ffb300;
    border:none;
    border-radius:8px;
    font-size:18px;
    font-weight:bold;
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

<div class="fee-box">

<h2>Registration Fee ₹100</h2>

<p>Scan the QR Code and complete payment</p>

<img src="legend-payment-qr.jpg" alt="QR Payment" class="qr">

<p>After payment send screenshot to:</p>

<p class="whatsapp">WhatsApp: 7501261333</p>

</div>

<div class="agreement">

<h3>Agreement & Declaration</h3>

<ul>
<li>The organizer is not responsible for network issues.</li>
<li>The organizer is not responsible for phone hang, lag, crash, or device problems.</li>
<li>Participants must ensure a stable internet connection.</li>
<li>Registration fees are strictly non-refundable.</li>
<li>Organizer decisions will be final.</li>
</ul>

<label>
<input type="checkbox" required>
I agree to all terms and conditions.
</label>

</div>

<button type="submit">
Complete Registration
</button>

</form>

</div>

</body>
</html>
legend-payment-qr.jpg