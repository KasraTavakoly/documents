---
title: "Pair Smartphone with PC"
description: "Pair Smartphone with PC"
date: 2022-02-22T15:33:45-08:00
lastmod: 2022-02-22T15:33:45-08:00
draft: false
images: []
---

<div class='d-block mb-5'>
<img src='pairingsteps.png' class='d-block m-auto mb-6' width="150">
</div>

<p>After installing and running IDmelon Pairing Tool, the app will show you a Pairing QR code.</p>
<p class='mb-6'>Scan the QR code with the smartphone.</p>

<div class='d-flex column flex-column mt-5'>
<a id="btn-scan-qr" role="button" class="btn btn-primary btn-lg d-block mb-3">Scan QR code</a>
<a role="button" class="btn btn-primary btn-lg d-block mb-3" href="http://docs.idmelon.com/pages/setupasecuritykey">I will do it later</a>
</div>

<style>@media (max-width: 480px) {.navbar, .footer { display: none; }}
h1{
    color : #4395ec;
}
</style>

<script>
    const btnQRCodeScan = document.getElementById('btn-scan-qr')
    btnQRCodeScan.addEventListener('click', (ev) => {
      location.replace(`https://www.idmelon.com/open-qr`);
    });
</script>
