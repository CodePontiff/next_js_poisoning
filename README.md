he CVE-2024-4698 vulnerability in Next.js involves a cache poisoning issue. It affects versions 13.5.1 to 13.5.7, as well as versions 14.0.0 to 14.2.10. This vulnerability occurs when websites use the _next/image?url= API with the ?url= parameter, allowing attackers to load images from their own servers.

An attacker can utilize tunneling services like Ngrok or an Apache server to serve malicious images from their local machine. Customizing the script to include delays can help bypass protections on some servers that implement upload timing restrictions.
