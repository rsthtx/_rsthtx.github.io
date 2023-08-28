# rsthtx.github.io

- [Getsrevel](https://getsrevel.github.io/)
- [Prog-B-2023](prog-b-2023/)
- [Prog-B-2022](prog-b-2022/)

<canvas id="qr"></canvas>

<script src="https://cdn.jsdelivr.net/npm/qrious@4.0.2/dist/qrious.min.js" integrity="sha256-25ncr0CpJhgbzkUiR3wu/Fkk9sSykRG2qX+upHfJUos=" crossorigin="anonymous"></script>
<script>
  (function() {
    let qr = new QRious({
      element: document.getElementById('qr'),
      size: 256,
      level: 'H',
      background: '#b5e853',
      value: window.location.href
    });
  })();
</script> 
