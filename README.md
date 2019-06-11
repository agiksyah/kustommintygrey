Cara sederhana mengubah tema di linux, dengan sedikit koding. Saya yakin tidak semua pengguna linux, khususnya linux mint adalah pemrogram atau mengerti koding.
Saya edit beberapa baris saja untuk perubahan warna dan border.

Pada file cinnamon.css yg saya upload ada banyak sekali kode nah pada baris 208 adalah pengaturan layout menu.

pada baris 212 ada pengaturan :
background-color: rgba(240, 240, 240, 0.60); 

240 240 240 adalah kode rgb untuk warna dan 0.60 adalah tingkat transparasi warna.

di bawah .menu-favorites-box {
pada baris   961 ada kode:

background-color: rgba(255, 255, 255, 0.60);
  
255 255 255 adalah kode warna putih untuk rgb, dan 0.60 adalah transparasi.

untuk pengaturan panel ada pada baris 423 :

.panel-top, .panel-bottom, .panel-left, .panel-right {
  color: #ffffff;
  border: none;
  background-color: rgba(47, 47, 47, 0.00);
  font-size: 1em;
  padding: 0px; }

  nah, warna 100% transparan karena 0.00.