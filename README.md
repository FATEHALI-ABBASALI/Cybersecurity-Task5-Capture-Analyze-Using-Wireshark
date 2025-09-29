<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>

  <h1>1 🚀 Task 5 Wireshark Capture and Analysis</h1>

  <h3>2 🛠 Tools and Environment</h3>
  <p> Kali Linux</p>
  <p> Wireshark</p>

  <h3>3 🔧 Installation</h3>
  <pre>
sudo apt update
sudo apt install wireshark -y
sudo usermod -aG wireshark $USER
newgrp wireshark
  </pre>

  <h3>4 ▶ Launch Wireshark</h3>
  <p> Run wireshark from terminal or open from apps menu</p>
  <pre>
wireshark &
  </pre>

  <h3>5 📡 Start Capture</h3>
  <p> Select active interface such as wlan0 or eth0</p>
  <p> Click start capture</p>

  <h3>6 ⚡ Generate Traffic</h3>
  <pre>
ping -c 5 google.com
curl http://example.com
  </pre>

  <h3>7 ⛔ Stop Capture and Save</h3>
  <p> Click the stop button in Wireshark</p>
  <p> Save file as task5_capture.pcapng via File then Save As</p>

  <h3>8 🔍 Filters to Use</h3>
  <p>1. dns</p>
  <p>2. http</p>
  <p>3. tcp</p>
  <p>4. udp</p>
  <p>5. icmp</p>
  <p>6. arp</p>

  <h3>9 📊 Observations</h3>
  <p>1. DNS observed for domain name resolution</p>
  <p>2. HTTP observed as GET request and server response</p>
  <p>3. TCP observed as SYN SYN ACK ACK handshake</p>

  <h3>10 💾 Repo and Submission</h3>
  <p> Include task5_capture.pcapng and README.md</p>
  <p> Push to GitHub and submit repo link via the form</p>

</body>
</html>
