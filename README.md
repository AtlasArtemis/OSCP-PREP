`this is code`

<p>This page is in no way affiliated with Offensive Security. It is merely my journey towards preparing for the OSCP exam. This guide will follow Offensive Security's readily available PWK (Penetration Testing with Kali Linux) Syllabus. The syllabus won't be followed to a tee but I plan to cover the more complex topics. Along with following the syllabus, I will reference a number of books that guide me along the way. </p>


<h2 class="has-text-align-center"><a href="https://www.offensive-security.com/documentation/penetration-testing-with-kali.pdf">PWK Syllabus</a></h2>

# Table of Contents

* 1 - Getting Comfortable with Kali Linux
  * 1.1 - Finding Your Way Around Kali
    * 1.1.1 Booting up Kali Linux
    * 1.1.2 The Kali Menu
    * 1.1.3 Find, Locate, and Which
    * Example
  * 1.2 - Managing Kali Linux Services
  * 1.3 - The Bash Environment
  * 1.4 - Intro to Bash Scripting
 

* 2 - The Essential Tools
  * 2.1 - Netcat
     * 2.1.1 - Connecting to a TCP/UDP Port
     * 2.1.2 - Listening on a TCP/UDP Port
     * 2.1.3 - Transfering Files with Netcat
     * 2.1.4 - Remote Administration with Netcat
     * 2.1.5 - Examples
  * 2.2 - Ncat
  * 2.3 - Wireshark
  * 2.4 - Tcpdump


* 3 - Passive Information Gathering
  * 3.1- Open Web Information Gathering
    * 3.1.1 - Google
    * 3.1.2 - Google Hacking
    * 3.1.3 - Sources / Examples
  * 3.2 - Email Harvesting
  * 3.3 - Additional Resources
  * 3.4 - Recon-ng
    
* 4 - Active Information Gathering
  * 4.1 - DNS Enumeration
    * 4.1.1 - Interacting with a DNS Server
    * 4.1.2 - Automating Lookups
    * 4.1.3 - Forward Lookup Brute Force
    * 4.1.4 - Reverse Lookup Brute Force
    * 4.1.5 - DNS Zone Transfers
    * 4.1.6 - Relevant Tools in Kali Linux
    * 4.1.7 - Examples
  * 4.2 - Port Scanning
    * 4.2.1 - TCP CONNECT / SYN Scanning
    * 4.2.2 - UDP Scanning
    * 4.2.3 - Common Port Scanning Pitfalls
    * 4.2.4 - Port Scanning with Nmap
    * 4.2.5 - OS Fingerprinting
    * 4.2.6 - Banner Grabbing / Service Enumeration
    * 4.2.7 - Nmap Scripting Engine (NSE)
    * 4.2.8 - Example
  * 4.3 - SMB Enumeration
    * 4.3.1 - Scanning for the NetBIOS Service
    * 4.3.2 - Null Session Enumeration
    * 4.3.3 - Nmap SMB NSE Scripts
    * 4.3.4 -Example
  * 4.4 - SMTP Enumeration
    * 4.4.1 - Example
  * 4.5 - SNMP Enumeration
     * 4.5.1 - MIB Tree
     * 4.5.2 - Scanning for SNMP
     * 4.5.3 - Windows SNMP Enumeration Example
     * 4.5.4 - Example

* 5 - Vulnerability Scanning
  * 5.1 - Vulnerability Scanning with Nmap
  * 5.2 - The OpenVAS Vulnerability Scanner
      * 5.2.1 - OpenVAS Initial Setup
      * 5.2.2 - Example

* 6 - Buffer Overflows
  * 6.1 - Fuzzing
      * 6.1.1 - Vulnerability History
      * 6.1.2 - A Word About DEP and ASLR
      * 6.1.3 - Interacting with the POP3 Protocol
      * 6.1.4 - Example

<p>7 - Win32 Buffer Overflow Exploitation</p>

<p>8 - Linux Buffer Overflow Exploitation</p>

<p>9 - Working with Exploits</p>

<p>10 - File Transfers</p>

<p>11 - Privilege Escalation</p>

<p>12 - Client Side Attacks</p>

<p>13 - Web Application Attacks</p>

<p>14 - Password Attacks</p>

<p>15 - Port Redirection and Tunneling</p>

<p>16 - The Metasploit Framework</p>

<p>17 - Bypassing Antivirus Software</p>

<p>18 - Assembling the Pieces: Penetration Test Breakdown</p>




<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->



# Books

<ul><li>Penetration Testing: A  Hands-On Introduction to Hacking</li><li>Black Hat Python</li><li>The Hacker Playbook 2 &amp; 3</li><li>Hacking: The Art of Exploitation</li><li>Kali Linux 2018: Windows Penetration Testing</li><li>Kali Linux 2 - Assuring Security by Penetration Testing</li><li>Gray Hat Hacking: The Ethical Hacker's Handbook</li><li>How Linux Works: What Every Superuser Should Know</li><li>The Internet Book</li><li>AWS Penetration Testing with Kali Linux</li><li>Mastering Embedded Linux Programming</li><li>Red Team Tactics</li></ul>

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:separator {"className":"is-style-wide"} -->
<hr class="wp-block-separator is-style-wide"/>
<!-- /wp:separator -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:separator {"className":"is-style-wide"} -->
<hr class="wp-block-separator is-style-wide"/>
<!-- /wp:separator -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:heading {"align":"center","level":3} -->
<h3 class="has-text-align-center"></h3>
<!-- /wp:heading -->

<!-- wp:pullquote -->
<figure class="wp-block-pullquote"><blockquote><p>"Computers have lots of memory, but no imagination."</p><cite>Bill Gates</cite></blockquote></figure>
<!-- /wp:pullquote -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:columns {"align":"wide","className":"has-2-columns contact-section"} -->
<div class="wp-block-columns alignwide has-2-columns contact-section"><!-- wp:column -->
<div class="wp-block-column"><!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p> </p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->

<!-- wp:separator {"className":"is-style-wide"} -->
<hr class="wp-block-separator is-style-wide"/>
<!-- /wp:separator -->

<!-- wp:spacer {"height":16,"className":"desktop-only"} -->
<div style="height:16px" aria-hidden="true" class="wp-block-spacer desktop-only"></div>
<!-- /wp:spacer -->
