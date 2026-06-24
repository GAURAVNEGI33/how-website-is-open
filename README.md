# Day 2 Task — DNS & Network Tab

## nslookup output
$ nslookup shorterloop.com
Server:  UnKnown
Address:  10.123.158.129

Non-authoritative answer:
Name:    shorterloop.com
Addresses:  64:ff9b::c724:9e64
          199.36.158.100

$ dig shorterloop.com +short
dig not available on Windows CMD

## Network Tab Requests — shorterloop.com

1. GET https://shorterloop.com/assets/css/testimonials.css → 200 OK (from memory cache)
   Type: stylesheet
   Header: referrer-policy: strict-origin-when-cross-origin

2. GET https://shorterloop.com/assets/scripts/common.js → 200 OK (from memory cache)
   Type: script
   Header: referrer-policy: strict-origin-when-cross-origin

3. GET https://shorterloop.com/assets/css/fonts.css → 200 OK (from memory cache)
   Type: stylesheet
   Header: referrer-policy: strict-origin-when-cross-origin

4. GET https://shorterloop.com/
   Type: document
   Header: Referrer Policy: strict-origin-when-cross-origin


## Screenshots
- network-tab-1.png

<img width="1547" height="467" alt="Screenshot 2026-06-24 164947" src="https://github.com/user-attachments/assets/4b4bbf11-f597-4d4e-87c8-a5605ef5d5c6" />

- 
- network-tab-2.png
<img width="1566" height="432" alt="Screenshot 2026-06-24 164924" src="https://github.com/user-attachments/assets/2ef33926-d4d2-436f-b8d3-eebfd804f970" />
- 
- network-tab-3.png

- <img width="1571" height="445" alt="Screenshot 2026-06-24 164901" src="https://github.com/user-attachments/assets/70989acc-4c7e-4261-87d3-4415054a7d83" />


- network-tab-4.png
<img width="1443" height="450" alt="Screenshot 2026-06-24 165006" src="https://github.com/user-attachments/assets/e11f61a1-fb9e-450f-b5da-7c604f59258a" />

- terminal-nslookup.png

<img width="767" height="417" alt="Screenshot 2026-06-24 164517" src="https://github.com/user-attachments/assets/d34b787b-bbbc-453e-bbf4-7ab0481ccf53" />
