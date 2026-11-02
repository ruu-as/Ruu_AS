<!DOCTYPE html>
<html lang="id">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
  <meta name="theme-color" content="#2196f3">
  <meta name="description" content="Pupu Celluler — layanan transaksi digital, pulsa, paket data, pembayaran, dan kebutuhan agen.">
  <title>Pupu Celluler</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0">
</head>

<body>
  <main class="app-shell">
    <header class="home-top">
      <div class="top-row">
        <button class="icon-button" id="menu-toggle" type="button" aria-label="Buka menu" aria-controls="offcanvas-menu" aria-expanded="false">
          <span aria-hidden="true" class="material-symbols-outlined">menu</span>
        </button>
        <a href="/" class="brand-name">Pupu Celluler</a>
        <div class="top-actions">
          <a href="/" class="icon-button" aria-label="Muat ulang halaman">
            <span aria-hidden="true" class="material-symbols-outlined">refresh</span>
          </a>
          <button class="icon-button" id="quick-actions-toggle" type="button" aria-label="Menu lainnya" aria-controls="quick-actions" aria-expanded="false"><span aria-hidden="true" class="material-symbols-outlined">more_vert</span></button>
        </div>
      </div>
      <nav class="tabs" role="tablist" aria-label="Navigasi utama">
        <button class="tab-link active" id="tab-transaksi" type="button" role="tab" aria-selected="true" aria-controls="transaksi-content" data-tab="transaksi">TRANSAKSI</button>
        <button class="tab-link" id="tab-menu-agen" type="button" role="tab" aria-selected="false" aria-controls="menu-agen" data-tab="menu-agen" tabindex="-1">MENU AGEN</button>
        <button class="tab-link" id="tab-history" type="button" role="tab" aria-selected="false" aria-controls="history" data-tab="history" tabindex="-1">HISTORY</button>
        <button class="tab-link" id="tab-info" type="button" role="tab" aria-selected="false" aria-controls="info" data-tab="info" tabindex="-1">INFO</button>
      </nav>
    </header>
    <div class="header-spacer" aria-hidden="true"></div>

    <div class="quick-dropdown" id="quick-actions" aria-label="Menu lainnya" aria-hidden="true">
      <a href="/" class="quick-backdrop" aria-label="Tutup menu lainnya"></a>
      <nav class="quick-panel" aria-label="Aksi akun"><a href="/">Logout</a><a href="/">Exit</a></nav>
    </div>

    <section class="tab-panel" id="transaksi-content" data-tab-panel="transaksi" role="tabpanel" aria-labelledby="tab-transaksi" aria-label="Transaksi">
      <div class="banner-stack">
        <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776157935.png" alt="Informasi layanan Pupu Celluler">
        <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776157901.png" alt="Ilustrasi transaksi digital">
      </div>
      <section class="account-summary" aria-label="Ringkasan akun">
        <div class="agent-line"><span data-account-field="agentId">AP76761</span><span data-account-field="name">Rara</span></div>
        <div class="balance-panel">
          <div class="balance-heading">
            <div class="balance-label"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/wallet.png" alt=""><span>Saldo Anda</span></div>
            <div class="balance-amount-wrap">
              <button class="balance-toggle" id="balance-toggle" type="button" aria-label="Tampilkan saldo" aria-pressed="false">
                <span aria-hidden="true" class="material-symbols-outlined" id="balance-icon">visibility</span>
              </button>
              <span id="balance-amount" data-balance-display data-hidden="••••••" data-visible="Rp 0">••••••</span>
            </div>
          </div>
          <div class="balance-actions">
            <a href="./Tukar%20Komisi.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/komisi.png" alt="">Komisi&nbsp; 0</a>
            <a href="./Tukar%20Poin.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/poin.png" alt="">Poin&nbsp; 0</a>
            <a href="./Tambah%20Saldo.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/tambah.png" alt="">Tambah saldo</a>
          </div>
        </div>
        <div class="balance-indicator" aria-hidden="true"></div>
      </section>

      <section class="content-section" aria-label="Produk terlaris">
        <div class="agent-group">
          <h2 class="agent-heading">Produk Terlaris</h2>
          <p class="agent-description">Layanan favorit para mitra</p>
          <div class="agent-shortcuts">
            <a href="./Pulsa%20Reguler.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1775989019.png" alt=""><span>Pulsa Reguler</span></a>
            <a href="./Pulsa%20Transfer.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776021952.png" alt=""><span>Pulsa Transfer</span></a>
            <a href="./Token%20PLN.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1775989119.png" alt=""><span>Token PLN</span></a>
            <a href="./Paket%20Data.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1775989048.png" alt=""><span>Paket Data</span></a>
            <a href="./Telp%20%26%20SMS.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1775989077.png" alt=""><span>Telepon &amp; SMS</span></a>
            <a href="./Zona%20Hiburan.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1782395912.png" alt=""><span>Zona Hiburan</span></a>
            <a href="./Voucher%20TV.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776021332.png" alt=""><span>Voucher TV</span></a>
            <a href="./Produk%20Lainnya.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022225.png" alt=""><span>Produk Lainnya</span></a>
          </div>
        </div>
        <div class="agent-group">
          <h2 class="agent-heading">Aneka Voucher</h2>
          <p class="agent-description">Berbagai pilihan voucher operator untuk kebutuhanmu</p>
          <div class="agent-shortcuts">
            <a href="./Voucher%20Fisik.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776021299.png" alt=""><span>Voucher Fisik</span></a>
            <a href="./Inject%20Voucher.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776021978.png" alt=""><span>Inject Voucher</span></a>
            <a href="./Masa%20Aktif.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022004.png" alt=""><span>Masa Aktif</span></a>
            <a href="./Aktivasi%20Perdana.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776021360.png" alt=""><span>Aktivasi Perdana</span></a>
          </div>
        </div>
        <div class="agent-group">
          <h2 class="agent-heading">Paket Unggulan</h2>
          <p class="agent-description">Pilih paket dari operator favorit</p>
          <div class="agent-shortcuts">
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098334.png" alt=""><span>Omni Telkomsel</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098302.png" alt=""><span>Paket by.U</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098273.png" alt=""><span>Digipos Aja!</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098362.png" alt=""><span>Paket Indosat</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098386.png" alt=""><span>Paket Tri</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098410.png" alt=""><span>Paket Axis</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776098459.png" alt=""><span>Paket XL</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/smartf.png" alt=""><span>Paket Smartfren</span></a>
          </div>
        </div>
        <div class="agent-group">
          <h2 class="agent-heading">Bayar Tagihan</h2>
          <p class="agent-description">Urus kebutuhan bulanan dengan praktis</p>
          <div class="agent-shortcuts">
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022527.png" alt=""><span>Bayar Listrik</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022595.png" alt=""><span>Bayar Indihome</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776102517.png" alt=""><span>Bayar Iconnet</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022621.png" alt=""><span>Bayar PDAM</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022649.png" alt=""><span>Bayar Gas</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022703.png" alt=""><span>Bayar BPJS</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022774.png" alt=""><span>Kartu Halo</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022225.png" alt=""><span>Tagihan Lainnya</span></a>
          </div>
        </div>
        <div class="promo-slider promo-slider-primary" role="region" aria-label="Promo pilihan pertama">
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154571.png" alt="Promo pembayaran">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154551.png" alt="Promo pembayaran">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo layanan digital">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154629.png" alt="Promo layanan digital">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154603.png" alt="Promo pembayaran">
          </a>
        </div>
        <div class="agent-group">
          <h2 class="agent-heading">Dompet Digital</h2>
          <p class="agent-description">Top up e-wallet favorit dengan cepat</p>
          <div class="agent-shortcuts">
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/danalogo.png" alt=""><span>DANA</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776079647.png" alt=""><span>OVO</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776079673.png" alt=""><span>ShopeePay</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/gopaylogo.png" alt=""><span>GoPay</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776079730.png" alt=""><span>LinkAja</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776079754.png" alt=""><span>Grab</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776079853.png" alt=""><span>Maxim</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776022225.png" alt=""><span>Lainnya</span></a>
          </div>
        </div>
        <div class="promo-slider promo-slider-secondary" role="region" aria-label="Promo pilihan kedua">
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154571.png" alt="Promo pembayaran">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154551.png" alt="Promo pembayaran">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo layanan digital">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154629.png" alt="Promo layanan digital">
          </a>
          <a href="/" class="promo-slide" aria-label="Promo pembayaran">
            <img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776154603.png" alt="Promo pembayaran">
          </a>
        </div>
        <div class="agent-group">
          <h2 class="agent-heading">Zona Game</h2>
          <p class="agent-description">Top up atau beli voucher game favoritmu</p>
          <div class="agent-shortcuts">
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080345.png" alt=""><span>Free Fire</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080365.png" alt=""><span>Mobile Legends</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080393.png" alt=""><span>Call of Duty</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080413.png" alt=""><span>Arena of Valor</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080436.png" alt=""><span>PUBG Mobile</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080460.png" alt=""><span>Voucher Game</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080485.png" alt=""><span>Steam Wallet</span></a>
            <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776080506.png" alt=""><span>Game Lainnya</span></a>
          </div>
        </div>
      </section>
    </section>

    <section class="tab-panel content-section" id="menu-agen" data-tab-panel="menu-agen" role="tabpanel" aria-labelledby="tab-menu-agen" aria-label="Menu agen" hidden>
      <div class="agent-group">
        <h2 class="agent-heading">Tambah Saldo</h2>
        <p class="agent-description">Pilih metode isi saldo yang nyaman</p>
        <div class="funding-grid">
          <a href="./Tambah%20Saldo.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786116593.png" alt="Isi saldo via QRIS"></a>
          <a href="./Tambah%20Saldo.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786116629.png" alt="Isi saldo via transfer bank"></a>
        </div>
      </div>
      <div class="agent-group">
        <h2 class="agent-heading">Kelola Downline</h2>
        <p class="agent-description">Kembangkan jaringan dan pantau aktivitasnya</p>
        <div class="downline-grid">
          <a href="./Daftarkan%20Downline.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786112206.png" alt="Daftar downline"></a>
          <a href="./List%20Downline.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786112283.png" alt="List downline"></a>
          <a href="./Jml%20Transaksi%20Downline.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786112324.png" alt="Transaksi downline"></a>
          <a href="./Transfer%20Saldo%20Downline.html"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1786112405.png" alt="Transfer saldo downline"></a>
        </div>
      </div>
      <div class="agent-group">
        <h2 class="agent-heading">Menu Agen</h2>
        <p class="agent-description">Informasi akun dan fitur khusus mitra</p>
        <div class="agent-shortcuts">
          <a href="./Info%20Akun.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776024775.png" alt=""><span>Info Akun</span></a>
          <a href="./Messenger.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776024910.png" alt=""><span>Messenger</span></a>
          <a href="./List%20Paralel.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776024939.png" alt=""><span>List Paralel</span></a>
          <a href="./Verif%20Akun.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776025550.png" alt=""><span>Verifikasi Akun</span></a>
        </div>
      </div>
      <div class="agent-group center-transaksi-group">
        <h2 class="agent-heading">Center Transaksi</h2>
        <p class="agent-description">Akses cepat ke pusat bantuan transaksi</p>
        <div class="agent-shortcuts">
          <a href="https://wa.me/6285882530024" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776122755.png" alt=""><span>Center WA 1</span></a>
          <a href="https://wa.me/6285882530024" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776122755.png" alt=""><span>Center WA 2</span></a>
          <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776122795.png" alt=""><span>Center Telegram</span></a>
        </div>
      </div>
      <div class="agent-group">
        <h2 class="agent-heading">Fitur Pendukung</h2>
        <p class="agent-description">Bantu kelola aktivitas transaksi harian</p>
        <div class="agent-shortcuts">
          <a href="./Pengaturan%20Kunci%20Aplikasi.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776025150.png" alt=""><span>Kunci Aplikasi</span></a>
          <a href="./Jadwal%20Transaksi.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776102872.png" alt=""><span>Jadwal Transaksi</span></a>
          <a href="./Cetak%20Struk.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776025133.png" alt=""><span>Cetak Struk</span></a>
          <a href="./Pengaturan.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776025036.png" alt=""><span>Pengaturan</span></a>
          <a href="./Price%20List.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776024784.png" alt=""><span>Price List</span></a>
          <a href="./Rekap%20Piutang.html" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776025036.png" alt=""><span>Rekap Piutang</span></a>
          <a href="/" class="product-link"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconmainmenu1776184857.png" alt=""><span>Channel WhatsApp</span></a>
        </div>
      </div>
      <div class="agent-group">
        <h2 class="agent-heading">Akun</h2>
        <p class="agent-description">Masuk atau buat akun Pupu Celluler</p>
        <div class="agent-shortcuts account-shortcuts">
          <a href="./Login.html" class="product-link"><span class="material-symbols-outlined" aria-hidden="true">login</span><span>Login</span></a>
          <a href="./Daftar.html" class="product-link"><span class="material-symbols-outlined" aria-hidden="true">person_add</span><span>Daftar</span></a>
          <a href="./Catatan%20Keuangan.html" class="product-link"><span class="material-symbols-outlined" aria-hidden="true">account_balance</span><span>Catatan Keuangan</span></a>
        </div>
      </div>
    </section>

    <section class="tab-panel history-panel" id="history" data-tab-panel="history" role="tabpanel" aria-labelledby="tab-history" aria-label="Riwayat dan laporan" hidden>
      <div class="history-list">
        <article class="history-feature-image">
          <a href="./Histori%20Transaksi.html" aria-label="Histori transaksi"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776117362.png" alt=""></a>
        </article>
        <article class="history-feature-image">
          <a href="./Histori%20Tambah%20Saldo.html" aria-label="Histori tambah saldo"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776117383.png" alt=""></a>
        </article>
        <article class="history-feature-image">
          <a href="./Histori%20Transfer%20Saldo%20Downline.html" aria-label="Histori transfer saldo"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776117408.png" alt=""></a>
        </article>
        <article class="history-feature-image">
          <a href="./Histori%20Tukar%20Komisi.html" aria-label="Histori tukar komisi"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1776117422.png" alt=""></a>
        </article>
        <article class="history-feature-image">
          <a href="./Histori%20Penjualan.html" aria-label="Histori penjualan"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjp1781497359.png" alt=""></a>
        </article>
      </div>
    </section>

    <section class="tab-panel info-feed" id="info" data-tab-panel="info" role="tabpanel" aria-labelledby="tab-info" aria-label="Informasi dan pengumuman" hidden>
      <article class="info-card">
        <h2>Cara isi saldo aplikasi Pupu Celluler</h2><time datetime="2026-04-28T14:50:26">28 April 2026 · 14:50</time>
        <hr>
        <p>Isi saldo melalui menu <strong>Tambah Saldo</strong>, lalu pilih metode QRIS atau transfer bank.</p>
        <p>Pastikan nominal dan nomor referensi sudah sesuai sebelum menyelesaikan pembayaran.</p>
      </article>
      <article class="info-card">
        <h2>Perbedaan Pulsa Reguler &amp; Pulsa Transfer</h2><time datetime="2025-09-20T16:02:45">20 September 2025 · 16:02</time>
        <hr>
        <p>Pulsa reguler dapat menambah masa aktif kartu. Pulsa transfer dikirim dari saldo pengguna lain dan mengikuti ketentuan operator.</p>
      </article>
      <article class="info-card">
        <h2>Deposit saldo dari e-wallet</h2><time datetime="2025-09-18T12:12:42">18 September 2025 · 12:12</time>
        <hr>
        <p>Gunakan rekening tujuan yang tersedia di menu tambah saldo dan simpan bukti transaksi untuk referensi.</p>
      </article>
      <article class="info-card">
        <h2>Format transaksi</h2><time datetime="2025-09-10">10 September 2025</time>
        <hr>
        <p>Gunakan format yang sesuai dan periksa kembali nomor tujuan sebelum mengirim transaksi.</p>
      </article>
    </section>

    <nav class="bottom-nav" aria-label="Navigasi bawah">
      <a href="/" aria-label="Profil"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconfloatingmenu1786000398.png" alt=""><span>Profil</span></a>
      <a href="https://wa.me/6285882530024" aria-label="Bantuan"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconfloatingmenu1786000435.png" alt=""><span>Bantuan</span></a>
      <a href="./Qris.html" class="active nav-center" aria-current="page" aria-label="Transaksi"><span class="nav-feature"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconfloatingmenu1785998605.png" alt=""></span></a>
      <a href="/" aria-label="Pesan"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconfloatingmenu1786000412.png" alt=""><span>Pesan</span></a>
      <a href="/" aria-label="Piutang"><img src="https://ruu77.wordpress.com/wp-content/uploads/2026/10/cjpiconfloatingmenu1786000468.png" alt=""><span>Piutang</span></a>
    </nav>

    <aside class="offcanvas" id="offcanvas-menu" aria-label="Menu utama" aria-hidden="true">
      <a href="/" class="offcanvas-backdrop" aria-label="Tutup menu"></a>
      <div class="offcanvas-panel" tabindex="-1">
        <div class="drawer-brand">
          <div class="drawer-mark">AP</div>
          <h2>Pupu Celluler</h2>
          <p>Digital Multi Payment</p>
          <p>Pusat PPOB digital untuk kebutuhan transaksi mitra.</p>
          <p>Lokasi belom di sett</p>
          <p class="contact-line"><span data-account-field="name">Rara</span> · <span data-account-field="agentId">AP76761</span><br>Customer Service · <span data-account-field="phone">085882530024</span></p>
        </div>
        <nav class="drawer-links" aria-label="Tautan menu">
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">support_agent</span><span>Customer Service</span></a>
          <a href="./Login.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">login</span><span>Login</span></a>
          <a href="./Daftar.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">person_add</span><span>Daftar Akun</span></a>
          <a href="./List%20Downline.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">groups</span><span>Data Agen</span></a>
          <a href="./Transfer%20Saldo%20Downline.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">account_balance_wallet</span><span>Transfer Saldo</span></a>
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">person_add</span><span>Pengirim Terdaftar</span></a>
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">language</span><span>Kunjungi Website</span></a>
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">system_update</span><span>Update Aplikasi</span></a>
          <a href="./Pengaturan%20Kunci%20Aplikasi.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">lock</span><span>Kunci Aplikasi</span></a>
          <a href="./Pengaturan.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">settings</span><span>Pengaturan</span></a>
          <a href="./Verif%20Akun.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">verified_user</span><span>Verifikasi Akun</span></a>
          <a href="./Kebijakan%20Privasi.html" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">policy</span><span>Kebijakan Privasi</span></a>
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">logout</span><span>Logout</span></a>
          <a href="/" class="drawer-link"><span class="material-symbols-outlined drawer-icon" aria-hidden="true">exit_to_app</span><span>Exit</span></a>
        </nav>
        <p class="drawer-version">Pupu Celluler · Versi 9.1.1</p>
      </div>
    </aside>
  </main>
  <script>
    (() => {
      const tabs = [...document.querySelectorAll('[role="tab"][data-tab]')];
      const panels = [...document.querySelectorAll('[data-tab-panel]')];
      const activateTab = (selectedTab, moveFocus = false) => {
        tabs.forEach((tab) => {
          const selected = tab === selectedTab;
          tab.classList.toggle('active', selected);
          tab.setAttribute('aria-selected', String(selected));
          tab.tabIndex = selected ? 0 : -1;
        });
        panels.forEach((panel) => {
          const visible = panel.dataset.tabPanel === selectedTab.dataset.tab;
          panel.hidden = !visible;
          panel.classList.toggle('is-active', visible);
        });
        if (moveFocus) selectedTab.focus();
        window.scrollTo({ top: 0, behavior: 'smooth' });
      };
      tabs.forEach((tab, index) => {
        tab.addEventListener('click', () => activateTab(tab));
        tab.addEventListener('keydown', (event) => {
          let next = index;
          if (event.key === 'ArrowRight') next = (index + 1) % tabs.length;
          else if (event.key === 'ArrowLeft') next = (index - 1 + tabs.length) % tabs.length;
          else if (event.key === 'Home') next = 0;
          else if (event.key === 'End') next = tabs.length - 1;
          else return;
          event.preventDefault();
          activateTab(tabs[next], true);
        });
      });
      const initialTab = tabs.find((tab) => tab.getAttribute('aria-selected') === 'true') || tabs[0];
      if (initialTab) activateTab(initialTab);

      const balanceToggle = document.getElementById('balance-toggle');
      const balanceAmount = document.getElementById('balance-amount');
      const balanceIcon = document.getElementById('balance-icon');
      const balanceKey = 'pupu-celluler-balance';
      const storedBalance = localStorage.getItem(balanceKey);
      const balance = storedBalance === null ? 0 : Number(storedBalance);
      const formattedBalance = new Intl.NumberFormat('id-ID', {
        style: 'currency', currency: 'IDR', maximumFractionDigits: 0
      }).format(Number.isSafeInteger(balance) && balance >= 0 ? balance : 0);
      document.querySelectorAll('[data-balance-display]').forEach((element) => {
        element.dataset.visible = formattedBalance;
        if (balanceToggle?.getAttribute('aria-pressed') === 'true') element.textContent = formattedBalance;
      });
      balanceToggle?.addEventListener('click', () => {
        const visible = balanceToggle.getAttribute('aria-pressed') !== 'true';
        balanceToggle.setAttribute('aria-pressed', String(visible));
        balanceToggle.setAttribute('aria-label', visible ? 'Sembunyikan saldo' : 'Tampilkan saldo');
        if (balanceAmount) balanceAmount.textContent = visible ? balanceAmount.dataset.visible : balanceAmount.dataset.hidden;
        if (balanceIcon) balanceIcon.textContent = visible ? 'visibility_off' : 'visibility';
      });

      const account = (() => {
        try { return JSON.parse(localStorage.getItem('pupu-celluler-account') || 'null'); }
        catch { return null; }
      })();
      const editedReferral = localStorage.getItem('agen-pulsa-kode-referral');
      document.querySelectorAll('[data-account-field]').forEach((element) => {
        const field = element.dataset.accountField;
        let value = account?.[field];
        if (field === 'ownReferral' && editedReferral) value = editedReferral;
        if (value == null) value = { agentId: '—', name: 'Belum terdaftar', phone: '—', ownReferral: '—' }[field];
        if (value !== undefined) element.textContent = value;
      });

      const drawer = document.getElementById('offcanvas-menu');
      const drawerPanel = drawer?.querySelector('.offcanvas-panel');
      const drawerToggle = document.getElementById('menu-toggle');
      const setDrawer = (open) => {
        if (!drawer || !drawerToggle) return;
        drawer.classList.toggle('is-open', open);
        drawer.setAttribute('aria-hidden', String(!open));
        drawerToggle.setAttribute('aria-expanded', String(open));
        if (open) drawerPanel?.focus({ preventScroll: true });
        else drawerToggle.focus({ preventScroll: true });
      };
      drawerToggle?.addEventListener('click', () => setDrawer(!drawer.classList.contains('is-open')));
      drawer?.querySelector('.offcanvas-backdrop')?.addEventListener('click', (event) => {
        event.preventDefault();
        setDrawer(false);
      });

      let touchStart = null;
      let dragging = false;
      drawerPanel?.addEventListener('touchstart', (event) => {
        const touch = event.changedTouches[0];
        touchStart = { x: touch.clientX, y: touch.clientY };
        dragging = false;
      }, { passive: true });
      drawerPanel?.addEventListener('touchmove', (event) => {
        if (!touchStart) return;
        const touch = event.changedTouches[0];
        const deltaX = touch.clientX - touchStart.x;
        const deltaY = touch.clientY - touchStart.y;
        if (deltaX < 0 && Math.abs(deltaX) > Math.abs(deltaY)) {
          event.preventDefault();
          dragging = true;
          drawerPanel.classList.add('is-dragging');
          drawerPanel.style.transform = `translateX(${deltaX}px)`;
        }
      }, { passive: false });
      const clearDrawerDrag = () => {
        touchStart = null;
        dragging = false;
        drawerPanel?.classList.remove('is-dragging');
        drawerPanel?.style.removeProperty('transform');
      };
      drawerPanel?.addEventListener('touchend', (event) => {
        if (!touchStart) return;
        const deltaX = event.changedTouches[0].clientX - touchStart.x;
        const shouldClose = dragging && deltaX < -Math.max(70, drawerPanel.clientWidth * 0.22);
        clearDrawerDrag();
        if (shouldClose) setDrawer(false);
      }, { passive: true });
      drawerPanel?.addEventListener('touchcancel', clearDrawerDrag, { passive: true });

      const quickMenu = document.getElementById('quick-actions');
      const quickToggle = document.getElementById('quick-actions-toggle');
      const setQuickMenu = (open) => {
        if (!quickMenu || !quickToggle) return;
        quickMenu.classList.toggle('is-open', open);
        quickMenu.setAttribute('aria-hidden', String(!open));
        quickToggle.setAttribute('aria-expanded', String(open));
      };
      quickToggle?.addEventListener('click', () => setQuickMenu(!quickMenu.classList.contains('is-open')));
      window.addEventListener('scroll', () => {
        if (quickMenu?.classList.contains('is-open')) setQuickMenu(false);
      }, { passive: true });
      quickMenu?.querySelector('.quick-backdrop')?.addEventListener('click', (event) => {
        event.preventDefault();
        setQuickMenu(false);
        quickToggle?.focus();
      });
      document.addEventListener('keydown', (event) => {
        if (event.key !== 'Escape') return;
        if (drawer?.classList.contains('is-open')) setDrawer(false);
        if (quickMenu?.classList.contains('is-open')) setQuickMenu(false);
      });

      document.querySelectorAll('.promo-slider').forEach((slider) => {
        const slides = [...slider.querySelectorAll('.promo-slide')];
        if (slides.length < 2) return;
        let timer;
        const advance = () => {
          const maxScroll = Math.max(0, slider.scrollWidth - slider.clientWidth);
          const positions = slides.map((slide) => {
            const centered = slider.scrollLeft + slide.getBoundingClientRect().left - slider.getBoundingClientRect().left
              - (slider.clientWidth - slide.getBoundingClientRect().width) / 2;
            return Math.max(0, Math.min(centered, maxScroll));
          });
          const current = positions.reduce((closest, position, index) =>
            Math.abs(position - slider.scrollLeft) < Math.abs(positions[closest] - slider.scrollLeft) ? index : closest, 0);
          slider.scrollTo({ left: positions[(current + 1) % slides.length], behavior: 'smooth' });
        };
        const start = () => {
          window.clearInterval(timer);
          timer = window.setInterval(advance, 4000);
        };
        const pause = () => {
          window.clearInterval(timer);
          window.setTimeout(start, 5000);
        };
        slider.addEventListener('touchstart', pause, { passive: true });
        slider.addEventListener('pointerdown', pause, { passive: true });
        slider.addEventListener('mouseenter', () => window.clearInterval(timer));
        slider.addEventListener('mouseleave', start);
        start();
      });
    })();
  </script>
</body>

</html>
