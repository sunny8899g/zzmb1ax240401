port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: :9090
proxies:
  - {name: sunny0401英国uk11, server: zzmb1ax71.vipvip33.top, port: 36822, type: vmess, uuid: e1c00634-64e9-301e-94e8-9f42ef3a550a, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401香港hk10, server: zzmb1ax70.vipvip33.top, port: 36821, type: vmess, uuid: e1c00634-64e9-301e-94e8-9f42ef3a550a, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401美国US12, server: zzmb1ax72.vipvip33.top, port: 36823, type: vmess, uuid: e1c00634-64e9-301e-94e8-9f42ef3a550a, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401新加坡SG13, server: zzmb1ax73.vipvip33.top, port: 36804, type: vmess, uuid: 8d49a471-1c9e-3255-8d29-33448f22d896, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401新加坡SG14, server: zzmb1ax74.vipvip33.top, port: 36805, type: vmess, uuid: 7110b97b-04c4-34af-b387-fe011a37a80e, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401日本jp15, server: zzmb1ax75.vipvip33.top, port: 36806, type: vmess, uuid: 7110b97b-04c4-34af-b387-fe011a37a80e, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401美国jp17, server: zzmb1ax77.vipvip33.top, port: 36808, type: vmess, uuid: 8d49a471-1c9e-3255-8d29-33448f22d896, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}


  - {name: sunny0401印度ind1, server: zzmb1axdin1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401印度ind1b, server: zzmb1axdin1.vipvip33.top, port: 19851, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401美国usd1, server: zzmb1axdus1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401美国usd2, server: zzmb1axdus2.vipvip33.top, port: 10051, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}



  - {name: sunny0401美国US1p, server: zzmb1axphk1.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: true, udp: false}
  - {name: sunny0401香港HK2p, server: zzmb1axphk2.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: false, udp: true}
  - {name: sunny0401香港HK3p, server: zzmb1axphk1.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: false, udp: false}
  - {name: sunny0401香港HK4p, server: zzmb1axphk2.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: true, udp: true}
  - {name: sunny0401韩国kr1P, server: zzmb1axpkr1.vipvip33.top, port: 27452, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: ip3691376078.mobgslb.tbcache.com, skip-cert-verify: true, udp: false}
  - {name: sunny0401韩国kr2P, server: zzmb1axpkr2.vipvip33.top, port: 42752, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: ip3691376078.mobgslb.tbcache.com, skip-cert-verify: true, udp: false}
  - {name: sunny0401韩国kr3P, server: zzmb1axpkr1.vipvip33.top, port: 27452, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: ip3691376078.mobgslb.tbcache.com, skip-cert-verify: false, udp: false}



  - {name: 暂时测试vip2.新加坡sg1G, server: 24j4d1.sunny678.top, port: 35501, type: ss, cipher: chacha20-ietf-poly1305, password: d44f58f2-ae8f-4efe-9e38-d49a8a43774e}
  - {name: 办理vip2多数据.美国us1G, server: 24j4d1a.sunny678.top, port: 35504, type: ss, cipher: chacha20-ietf-poly1305, password: d44f58f2-ae8f-4efe-9e38-d49a8a43774e}

  - {name: sunny0401英国ukd1, server: zzmb1axduk1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401英国ukd3, server: zzmb1axduk3.vipvip33.top, port: 18851, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401德国ded1, server: zzmb1axdde1.vipvip33.top, port: 10051, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401德国ded1b, server: zzmb1axdde1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401香港hkd1, server: zzmb1axdhkk1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: hk.daxiongda.top}}, udp: false}
  - {name: sunny0401美国usd3a, server: zzmb1axdus3.vipvip33.top, port: 53, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401美国usd3, server: zzmb1axdus3.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401美国usd4, server: zzmb1axdus4.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401巴西brd1, server: zzmb1axdbr1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401巴西brd1b, server: zzmb1axdbr1.vipvip33.top, port: 10351, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401墨西哥mxd1, server: zzmb1axdmx1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401墨西哥mxd1b, server: zzmb1axdmx1.vipvip33.top, port: 22202, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401西班牙esd1, server: zzmb1axdse1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401台湾twd1, server: zzmb1axdtw1.vipvip33.top, port: 8080, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401台湾twd1b, server: zzmb1axdtw1.vipvip33.top, port: 18803, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401台湾twd1c, server: zzmb1axdtw1.vipvip33.top, port: 50414, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401迪拜ard1, server: zzmb1axdar1.vipvip33.top, port: 10051, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}


  - {name: sunny0401美国jp18, server: zzmb1ax78.vipvip33.top, port: 36809, type: vmess, uuid: 8d49a471-1c9e-3255-8d29-33448f22d896, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}




  - {name: sunny0401印度ind2, server: zzmb1adin1.vipvip33.top, port: 10051, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401韩国krd1, server: zzmb1adkr1.vipvip33.top, port: 80, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401韩国krd1b, server: zzmb1adkr1.vipvip33.top, port: 11251, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401西班牙sed1, server: zzmb1adse1.vipvip33.top, port: 19851, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401西班牙sed1b, server: zzmb1adse1.vipvip33.top, port: 16666, type: vmess, uuid: c7d951dc-c86b-4f65-880e-6901e9fabd37, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /, headers: {Host: dxh1.sunny0003.top}}, udp: false}
  - {name: sunny0401日本jp1Gvip1, server: zzmb1axgjp1.vipvip33.top, port: 443, type: trojan, password: 1e480128-c5bf-403b-b18a-5205d4dac937, skip-cert-verify: true, udp: false}
  - {name: sunny0401日本jp2Gvip1, server: zzmb1axgjp2.vipvip33.top, port: 443, type: trojan, password: 1e480128-c5bf-403b-b18a-5205d4dac937, skip-cert-verify: true, udp: false}


  - {name: sunny0401韩国kr4P, server: zzmb1axpkr3.vipvip33.top, port: 22102, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: ip3691376078.mobgslb.tbcache.com, skip-cert-verify: true, udp: false}
  - {name: sunny0401韩国kr5P, server: zzmb1axpkr3.vipvip33.top, port: 22102, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: ip3691376078.mobgslb.tbcache.com, skip-cert-verify: false, udp: false}
  - {name: sunny0401日本jp1P, server: zzmb1axpjp1.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: false, udp: false}
  - {name: sunny0401日本jp2P, server: zzmb1axpjp1.vipvip33.top, port: 443, type: trojan, password: 9fc1e2ba-c7ee-45e2-8449-0d45d4679c86, sni: 13-231-155-134.nhost.00cdn.com, skip-cert-verify: true, udp: false}
  - {name: sunny0401美国19, server: zzmb1ax79.vipvip33.top, port: 36810, type: vmess, uuid: 7110b97b-04c4-34af-b387-fe011a37a80e, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401日本jp3Gvip1, server: zzmb1axgjp2.vipvip33.top, port: 443, type: trojan, password: 1e480128-c5bf-403b-b18a-5205d4dac937, skip-cert-verify: false, udp: false}







  - {name: sunny0401p1, server: zzmb1axpp1.vipvip33.top, port: 443, type: trojan, password: b25ed935-dd18-4ea4-989c-00c0651c2a7b, sni: p2jp1.pqjc.buzz, skip-cert-verify: false, network: ws, ws-opts: {path: /pq/jp1, headers: {Host: p2jp1.pqjc.buzz}}, udp: false}
  - {name: sunny0401p2, server: zzmb1axpp2.vipvip33.top, port: 443, type: trojan, password: b25ed935-dd18-4ea4-989c-00c0651c2a7b, sni: 3jp2.pqjc.buzz, skip-cert-verify: false, network: ws, ws-opts: {path: /pq/jp1, headers: {Host: 3jp2.pqjc.buzz}}, udp: true}
  - {name: sunny0401p3, server: zzmb1axpp3.vipvip33.top, port: 443, type: trojan, password: b25ed935-dd18-4ea4-989c-00c0651c2a7b, sni: p3us1.pqjc.buzz, skip-cert-verify: false, network: ws, ws-opts: {path: /pq/jp1, headers: {Host: p3us1.pqjc.buzz}}, udp: true}
  - {name: sunny0401p4, server: zzmb1axpp4.vipvip33.top, port: 443, type: trojan, password: b25ed935-dd18-4ea4-989c-00c0651c2a7b, sni: 3us2.pqjc.buzz, skip-cert-verify: false, network: ws, ws-opts: {path: /pq/jp1, headers: {Host: 3us2.pqjc.buzz}}, udp: true}
  - {name: sunny04010901香港hk99, server: zzmb1axpp99.vipvip33.top, port: 21600, type: vmess, uuid: 60766FB1-7C38-899D-7210-AF547F756FA9, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /video, ws-headers: {Host: vvna7g1.vipvip11.club}, udp: false}

  - {name: sunny0401英国uk81, server: zzmb1ax81.vipvip33.top, port: 36802, type: vmess, uuid: 7110b97b-04c4-34af-b387-fe011a37a80e, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}
  - {name: sunny0401香港hk80, server: zzmb1ax80.vipvip33.top, port: 36801, type: vmess, uuid: 7110b97b-04c4-34af-b387-fe011a37a80e, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: /hls/cctv5phd.m3u8, headers: {Host: sunnyxxf.vipvip33.top}}, udp: false}

