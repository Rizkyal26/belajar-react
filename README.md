# React Documentrary

Merupakan file dokumentasi hasil pembelajaran dari Web Programming Unpas
Terimakasih banyak kepada beliau untuk ilmu pembelajaran nya tentang React.JS

Berikut ini merupakan Library (sesajen) untuk penggunaan React.js dalam versi sederhana:

#### 1. Mengambil Daftar Provinsi

<!-- Perintah berikut dapat diletakan langsung di Head atau di body-->
<head>
    
    <!-- Fungsi buat judul tab halaman-->
    <title>Belajar React.js Pemula</title>

    <!-- Fungsi React-->
    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>

    <!-- Fungsi Dom buat React-->
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script> 

    <!-- Fungsi Babel buat menjalankan JSX di web-->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

</head>

<body>

    <!-- Default Code from React.js-->
    <div id="root"></div>

    <!--  jangan lupa type text nya diganti babel(berwarna) atau jsx(tidak berwarna) -->
    <script type="text/babel">

    // merupakan function declaration dari perintah react.js
    const container = document.getElementById('root');
    const root = ReactDOM.createRoot(container);

    // pada bagian "kalimat "HomePage" ini disesuaikan dengan perintah deklrasi pada function". jadi tidak harus serta merta sama
    root.render(<HomePage />);

</body>
