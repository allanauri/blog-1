+++
title = "Cara Setting CCTV Online"
date = 2012-03-12T23:49:00Z
updated = 2012-03-13T10:40:37Z
tags = ["Tips dan Trick"]
blogimport = true 
[author]
	name = "Rifky Fuady"
	uri = "https://plus.google.com/101982203483309256996"
+++

<br /><div class="MsoNormal">Di postingan ini saya akan berbagi ilmu cara setting <b>CCTV online</b>. Disini saya menggunakan Kamera dan DVR merk <b>Avtech</b>, serta modem Adsl Speedy (<b>TP-Link</b>). berikut ini cara setting agar CCTV bisa Online :</div><div class="MsoNormal"><br /></div><div class="MsoNormal">1. Kita buka <a href="http://www.dyndns.com/">www.dyndns.com</a></div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-6RifAuwzyq0/T14gpZCUUHI/AAAAAAAAAJM/OTWG7gSlmXo/s1600/logindyn.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="200" src="http://4.bp.blogspot.com/-6RifAuwzyq0/T14gpZCUUHI/AAAAAAAAAJM/OTWG7gSlmXo/s320/logindyn.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal">&nbsp;&nbsp; Login, bila belum punya akun, buat akun anda dulu. disini kita akan mendaftarkan DNS yg akan dipakai buat CCTV.</div><div class="MsoNormal"><br /></div><div class="MsoNormal">2. Klik ke <b>My servise - Host Servise - Add Hostname</b>.</div><div class="MsoNormal">&nbsp;&nbsp; Buat Hostname anda, lihat gambar :</div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-z24HxTNYrgY/T14g6HxrEFI/AAAAAAAAAJU/oN7KDeEzqJc/s1600/DNSadd.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="199" src="http://4.bp.blogspot.com/-z24HxTNYrgY/T14g6HxrEFI/AAAAAAAAAJU/oN7KDeEzqJc/s320/DNSadd.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal">3. Untuk mengeceknya sudah aktif apa belum, kita lakukan ping test ke hostname tersebut.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://2.bp.blogspot.com/-6_rBKJJ5m18/T14hLzV8h6I/AAAAAAAAAJc/EBxfdh1az-w/s1600/ping.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="139" src="http://2.bp.blogspot.com/-6_rBKJJ5m18/T14hLzV8h6I/AAAAAAAAAJc/EBxfdh1az-w/s320/ping.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp; <b>Start - RUN.</b></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp; ping <span style="color: red;">home-rifky.dvrdns.org</span> -t</div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp; jika "<b>reply</b>from 144.79.61.122", berarti berhasil.</div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">4. Kalau sudah, kemudian kita Setting modem <b>Tp-Link</b> nya, </div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-vNkCv5Wvi30/T14hdtGrdII/AAAAAAAAAJk/h28Ni45VM_Y/s1600/loginmodem.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="187" src="http://4.bp.blogspot.com/-vNkCv5Wvi30/T14hdtGrdII/AAAAAAAAAJk/h28Ni45VM_Y/s320/loginmodem.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal">&nbsp;&nbsp; Masuk ke settingan modem lewat browser dulu (defaultnya tulis di browser <b>192.168.1.1</b>, user sama passwordnya : admin).</div><div class="MsoNormal"><br /></div><div class="MsoNormal">5. Masuk ke tab menu <b>Advanced Setup - NAT </b></div><div class="separator" style="clear: both; text-align: center;"><a href="http://2.bp.blogspot.com/-MgmFXQLWmPg/T14h-Xs3pGI/AAAAAAAAAJ0/HBE95vUlHsw/s1600/Nat.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="141" src="http://2.bp.blogspot.com/-MgmFXQLWmPg/T14h-Xs3pGI/AAAAAAAAAJ0/HBE95vUlHsw/s320/Nat.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Virtual Ciecuit : <b>PVC1</b></div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">6. Setelah itu klik <b>DMZ</b>,</div><div class="separator" style="clear: both; text-align: center;"><a href="http://2.bp.blogspot.com/-Azt3lnwgpVA/T14iNDkwaQI/AAAAAAAAAJ8/_JboRCmC25M/s1600/DMZ.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="123" src="http://2.bp.blogspot.com/-Azt3lnwgpVA/T14iNDkwaQI/AAAAAAAAAJ8/_JboRCmC25M/s320/DMZ.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DMZ : <b>Enable</b></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DMZ Host IP Address : <b>192.168.1.10</b> (karena ini adalah IP default dari DVR Avtech)</div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">7. Kemudian masuk ke tab menu <b>Access Management - DDNS</b>,</div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-7Yk57htsmRw/T14iamoHBaI/AAAAAAAAAKE/yVngCT1N3GY/s1600/DDNS.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="161" src="http://4.bp.blogspot.com/-7Yk57htsmRw/T14iamoHBaI/AAAAAAAAAKE/yVngCT1N3GY/s320/DDNS.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Dynamic DNS : <b>Actived</b></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; My Host name : <span style="color: red;">home-rifky.dvrdns.org</span> (nama DNS yang tadi didaftarkan di Dyndns)</div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Wildcard support : <b>No</b></div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">8. Jika sudah, kita hubungkan DVR ke Modem dengan <b>kabel LAN</b>(UTP).</div><div class="separator" style="clear: both; text-align: center;"><a href="http://3.bp.blogspot.com/-P5aqzLPHGzM/T14k0tNNAlI/AAAAAAAAAKM/rdNo3sKmbf4/s1600/cat512.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="240" src="http://3.bp.blogspot.com/-P5aqzLPHGzM/T14k0tNNAlI/AAAAAAAAAKM/rdNo3sKmbf4/s320/cat512.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal"><br /></div><div class="MsoNormal">9. Untuk setting di DVRnya, Install Video Viewer.exe, biasanya ada di CD DVR nya.&nbsp;kalau belum punya, bisa donwload <a href="http://www.ziddu.com/download/18851966/Avtech.rar.html" target="_blank">disini</a>.</div><div class="MsoNormal"><br /></div><div class="MsoNormal">10. Jalankan Video Viewer.exe, <b>Add&nbsp;</b>(tanda +).&nbsp;Settingan lihat digambar :</div><div class="separator" style="clear: both; text-align: center;"><a href="http://3.bp.blogspot.com/-Z1LvBMNa6uc/T14lIRiUBfI/AAAAAAAAAKU/O_iTscg1c-s/s1600/runAvexe.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="212" src="http://3.bp.blogspot.com/-Z1LvBMNa6uc/T14lIRiUBfI/AAAAAAAAAKU/O_iTscg1c-s/s320/runAvexe.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-mu0sjfb4mNE/T14lXuCstBI/AAAAAAAAAKc/UzDNjQlg9RA/s1600/addIPlocal.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="173" src="http://4.bp.blogspot.com/-mu0sjfb4mNE/T14lXuCstBI/AAAAAAAAAKc/UzDNjQlg9RA/s320/addIPlocal.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal"><br /></div><div class="MsoNormal">11. Double klik IP settingan tadi untuk login.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://3.bp.blogspot.com/--NEvCN2auAI/T14lhHdVbpI/AAAAAAAAAKk/Ha-kfpnwIMg/s1600/loginAvtect.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="149" src="http://3.bp.blogspot.com/--NEvCN2auAI/T14lhHdVbpI/AAAAAAAAAKk/Ha-kfpnwIMg/s320/loginAvtect.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal"><br /></div><div class="MsoNormal">12. Kemudian masuk ke menu <b>Miscellaneous Control - Server seetting</b>.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-0p8Ny3bvt48/T14lqlSEIkI/AAAAAAAAAKs/1kP3s1zwQa0/s1600/milleciound.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="192" src="http://4.bp.blogspot.com/-0p8Ny3bvt48/T14lqlSEIkI/AAAAAAAAAKs/1kP3s1zwQa0/s320/milleciound.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal"><br /></div><div class="MsoNormal">13. Klik <b>Network</b>. Setting sperti gambar dibawah.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-G8Kz7m5enyE/T14lzaeJliI/AAAAAAAAAK0/2AVQjGUuDns/s1600/network.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="156" src="http://4.bp.blogspot.com/-G8Kz7m5enyE/T14lzaeJliI/AAAAAAAAAK0/2AVQjGUuDns/s320/network.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Web Port : 81, karena biar bisa diakses lewat Handphone.</div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">14. Masuk ke <b>DDNS</b>. Setting seperti gambar dibawah.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://4.bp.blogspot.com/-ECFTzf5YqUw/T14l-2Noi7I/AAAAAAAAAK8/_oXklPZmoTQ/s1600/ddnsvv.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="156" src="http://4.bp.blogspot.com/-ECFTzf5YqUw/T14l-2Noi7I/AAAAAAAAAK8/_oXklPZmoTQ/s320/ddnsvv.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="MsoNormal" style="text-align: center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DNS 1 dan DNS 2 adalah IP dari www.dyndns.com (lakukan ping test kalau tidak percaya)</div><div class="MsoNormal" style="text-align: center;"><br /></div><div class="MsoNormal">15. Klik <b>Apply - OK</b>.</div><div class="MsoNormal"><br /></div><div class="MsoNormal">16. seperti langkah no. 10, coba IP Addres di ganti : “home-rifky.dvrdns.org” dan Login. berhasil berarti selesai.</div><div class="separator" style="clear: both; text-align: center;"><a href="http://1.bp.blogspot.com/-vh6KeNwGBcg/T14oI7oEOSI/AAAAAAAAALM/Z1a37AWJgbw/s1600/videoviewer_0130_full_screen_dashboard.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="240" src="http://1.bp.blogspot.com/-vh6KeNwGBcg/T14oI7oEOSI/AAAAAAAAALM/Z1a37AWJgbw/s320/videoviewer_0130_full_screen_dashboard.jpg" width="320" /></a></div><div class="MsoNormal"><br /></div><div class="separator" style="clear: both; text-align: center;"></div><div class="MsoNormal"><br /></div><div class="MsoNormal"><br /></div><div class="MsoNormal">Sekian dulu tutorial dari saya, semoga bermanfaat untuk anda.</div><div class="MsoNormal"><o:p><br /></o:p></div><div class="MsoNormal"><o:p><span style="font-size: 9pt; line-height: 115%;">Catatan : sekarang akun Dyndns sudah tidak free lagi, kalau ingin yang free bisa</span><span style="font-size: 9pt; line-height: 115%;">&nbsp; </span><span style="font-size: 9pt; line-height: 115%;">memakai akun <a href="http://www.no-ip.com/" target="_blank">no-ip</a>, tapi harus memakai modem yang support <a href="http://www.no-ip.com/" target="_blank">no-ip</a>, contoh : Modem <b>D-Link.</b></span>&nbsp;</o:p></div><div class="MsoNormal"><br /></div>