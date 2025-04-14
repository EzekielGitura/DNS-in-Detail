# Decoding the Mysteries of DNS 🕵️‍♂️🌐

## Welcome to My DNS Deep Dive! 🚀

If you’ve ever wondered how typing `www.google.com` into your browser magically takes you to a website, then this project is for you. I embarked on a journey to demystify one of the most fundamental systems powering the Internet: **DNS (Domain Name System)**. Using tools like **Wireshark** and modules from **TryHackMe**, I uncovered the inner workings of DNS and gained hands-on experience with its protocols, records, and caching mechanisms.

---

## What Was I Doing? 🤔

This assignment was all about understanding DNS—the "phonebook of the Internet." Through a mix of theoretical learning and practical exploration, I investigated:
- How DNS translates human-friendly domain names (like `www.website.thm`) into machine-readable IP addresses.
- The different types of DNS records, such as A, MX, CNAME, and AAAA, and their purposes.
- How DNS queries propagate across recursive and authoritative servers.
- The role of TTL (Time to Live) in caching DNS records for efficiency.

Using **Wireshark**, I captured live DNS traffic to analyze packet details and observe the query-response process in action. On **TryHackMe**, I completed interactive challenges that tested my knowledge and gave me real-world insights into DNS operations.

---

## Tools Used 🔧

1. **Wireshark**: A powerful network protocol analyzer that let me capture and dissect DNS packets in real-time.
2. **TryHackMe**: An awesome platform for hands-on cybersecurity and networking labs. It provided structured lessons and challenges to solidify my understanding of DNS.
3. **DNS Records Explored**:
   - **A**: Maps domain names to IPv4 addresses.
   - **AAAA**: Maps domain names to IPv6 addresses.
   - **MX**: Specifies mail server locations.
   - **CNAME**: Creates aliases for domains.
   - **TXT**: Stores text-based information, often used for verification or security purposes.

---

## Skills Gained 💡

- **Understanding DNS Structure**:
  - Learned about domain name limits (e.g., max subdomain length = 63 characters).
  - Discovered the difference between TLDs (Top-Level Domains) like `.com` and ccTLDs (country-code TLDs) like `.co.uk`.
- **Analyzing DNS Traffic**:
  - Captured and interpreted DNS queries and responses using Wireshark.
  - Identified key fields like `TTL`, `TYPE`, and `ANSWER` in DNS packets.
- **Record Management**:
  - Explored various DNS record types and their roles in directing traffic and services.
  - Practiced querying records like `MX` for email routing and `CNAME` for aliases.
- **Problem-Solving**:
  - Solved challenges involving hidden flags in TXT records and numerical priorities in MX records.

---

## Fun Highlights 🎉

- **"The Phonebook Analogy"**: Realized DNS is essentially the Internet’s phonebook—translating names into numbers so computers can talk to each other.
- **"Hidden Treasure"**: Found a secret flag (`THM{7012BBA60997F35A9516C2E16D2944FF}`) hidden in a TXT record. Who knew DNS could be so sneaky?
- **"Mail Routing Mystery"**: Discovered that an MX record with priority `30` determines which mail server handles emails for a domain.
- **"IPv6 Adventure"**: Learned how AAAA records support IPv6 addresses, ensuring the Internet stays future-proof.

---

## Why Should You Care? 🌟

DNS might seem like a behind-the-scenes player, but it’s absolutely critical to the functioning of the Internet. Whether you’re troubleshooting network issues, securing your infrastructure, or just curious about how websites work, understanding DNS is invaluable. Plus, knowing how to analyze DNS traffic with tools like Wireshark can give you superpowers in cybersecurity and IT roles.

---

## Final Thoughts 📝

This project turned what initially seemed like a complex topic into something approachable and even fun. By breaking down DNS into manageable pieces and exploring it through practical exercises, I gained confidence in navigating this cornerstone of modern networking.

So, if you’re ready to become a DNS detective, fire up Wireshark, dive into some packet captures, and start uncovering the secrets of the Domain Name System. Trust me—it’s more exciting than it sounds!

Happy Decoding! 🕵️‍♂️🔗
