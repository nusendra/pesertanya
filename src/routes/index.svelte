<svelte:head>
  <title>PeserTanya</title>
</svelte:head>

<body>
  <script src="https://www.gstatic.com/firebasejs/7.6.0/firebase-app.js">

  </script>
  <script src="https://www.gstatic.com/firebasejs/7.6.0/firebase-analytics.js">

  </script>
  <script>
    var firebaseConfig = {
      apiKey: "AIzaSyC3NJbBxuQD_Z9PEfbQW_TLyK2mbv-Qed4",
      authDomain: "pesertanya-nusendra.firebaseapp.com",
      databaseURL: "https://pesertanya-nusendra.firebaseio.com",
      projectId: "pesertanya-nusendra",
      storageBucket: "pesertanya-nusendra.appspot.com",
      messagingSenderId: "924115205409",
      appId: "1:924115205409:web:ae13e53fb93ee41f349260",
      measurementId: "G-VJJ8QTC5HY"
    };
    firebase.initializeApp(firebaseConfig);
    firebase.analytics();
  </script>
</body>
