# mpesa-api-package

<p>
Its a simple package to help consume the mpesa daraja api v2 to achive mpesa payments in your website
</p>



<ol>
To use it simply follow the instructions below
<li>
npm install mpesa-controller
</li>
<li>
In your routes file import the package e.g <em>const mpesaController = require('mpesa-controller')</em>
</li>
<li>
Initialize the functions you require in your route Example <em>
router.get("/access_token", mpesaapi.MpesaToken, (req, res) => {
  res.status(200).json({ access_token: req.token });
});
</em>
</li>
</ol>
