following CVE-2024-4698, the next js have cache poisoning vulnerability it's affected at 13.5.1 to 13.5.7 and also 14.0.0 14.2.10 version of next_js
some website have _next/image?url= API with ?url= parameter, attacker can load their image from the attacker machine
you can use tunneling service such as ngrok tunnel and apache service to provide image from your local machine

by using this script your image from local machine can be copied with some number from your input to be uploaded to victim machine 
also try to custom the delay in this script to trick the server (some server have delay the upload process)
